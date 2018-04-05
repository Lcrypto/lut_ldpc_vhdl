# Introduction
LUT LDPC VHDL is a software tool that uses the optimized look-up tables designed by the the LUT LDPC software in order to generate VHDL code and simulation files for a fully-unrolled LDPC decoder (cf. [[3-4]](#literature)).

# Installation

## Requirements
For the generation of the VHDL code, the LUT LDPC VHDL software requires an installation of MATLAB. It has been tested and verified to be working with MATLAB R2016b. The simulation of the generated VHDL code with the provided testbenches requires a functioning installation of ModelSim.

## Installation
The LUT LDPC VHDL software is installed as part of the LUT LDPC software tools. The installation procedure is described in detail [here](https://dev.meidlinger.info/michael.meidlinger/lut_ldpc/blob/master/README.md#installation). After the installation, the VHDL generation scripts can be found in the `lut_ldpc_vhdl` directory.

# Structure
The `lut_ldpc_vhdl` folder has the following structure
```
.
├── ModelSim                        # Scripts and files for compilation and simulation with ModelSim
├── TopLevelDecoder                 # Generated VHDL files for LUT-based decoder
├── TopLevelDecoderGenerator        # VHDL generation scripts for LUT-based decoder
├── TopLevelDecoderAdders           # Generated VHDL files for baseline adder-based decoder
├── TopLevelDecoderGeneratorAdders  # VHDL generation scripts for baseline adder-based decoder
└── README.md                       # This README file
```

# Usage

# Referencing
If you use this software for your academic research, please consider referencing our original contributions [[1,2,3,4]](#literature).

# Literature
[[1] M. Meidlinger, A. Balatsoukas-Stimming, A. Burg, and G. Matz, “Quantized message passing for LDPC codes,” in Proc. 49th Asilomar Conf. Signals, Systems and Computers, Pacific Grove, CA, USA, Nov. 2015.](http://ieeexplore.ieee.org/document/7421419/)

[[2] M. Meidlinger and G. Matz, “On irregular LDPC codes with quantized message passing decoding,” in Proc. IEEE SPAWC 2017, Sapporo, Japan, Jul. 2017.
](http://ieeexplore.ieee.org/document/8227780/)

[[3]  A. Balatsoukas-Stimming, M. Meidlinger, R. Ghanaatian, G. Matz, and A. Burg, “A fully-unrolled LDPC decoder based on quantized message passing,” in Proc. SiPS 2015, Hang Zhou, China, 10 2015.
](http://ieeexplore.ieee.org/abstract/document/7345024/)

[[4] R. Ghanaatian, A. Balatsoukas-Stimming, C. Mu ̈ller, M. Meidlinger, G. Matz, A. Teman, and A. Burg, “A 588 Gbps LDPC decoder based on finite-alphabet message passing,” IEEE Trans. VLSI Systems, vol. 26, no. 2, pp. 329–340, 2 2018.
](http://ieeexplore.ieee.org/document/8113527/)

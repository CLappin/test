# RTG4 Development Kit Mi-V Sample Designs

This repository contains Libero projects for the MIV_RV32IMA_L1_AHB and MIV_RV32IMA_L1_AXI soft core RISC-V processors.
FlashPro Express projects containting pre-generated programming bitstreams are also available for each of the designs.


# Libero Projects
The Libero_Projects folder contains the Tcl scripts that build the sample Mi-V projects.

## Design Features
The Libero designs include the following features:
* A MIV_RV32IMA_L1_AHB or MIV_RV32IMA_L1_AXI soft RISC-V processor.
* RISC-V debug block allowing on-target debug using SoftConsole.
* The operating frequency of the design is 50MHz.
* Target memory is LSRAM.
* User peripherals (GPIO, Timers, UART).

# FlashPro Express
The FlashPro_Express_Projects folder contains pre-generated FPGA programming bitstreams.
These can be downloaded directly to the target board using FlashPro Express.

# Design Tools
The following design tools are required.

## Libero SoC v12.3
Libero SoC is Microsemi's FPGA design suite that is used to generate the sample projects.
It is available from [here](https://www.microsemi.com/products/fpga-soc/design-resources/design-software/libero-soc#downloads).

## FlashPro Express (FPExpress)
FlashPro Express is Microsemi's Programming and debug tool. It is included in the Libero SoC software and is also
available as a standalone application found [here](http://www.microsemi.com/products/fpga-soc/design-resources/programming/flashpro#software). Please note, that if Libero SoC is already on your system, you do not need
the standalone version.

## SoftConsole
SoftConsole is Microsemi’s free software development environment facilitating the rapid development of bare-metal and RTOS based C/C++ software for Microsemi CPU and SoC based FPGAs. It provides development and debug support for all Microsemi SoC FPGAs and 32-bit soft IP CPUs. SoftConsole can be downloaded [here](https://www.microsemi.com/product-directory/design-tools/4879-softconsole).  

### SoftConsole Projects
A set of RISC-V example software projects are also available for these designs from the SoftConsole [page](https://github.com/RISCV-on-Microsemi-FPGA/SoftConsole).

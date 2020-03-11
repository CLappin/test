# RTG4 Development Kit Mi-V Designs FlashPro Express Programming Files (Libero v12.3)

FlashPro Express projects for sample Mi-V designs on the RTG4 Development Kit.

## FlashPro Express
The programming files contained here are exported from Libero projects and their configurations found in this repository.
Select the desired programming .job file and program your device using the standalone installer for FlashPro Express
which can be found [here](https://www.microsemi.com/product-directory/programming/4977-flashpro#software).

## Programming the Device using FPExpress
1. Power-up your board and connect it to your programming device running FlashPro Express.
2. Launch FPExpress.
3. Select Project from the top left bar and select "New Job Project from FlashPro Express Job"
4. To select the "Programming job file:" navigate to your FlashPro_Express_Project/Programming_Files directory 
   and select the (.job) programming file.
5. For "FlashPro Express job project location:" select the FlashPro_Express_Projects.
6. Select OK
7. From the bottom left drop-down menu select the PROGRAM option if it's not selected by default and click RUN.
   Wait for device to be programmed.

## Target Hardware
Details on the RTG4 Development kit and it's features can be found:
* RTG4-DEV-KIT [here](https://www.microsemi.com/product-directory/dev-kits-solutions/3865-rtg4-kits)

## Target Mi-V CPU
Details of the features of Mi-V CPUs are available [here](https://github.com/RISCV-on-Microsemi-FPGA/CPUs).

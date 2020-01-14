### CYW9P62S1-43438EVB-01 BSP
The CYW9P62S1-43438EVB-01 Kit is a low-cost hardware platform that enables design and debug of the Azurewave AW-CU427 Module. AW-CU427 is a System in Package (SiP) module that contains the MCU part, PSoC 62 MCU (CY8C6247BZI-D54) and the radio part CYW43438 ( WiFi + Bluetooth Combo Chip).

### What's New In This Release?
* This release adds updated linker scripts and startup code for the CM0+ and CM4 cores. The files are now in core specific directories.
* Minor updates up avoid potential warnings on some toolchains

### What's Included?
The CYW9P62S1-43438EVB-01 library includes the following:
* BSP specific makefile to configure the build process for the board
* cybsp.c/h files to initialize the board and any system peripherals
* cybsp_types.h file describing basic board setup
* CM4 Linker script & startup code for GCC, IAR, ARM toolchains
* CM0+ Linker script & startup code for GCC, IAR, ARM toolchains
* Configurator design files (and generated code) to setup board specific peripherals
* .lib file references for all dependent libraries
* API documentation

### Supported Software and Tools
This version of the CYW9P62S1-43438EVB-01 BSP was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox Software Environment         | 2.0     |
| GCC Compiler                              | 7.4     |
| IAR Compiler                              | 8.32    |
| ARM Compiler                              | 6.11    |

### More information
* [CYW9P62S1-43438EVB-01 BSP API Reference Manual][api]
* [CYW9P62S1-43438EVB-01 Documentation](http://www.cypress.com/documentation/development-kitsboards/cyw9p62s1-43438-evb-01)
* [Cypress Semiconductor](http://www.cypress.com)
* [Cypress Semiconductor GitHub](https://github.com/cypresssemiconductorco)
* [ModusToolbox](https://www.cypress.com/products/modustoolbox-software-environment)

[api]: modules.html

---
© Cypress Semiconductor Corporation, 2019.
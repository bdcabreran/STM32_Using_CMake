# STM32 Example using CMake
This is an example project for the STM32 microcontroller using the CMake build system. It demonstrates how to set up a development environment for STM32 projects using CMake, and provides a basic template for starting a new project.

## Prerequisites
* CMake 3.10 or higher
* A GCC toolchain for ARM microcontrollers
* STM32CubeMX
* A STM32 development board
## Setting up the project
1. Clone this repository to your local machine.
2. Open the .ioc file in STM32CubeMX and generate the code.
3. Copy the generated code into the src directory.
4. In the terminal, navigate to the project directory and run cmake ..
5. Run make to build the project.
6. Connect your STM32 development board and flash the binary using a suitable tool (e.g. ST-Link Utility).
7. Customizing the project
8. You can customize the project by modifying the CMakeLists.txt file and adding your own source files to the src directory.

## Further reading
* [CMake documentation]("https://cmake.org/documentation/")
* [STM32CubeMX documentation](https://www.st.com/content/st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-configurators-and-code-generators/stm32cubemx.html)
* [STM32 programming documentation](https://www.st.com/content/st_com/en/products/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html)
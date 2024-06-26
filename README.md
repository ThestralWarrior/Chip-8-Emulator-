# CHIP-8 Emulator
An implementation of the Chip-8 Emulator (or to be precise, Interpreter) in C

# Overview
The CHIP-8 Emulator is a classic virtual machine designed to run programs written for the CHIP-8 instruction set. CHIP-8 is a simple interpreted language developed in the 70s for early microcomputers like the COSMAC VIP, offering a basic environment for creating simple games and applications. With a minimalist instruction set, basic graphics system, and simple sound capabilities, it was designed to be easy to program, making it popular among hobbyists and educators for learning about computer architecture and emulator development.

# Emulator Specifications
* 4 kilobytes of RAM
* Sixteen 8-bit general-purpose registers
* One 16-bit index register
* A stack with sixteen 16-bit values
* Two special registers: the program counter and the stack pointer
* A hexadecimal keypad with values 0 through F
* A monochrome display with a resolution of 64 x 32
* An 8-bit delay timer
* An 8-bit sound timer

# Test Outputs
![1-chip8-logo.ch8](test-outputs/1-chip8-logo.png)
![2-ibm-logo.ch8](test-outputs/2-ibm-logo.png)
![3-corax+.ch8](test-outputs/3-corax+.png)
![4-flags.ch8](test-outputs/4-flags.png)

# Requirements
* Linux
* C-11
* SDL2

# Usage
For Linux only

`make` To Compile

`./chip8 <path/to/file.ch8>` To Run

# Resources
Website references:
* http://devernay.free.fr/hacks/chip8/C8TECH10.HTM (Outdated and Inconsistent, Error-Prone)

Repository references:
* https://github.com/f0lg0/CHIP-8 (Code Organization and Implementation)
* https://github.com/queso-fuego/chip8_emulator_c (SDL2 Usage)
* https://github.com/Timendus/chip8-test-suite (Test-Suite ROMs Collection)
* https://github.com/mattmikolay/chip-8/wiki/CHIP‐8-Technical-Reference (Up-to-date Technical Reference)

Social Media: - 
* /r/EmuDev [Reddit]
* Emulator Development [Discord] (Thanks, Janitor Raus and Gulrak!)

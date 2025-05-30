#  5-Bit CPU Design Using Logisim
This project presents a custom-built CPU architecture designed in **Logisim** as part of an academic assignment. It demonstrates essential concepts in digital logic, processor design, and instruction execution.

##  a) Project Specifications

**a.1)** Word Size of CPU: 5 bits  
**a.2)** ALU Operations:
- AND  
- ADD  
- ROL (Rotate Left)

**a.3)** Number of Registers: 3  
**a.4)** RAM Size: 9 words  
**a.5)** Word Size of ISA and RAM: 15 bits  
**a.6)** Supported Instruction Types:
- Register Mode  
- Immediate Mode  
- Branching Mode (JMP, JLE)

##  b) Implemented Components

**b.1)** ALU Circuit: Supports ADD, AND, ROL  
**b.2)** Register Set: Includes 1-bit, 5-bit registers, and 3-register system  
**b.3)** Program Counter: 4-bit PC with adder  
**b.4)** Memory Modules: 1×1 RAM, 1×15 RAM, and final 9×15 SRAM  
**b.5)** Control Unit (CU): Handles instruction decoding and control signals  
**b.6)** Integrated CPU: Combines datapath, control path, and memory interface

##  c) Features

**c.1)** Custom-designed Instruction Set Architecture (ISA)  
**c.2)** Supports execution of sample machine code  
**c.3)** Covers core CPU phases: fetch, decode, execute  
**c.4)** Entire project built and tested in Logisim environment

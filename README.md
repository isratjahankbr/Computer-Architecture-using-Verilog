5-Bit CPU Design Using Logisim
This project presents a custom-built CPU architecture designed in Logisim as part of an academic assignment. It demonstrates essential concepts in digital logic, processor design, and instruction execution.

** a) Project Specifications**
      1) Word Size of CPU: 5 bits
      2) ALU Operations:
          • AND
          • ADD
          • ROL (Rotate Left)
      3) Number of Registers: 3
      4) RAM Size: 9 words
      5) Word Size of ISA and RAM: 15 bits
      6) Supported Instruction Types:
          • Register Mode
          • Immediate Mode
          • Branching Mode (JMP, JLE)

 **b) Implemented Components**
      1) ALU Circuit: Supports ADD, AND, ROL
      2) Register Set: Includes 1-bit, 5-bit registers, and 3-register system
      3) Program Counter: 4-bit PC with adder
      4) Memory Modules: 1×1 RAM, 1×15 RAM, and final 9×15 SRAM
      5) Control Unit (CU): Handles instruction decoding and control signals
      6) Integrated CPU: Combines datapath, control path, and memory interface

 **c) Features**
      1) Custom-designed Instruction Set Architecture (ISA)
      2) Supports execution of sample machine code
      3) Covers core CPU phases: fetch, decode, execute
      4) Entire project built and tested in Logisim environment

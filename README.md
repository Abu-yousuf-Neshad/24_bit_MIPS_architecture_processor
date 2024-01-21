Cse 332 project

ISA (Part 1)

Title: ISA Design Type: Document

Consider yourself as a computer architect and you are employed in a vendor company. The company told you that they are going to design a new 24-bit single-cycle CPU that has separate Data and Instruction Memory. The ISA should be general-purpose enough to be able to run provided general programs

Input/Output Operations

It should also be able to connect with the display unit (ex: seven-segment display) to display results or any data and a keyboard or something similar to get input from the user. you should make any necessary arrangements (extra instruction or special register or any other) to accommodate this external communication into your ISA design. For example, you might consider including dedicated instructions like IN & OUT to perform the input/output operations.

Design requirements

As an ISA designer, your job is to propose a detailed design of the ISA. A few of the issues probably you would have to address are given below:

How many operands?

Types of operand? (Register based?? Memory-based? Mixed?)

How many operations? why?

Types of operations? (Arithmetic, logical, branch type?? How many are from each category? Draw a table with a list of instructions, instruction type, their opcode, functionality (if any)

How many formats would you choose? Draw the formats along with the field name and number of bits in each field

list of registers? Draw a register table. (with register name and values)

Addressing Modes

Benchmark Programs

You have to design your ISA focusing on the following three categories of programs

a) Simple arithmetic & logic operations

b) Programs that require checking conditions

c) Loop type of programs

d) Bubble sort

Guideline Your assignment will be evaluated according to the following criteria:

Ability to execute the provided benchmark programs, and other general-purpose programs?
How much is it different from existing ISAs such as MIPS?
How long does it take to run benchmark programs on your processor? You must answer those with your reasoning. While you are deciding on the above issues, you might consider some sample high-level programs that can be run on this CPU using your ISA. Say, during the decisions about the types of operation to include, you can think about the type of high-level language program it will be able to execute. The design might vary from one group to another and there might be multiple possible solutions. You will be scored based on your clear reasoning.


Assembler (Part 2)

Title: Assembler Type: Software (Platform: any) It is difficult and error-prone to manually write machine code. The problem can be addressed by writing an assembler, which can automatically generate a machine code from an assembly file. In this project, you should write an assembler for your ISA. The assembler reads a program written using assembly language in a text file, then translates it into binary code and generates an output file(.txt) containing machine code. The generated output files will later be useful to run a program when you develop your actual CPU.

Language:

You can use any high-level language. C-based source codes are available here.

I/O format:

the input code will be written in a text file in assembly format following your ISA. There will be one instruction per line. The output will be generated in Hexadecimal format instead of binary. this will be helpful for us to later transfer this code into the RAM block of the logicism circuit.

Documentation: You must prepare your own documentation. A sample documentation is available for you here.

Datapath (Part 3)

Title: Datapath Type: Software (Logisim) In this part of the project, you have to design a Datapath of your proposed 24-bit architecture. Datapath must have all the necessary components. The components must be adequately connected. It is mandatory to design the control unit at this phase. You can provide manual input to all the control lines if you can't manage the design control units. However, the datapath must be fully operational for all individual instructions proposed.


Processor Testing (Part 4)

Programs will be of the following type

a) Simple arithmetic & logic operations

b) Programs that require checking conditions

c) Loop type of programs

d) Bubble sort
![5](https://github.com/Abu-yousuf-Neshad/24_bit_MIPS_architecture_processor/assets/113527483/7113de3c-c9ec-47fd-8b6f-3d3992f0a9dd)
![4](https://github.com/Abu-yousuf-Neshad/24_bit_MIPS_architecture_processor/assets/113527483/c4d53790-e5cf-462b-bfa7-412c8009e07e)
![3](https://github.com/Abu-yousuf-Neshad/24_bit_MIPS_architecture_processor/assets/113527483/d1383cc5-4f1b-4730-97d6-3c160fa2029e)
![1](https://github.com/Abu-yousuf-Neshad/24_bit_MIPS_architecture_processor/assets/113527483/cfa3affa-8e8e-410f-81a7-73726c58fd7a)
![2](https://github.com/Abu-yousuf-Neshad/24_bit_MIPS_architecture_processor/assets/113527483/89e9ac28-3184-4224-a038-b22cf93a0c5c)

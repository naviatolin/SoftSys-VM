# Implementing a VM in C

## The Project

In this project, I aim to create a working virtual machine in C. I will create virtual registers, a way to fetch instructions written in and decode them, and execute the instructions I receive. I will be using Little Computer 3 VM since it has less instructions than other assembly versions.

### Minimum Viable Product

I will create a virtual machine that can increment the program counter, read instructions, decode the instructions, and execute them. The instructions I will implement in this MVP will be instructions that are of an ALU's instruction set. I will write a way to load programs into memory here in order to run them.

### Set Goal

I will create a virtual machine that can implement more instructions beyond the ALU's instruction set. I will implement branch and jump and several other common assembly instructions. I will implement memory mapped registers in order to take in keyboard input.

### Stretch Goal

I will implement trap codes for the input and output of strings. Following this, I will create a way to gather keyboard input from the terminal. I will create a complete LC-3 virtual machine here.

## Learning Goals

I intend to learn more deeply about computer architecture by working on this project. By becoming familiar with LC-3 assembly which is so often used to teach students about computer architecture, I am diving in deeper in order to learn more about C.

## Current Status

I am able to find lots of resources online regarding LC-3 assembly and its implementations. Currently, I do not need help in this implementation, but I may in the future.

## Next Steps

[ ] Understand the instructions in LC-3 assembly
[ ] Write a basic loop that can read, decode, and execute simple arithmetic/bitwise instructions
[ ] Attempt to run a basic machine code file with simple arithmetic instructions

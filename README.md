0x19. C - Stacks, Queues - LIFO, FIFO

Monty is a simple scripting language that is compiled into Monty byte codes. The goal of this project is to create an interpreter for Monty ByteCodes files.

## Introduction

This project aims to implement a Monty interpreter with various opcodes that allow manipulating a stack and performing arithmetic operations. It also includes advanced features such as commenting, printing characters, and more.

## Project Structure

The project is organized as follows:

- `*.c` - Source code files
- `monty.h` - Header file with function prototypes
- `bf/` - Directory containing Brainf*ck scripts
- `README.md` - Project documentation

## Compilation & Execution

Compile the project using the following command:

```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty

Execute Monty with a Monty bytecode file:
$ ./monty path/to/monty_bytecode_file.m



Certainly! Below is a template for a README.md file for your Monty project. You can customize it with specific details about your project.

markdown
Copy code
# Monty Project

Monty is a simple scripting language that is compiled into Monty byte codes. The goal of this project is to create an interpreter for Monty ByteCodes files.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Compilation & Execution](#compilation--execution)
- [Usage](#usage)
- [Implemented Opcodes](#implemented-opcodes)
- [Advanced Opcodes](#advanced-opcodes)
- [Brainf*ck Scripts](#brainfck-scripts)
- [Additional Programs](#additional-programs)
- [Authors](#authors)
- [License](#license)

## Introduction

This project aims to implement a Monty interpreter with various opcodes that allow manipulating a stack and performing arithmetic operations. It also includes advanced features such as commenting, printing characters, and more.

## Project Structure

The project is organized as follows:

- `*.c` - Source code files
- `monty.h` - Header file with function prototypes
- `bf/` - Directory containing Brainf*ck scripts
- `README.md` - Project documentation

## Compilation & Execution

Compile the project using the following command:

```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
Execute Monty with a Monty bytecode file:

bash
Copy code
$ ./monty path/to/monty_bytecode_file.m
Usage
The Monty program reads Monty bytecode files and executes the instructions specified in the file. It supports various opcodes for stack manipulation, arithmetic operations, and more.

Implemented Opcodes
push: Pushes an element onto the stack.
pall: Prints all elements of the stack.
pint: Prints the value at the top of the stack.
pop: Removes the top element of the stack.
swap: Swaps the top two elements of the stack.
add: Adds the top two elements of the stack.
nop: No-operation (does nothing).
Advanced Opcodes
sub: Subtracts the top element from the second top element.
div: Divides the second top element by the top element.
mul: Multiplies the top two elements of the stack.
mod: Computes the remainder of the division of the second top element by the top element.
pchar: Prints the ASCII character at the top of the stack.
pstr: Prints the string starting at the top of the stack.
rotl: Rotates the stack to the top.
rotr: Rotates the stack to the bottom.
stack: Sets the data format to a stack (LIFO).
queue: Sets the data format to a queue (FIFO).
Brainf*ck Scripts
1000-school.bf: Brainf*ck script that prints "School".
1001-add.bf: Adds two digits provided by the user.
1002-mul.bf: Multiplies two digits provided by the user.
1003-mul.bf: Multiplies two digits provided by the user with a newline.
Additional Programs
add_two_digits.c: C program to add two digits from user input.
multiply_digits.c: C program to multiply two digits from user input.
multiply_digits_level_up.c: C program to multiply two digits from user input with a newline.

Authors
Odewale Toheeb
Toheeb Toheeb

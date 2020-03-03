#  Mips Assembler

This program takes in a mips asm file from standard input and writes the machine code to standard output.

## Supported Directives:
* .text (switch to the text segment)
* .data (switch to the data segment)
* .word w1, ... , wn (store n 32-bit integer values in successive memory words)
* .space n (allocate n words)

## Supported instructions:
* addiu
* addu
* and
* beq
* bne
* div
* j
* lw
* mfhi
* mflo
* mult
* or
* slt
* subu
* sw
* syscall

## Example input file:

<img src="https://i.imgur.com/ArmsUtX.png">

## Example output file:

<img src="https://i.imgur.com/cxRwupl.png">

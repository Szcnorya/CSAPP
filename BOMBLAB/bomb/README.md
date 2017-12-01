# BombLab
Well fairly fantastic lab homework. 

## Helpful Resource
* Google!
* X86/64 Cheat Sheet from Brown CS:https://cs.brown.edu/courses/cs033/docs/guides/x64_cheatsheet.pdf
* GDB x Usage:http://visualgdb.com/gdbreference/commands/x
* X86/64 Stack layout:https://eli.thegreenplace.net/2011/09/06/stack-frame-layout-on-x86-64
* Procedure Linkage Table(well,not neccessary but helpful):https://docs.oracle.com/cd/E19120-01/open.solaris/819-0690/feowg/index.html

## Get started:
1. objdump to disassemble the binary.
2. gdb to trace running and watch data field not visible in assembly.

## Hint:
* Be careful to unsigned/signed compare
* Watch for argument passing before function calling
* Try to recover the loops from assembly(jump and iterating registers)
* Watch for difference between Address and Data e.g. "%eax" or "(%eax)".
* Addressing mode sometime used for calculation  e.g "leaq (%eax,%eax,2) %eax" == %eax*=3

## Solutions(Careful not to read before you finish!)

### Phase I
Basically, phase I is directly calling strcmp function to check input with a pregiven string in address 0x402400. 

### TOBEDONE
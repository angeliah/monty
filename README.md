0x19. C - Stacks, Queues - LIFO, FIFO

In thi project, we are tasked to come up with an interpreter for Monty Byte Code files.These files will have command per line to manipulate the given data structures.

The Monty language:
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty byte code files:
Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument.


Learning objectives:
At the end of this project, you are expected to be able to explain to anyone, without the help of Googl:
What do LIFO and FIFO mean

What is a stack, and when to use it

What is a queue, and when to use it

What are the common implementations of stacks and queues

What are the most common use cases of stacks and queues

What is the proper way to use global variables


Instructions

Compile with:
gcc -Wall -Werror -Wextra -pedantic *.c -o monty

Tasks

0. push, pall

Implement the push and pall opcodes.

The opcode push pushes an element to the stack.

The opcode pall prints all the values on the stack, starting from the top of the stack.

1. pint

Implement the pint opcode.

The opcode pint prints the value at the top of the stack, followed by a new line.

2. pop

Implement the pop opcode.

The opcode pop removes the top element of the stack.

3. swap

Implement the swap opcode

The opcode swap swaps the top two elements of the stack.

4. add

Implement the add opcode.

The opcode add adds the top two elements of the stack.

5. nop

Implement the nop opcode.

The opcode nop doesn’t do anything.

Advanced Tasks:

opcodes: sub, div, mul, mod, comments, pchar, pstr, rotl, rotr, stack, queue, Brainf*ck, Add two digits, Multiplication, Multiplication level up

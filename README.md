Solution to The Monty Project
0 - Implement the push and pall opcodes

    The push opcode

    The opcode push pushes an element to the stack.

        Usage: push <int>
            where <int> is an integer
        if <int> is not an integer or if there is no argument given to push, print the error message L<line_number>: usage: push integer, followed by a new line, and exit with the status EXIT_FAILURE
            where is the line number in the file
        You won’t have to deal with overflows. Use the atoi function

    The pall opcode

    The opcode pall prints all the values on the stack, starting from the top of the stack.

        Usage pall
        If the stack is empty, don’t print anything

1 - Implement the pint opcode

    The pint opcode

    The opcode pint prints the value at the top of the stack, followed by a new line.

        Usage: pint
        If the stack is empty, print the error message L<line_number>: can't pint, stack empty, followed by a new line, and exit with the status EXIT_FAILURE

2 - Implement the pop opcode

    The swap opcode

    The opcode swap swaps the top two elements of the stack.

        Usage: swap
        If the stack contains less than two elements, print the error message L<line_number>: can't swap, stack too short, followed by a new line, and exit with the status EXIT_FAILURE

3 - Implement the swap opcode
4 - Implement the add opcode
5 - Implement the nop opcode
6 - Implement the sub opcode
7 - Implement the div opcode
8 - Implement the mul opcode
9 - Implement the mod opcode
10 - Implement the commenting function
11 - Implement the pchar opcode
12 - Implement the pstr opcode
13 - Implement the rotl opcode
14 - Implement the rotr opcode
15 - Implement the stack and queue opcodes
16 - Brainfck script prints "School" followed by a new line
17 - Adds two digits given by the user
18 - Multiply two digits given by the user
19 - Multiply two digits given by the user

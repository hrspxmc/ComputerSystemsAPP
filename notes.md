## Chapter2 Representing and Manipulating Information (lab1)

? Jak działają podstawowe operacje bitowe na intach: ! ~ & ^ | + << >>

- Reprezentacja trzech typów - unsigned int, signed int i float'u.

- Big endian - przechowywanie w pamięci bitów w kolejnościLittle endian 

! Zapis hexadecymalny

Stack:
the stack is managed by the CPU, there is no ability to modify it
variables are allocated and freed automatically
the stack it not limitless – most have an upper bound
the stack grows and shrinks as variables are created and destroyed
stack variables only exist whilst the function that created them exists


A summary of the heap:
the heap is managed by the programmer, the ability to modify it is somewhat boundless
in C, variables are allocated and freed using functions like malloc() and free()
the heap is large, and is usually limited by the physical memory available
the heap requires pointers to access it


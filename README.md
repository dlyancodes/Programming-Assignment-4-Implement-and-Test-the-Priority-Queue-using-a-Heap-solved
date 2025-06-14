# Programming-Assignment-4-Implement-and-Test-the-Priority-Queue-using-a-Heap-solved

Download Here: [Programming Assignment 4: Implement and Test the Priority Queue using a Heap solved](https://jarviscodinghub.com/assignment/programming-assignment-4-implement-and-test-the-priority-queue-using-a-heap-solved/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Implement the Priority Queue class, using a heap to store the items, as described in Section 11.1.
Purposes:
Ensure that you understand and can use heap which is implemented in an array.
Before Starting:
Read all of Sections 8.4, 10.2 and 11.1 (primary)
Files that you must write:
1. pqueue2.h: Header file for this version of the PriorityQueue class. You don’t have to write much
of this file. Just copy our version from https://www.cs.colorado.edu/~main/programs/pqueue2.h
2. pqueue2.cxx: The implementation file for the new PriorityQueue class. A version that contains
just stubs is available for you to copy https://www.cs.colorado.edu/~main/programs/pqueue2.cxx
Other files that you may find helpful:
1. pqtest.cxx: A simple interactive test program for debugging your program.
https://www.cs.colorado.edu/~main/programs/pqtest.cxx
2. pqexam2.cxx: A non-interactive test program that will be used to grade the correctness of your
Priority Queue class. https://www.cs.colorado.edu/~main/programs/pqexam2.cxx
Discussion of the Assignment
Your PriorityQueue class for this assignment will use a heap that is stored in an array. The component type
of the array is called OneItemInfo, and is defined as part of the PriorityQueue class in pqueue2.h. In order
for you to further learn how to use private member functions, I would like for you to write and use all the
private member functions that are listed in pqueue2.h. The precondition/postcondition contracts for these
functions are given in the stub version of pqueue2.cxx.
Do the Assignment in Two Parts
For easier debugging, carry out this assignment in two Parts. Part 1 should include everything except the
public get_front member function and the private functions that are needed for get_front (i.e., is_leaf,
big_child_index, and big_child_priority). While you are debugging Part 1, you should add a new option
to the interactive test program. The new option makes this call to print the current state of the tree of the
test PriorityQueue: test.print_tree(“STATE OF THE TREE:”). (Note that print_tree is a public member
function that I wrote for you. You should remove it before you submit your final work.)
Once Part One is working and tested, you may complete the assignment by implementing the get_front
member function and its associated private functions.
Use the interactive test program and the debugger to track down errors in your implementation. If you have
an error, do not start making changes until you have identified the cause of the error.


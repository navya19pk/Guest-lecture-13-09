#Program a:
Aim: To implement a stack data structure using an array in C++ that supports basic operations like push, pop, and display, demonstrating the Last-In-First-Out (LIFO) behavior of stacks.

Thoery: The program implements a simple stack data structure using an array with a fixed size of 5 elements. A stack follows the Last-In-First-Out (LIFO) principle, meaning the most recently added item is the first to be removed. The Stack class has private members: an integer array to hold the stack elements and an integer top to track the index of the current top element. The push method adds an element to the top of the stack by incrementing top and assigning the new value. The pop method removes the top element by decrementing top. The display method attempts to print the elements of the stack, but there is a small bug in the loop which causes it to print the top element multiple times instead of all elements. Overall, the code demonstrates basic stack operations but can be improved by adding boundary checks and correcting the display logic.

Algorithm:

- Step-1: Start
- Step-2: Increment the top index by 1.
- Step-3: Insert the new element at arr[top].
- Step-4: Decrement the top index by 1, effectively removing the top element from the stack.
- Step-5: Iterate from index 0 to top.
- Step-6: Print each element in the stack.
- Step-7: End.


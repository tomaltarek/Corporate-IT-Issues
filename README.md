# IT-Issues

[Go to Real Cool Heading section](#real-cool-heading)



Data Sructure: 
Stack
To understand computer memory is crucial for a programmer.

From the  programmer's perspective, two types of memory structure is important. Stack and heap but we will limit our discussion on stack. 

When a program is executed, it occupies some space in memory. There are three types of space allocated for a program to run. There is a space allocated for global variables. Then the code itself which is text needs some space. And the third space is called stack frame. At first the main program stays on the stack frame. If that main program has some subroutines or functions which is most of the time the case, for every function call another stack frame is created and control pass to the newest stack frame. If this function calls another function then other newest stack frame will be created on top. After doing their job the called function will return control to the function below which is a caller function. All the memory including the  local variables on that the stack frame will be deleted permanently. For this reason a called function cannot modify variables of the caller function unless it is done by some sort of pointers.
From the scenario what we found is stack is a memory of last in first out type. For every program to run there is a stack of  limited size which men's if your program have so many functions to call and one function calls another function and it keeps going on then at some point that stack will overflow. Hands the error stack overflow come. 

The stack we talked about so far is created by the operating system. But you can create your own stack if needed. You can create a stack based out of an array or based out of a linked list. 
 Adding a member on top of a stack is called Push. Removing an element from the top is called pop. 
You can create a stack out of the scratch or use the language Library. Every language has Library and has built-in functions for any kind of data structure. 
# Real Cool Heading
Popular functions of stacks are push pop, peek and  Isempty. 

Use Case:
Reverse a string. 
Inflix prefix and postfix
fasdfsafd

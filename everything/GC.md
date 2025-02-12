# Gabage Collection
If you are not reachable from root set(set of variables from stack), I delete you to make the earth cleaner!!!  
![image](imgs/Animation_of_the_Naive_Mark_and_Sweep_Garbage_Collector_Algorithm.gif)  
Naive mark-and-sweep in action on a **heap** containing eight objects. Arrows represent object references. Circles represent the objects themselves. Objects #1, #2, #3, #4, and #6 are strongly referenced from the root set. On the other hand, objects #5, #7, and #8 are not strongly referenced either directly or indirectly from the root set; therefore, they are garbage.

## What is it?
Garbage collection (GC) is a memory recovery feature built into programming languages such as C# and Java. A GC-enabled programming language includes one or more garbage collectors (GC engines) that **automatically free up memory space that has been allocated to objects no longer needed by the program**. The reclaimed memory space can then be used for future object allocations within that program.

In older programming languages like C and C++, developers must manually delete objects and free up memory. Replying on manual proccess made it easy to raise the bugs into the code, some of which can have serious consequences. For example, if a developer forget to free up memory, it could leading to memory leak problem.
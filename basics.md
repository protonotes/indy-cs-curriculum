# Basic Concepts in Computer Science

__Pipelines__

Simplified CPU Pipeline Stages
```
Instruction Fetch
Instruction Decode
Scheduling
Dispatch
Read
Execute
Write
```
Differing CPUs have a different number of stages for their pipelines so beware.
Modern CPUs have a deep pipeline. A pipeline stall is when a set of instructions has to wait for the previous to complete.

CPU branching = if else functions.
Wait State: CPU is waiting to access to a memory

CPU Cache (SRAM)
DRAM Memory
SRAM Memory
Consumes more power. Much faster than DRAM. Only in CPU cache.

### CPU Data Access Hierarchy
```
Large and Slow    [   Network  ] [ File System ]
                         v              v
                  [        System Memory       ]
                  [ DRAM Row Banks (Sequential)]
                                 v
                  [       CPU Cache (L3)       ]
                  [       CPU Cache (L2)       ]
                  [       CPU Cache (L1)       ]
                                 V              
Small and Fast    [         CPU Registers      ]
```
Try to keep as much of your program data at the bottom as possible.

__Notes on OOP__

From Brian Will:
Imperative programming does away with state
Functional minimizes state
OOP segregates state.
He believes the problem with OOP is encapsulation. Ultimately, he maintains that encapsulation cannot be maintained in an evolving program, and breaking encapsulation in such a program leads to disorganization and inconsistencies.

__Interviewing__
Things to study:
* Data Structures
* Algorithms.
* Any language
* Concepts: CS concepts (bits, threads), recursion, parallelism, concurrency



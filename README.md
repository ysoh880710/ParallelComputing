# [Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing)

## Definition

![Parallel computing](https://www.researchgate.net/publication/324215607/figure/fig3/AS:779408600227843@1562836899291/Serial-algorithm-and-parallel-computing.gif)

>"[Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing) is a type of computation in which many calculations or processes are carried out **simultaneously**." ([Parallel computing, wikipedia](https://en.wikipedia.org/wiki/Parallel_computing))

## Why [Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing)?

>"Large problems can often be divided into smaller ones, which can then be solved at the same time." ([Parallel computing, wikipedia](https://en.wikipedia.org/wiki/Parallel_computing))

>"Solve Larger Problems in a short point of time." ([Parallel computing and its advantage and disadvantage, geekboots](https://www.geekboots.com/story/parallel-computing-and-its-advantage-and-disadvantage))

More advantages can be found. However, the [speedup](https://en.wikipedia.org/wiki/Speedup) in aspect of performance is mentioned in common and seems to be the core.

>"**The primary goal of [parallel computing](https://en.wikipedia.org/wiki/Parallel_computing) is to increase available computation power for faster application processing and problem solving**." ([Parallel Computing Definition, heavy.ai](https://www.heavy.ai/technical-glossary/parallel-computing))

*Keyword note : [Speedup](https://en.wikipedia.org/wiki/Speedup), [Amdahl's law](https://en.wikipedia.org/wiki/Amdahl%27s_law)

## What are the types of parallelism?

>"There are several different forms of [parallel computing](https://en.wikipedia.org/wiki/Parallel_computing): [bit-level](https://en.wikipedia.org/wiki/Bit-level_parallelism), [instruction-level](https://en.wikipedia.org/wiki/Instruction-level_parallelism), [data](https://en.wikipedia.org/wiki/Data_parallelism), and [task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)." ([Parallel computing, wikipedia](https://en.wikipedia.org/wiki/Parallel_computing))

- [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)
- [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)
- [Bit-level parallelism](https://en.wikipedia.org/wiki/Bit-level_parallelism)
- [Instruction-level parallelism](https://en.wikipedia.org/wiki/Instruction-level_parallelism)

([Types of Parallelism in Processing Execution, tutorialspoint](https://www.tutorialspoint.com/types-of-parallelism-in-processing-execution))

## [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)

### Definition

![Data parallelism](https://upload.wikimedia.org/wikipedia/commons/a/a7/Sequential_vs._Data_Parallel_job_execution.png)

>"[Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism) is parallelization across [multiple processors](https://en.wikipedia.org/wiki/Multi-core_processor) in parallel computing environments. It focuses on distributing the data across different nodes, which **operate on the data in parallel**." ([Data parallelism, wikipedia](https://en.wikipedia.org/wiki/Data_parallelism))

### How to achieve [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)?

>"In a [multiprocessor](https://en.wikipedia.org/wiki/Multi-core_processor) system executing a single set of instructions ([SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data)), [data parallelism](https://en.wikipedia.org/wiki/Data_parallelism) is achieved **when each processor performs the same task on different distributed data**." ([Data parallelism, wikipedia](https://en.wikipedia.org/wiki/Data_parallelism))

#### What is [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data)?

>"[Single instruction, multiple data (SIMD)](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) is a type of parallel processing in [Flynn's taxonomy](https://en.wikipedia.org/wiki/Flynn%27s_taxonomy). [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) can be internal (part of the hardware design) and it can be directly accessible through an instruction set architecture (ISA), but it should not be confused with an ISA. [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) describes computers with multiple processing elements that perform the **same operation on multiple data points simultaneously**." ([Single instruction, multiple data, wikipedia](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data))

>"The first widely deployed desktop [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) was with Intel's MMX extensions to the x86 architecture in 1996. This sparked the introduction of the much more powerful AltiVec system in the Motorola PowerPC and IBM's POWER systems. Intel responded in 1999 by introducing the all-new [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions) system." ([Single instruction, multiple data, wikipedia](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data))

#### Does [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) require [multi-core](https://en.wikipedia.org/wiki/Multi-core_processor) CPU?

>"No. "SI" = single instruction, "MD" = multiple data. The core needs to have, say, 4 multiplier circuits available so the single instruction can multiply 4 numbers at the same time. **The parallelism is in the core itself**." ([Does SIMD require a multi-core CPU?, stackoverflow](https://stackoverflow.com/questions/49810600/does-simd-require-a-multi-core-cpu))

>"**Every core has its own independent [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) execution units**. Using [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) instructions in one core doesn't cost execution resources in other cores." ([Does SIMD require a multi-core CPU?, stackoverflow](https://stackoverflow.com/questions/49810600/does-simd-require-a-multi-core-cpu))

#### What is [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)?

>"[Streaming SIMD Extensions (SSE)](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions) is a **[single instruction, multiple data (SIMD)](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) instruction set extension** to the x86 architecture, designed by Intel and introduced in 1999 in their Pentium III series of Central processing units (CPUs) shortly after the appearance of Advanced Micro Devices (AMD's) 3DNow!." ([Streaming SIMD Extensions, wikipedia](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions))

#### What is the difference between [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) and [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)?

>"**[SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) is the 'concept', [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)/AVX are implementations of the concept**." ([What's the difference between SIMD and SSE?, stackoverflow](https://stackoverflow.com/questions/30282271/whats-the-difference-between-simd-and-sse))

## [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)

### Definition

>"[Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) is a form of **parallelization of computer code across [multiple processors](https://en.wikipedia.org/wiki/Multi-core_processor) in [parallel computing](https://en.wikipedia.org/wiki/Parallel_computing) environments**. [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) focuses on **distributing tasks—[concurrently](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) performed by processes or [threads](https://en.wikipedia.org/wiki/Thread_(computing))—across different processors**." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

>"In contrast to [data parallelism](https://en.wikipedia.org/wiki/Data_parallelism) which involves running the same task on different components of data, [task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) is distinguished by **running many different tasks at the same time** on the same data." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

>"[Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) (**also known as Thread level parallelism**, function parallelism and control parallelism) is a form of [parallel computing](https://en.wikipedia.org/wiki/Parallel_computing) for [multiple processors](https://en.wikipedia.org/wiki/Multi-core_processor) using a technique for distributing execution of processes and [threads](https://en.wikipedia.org/wiki/Thread_(computing)) across different parallel processor nodes. It contrasts to [data parallelism](https://en.wikipedia.org/wiki/Data_parallelism) as another form of parallelism." ([Task parallelism, Simple English wikipedia](https://simple.wikipedia.org/wiki/Task_parallelism))

### What is [Thread level parallelism](https://en.wikipedia.org/wiki/Task_parallelism)?

![Thread level parallelism](https://i.pinimg.com/originals/59/37/20/593720df6d7374598c27c70a5a26f6a8.png)

>"[Thread-level parallelism (TLP)](https://en.wikipedia.org/wiki/Task_parallelism) is the parallelism inherent in an application that **runs multiple [threads](https://en.wikipedia.org/wiki/Thread_(computing)) at once**." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

>"The exploitation of [thread-level parallelism](https://en.wikipedia.org/wiki/Task_parallelism) has also begun to make inroads into the desktop market with the advent of [multi-core microprocessors](https://en.wikipedia.org/wiki/Multi-core_processor)." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

### How to achieve [Task parallelism (Thread level parallelism)](https://en.wikipedia.org/wiki/Task_parallelism)?

>"In a [multiprocessor](https://en.wikipedia.org/wiki/Multi-core_processor) system, [task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) is achieved **when each processor executes a different [thread](https://en.wikipedia.org/wiki/Thread_(computing)) (or process) on the same or different data**." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

#### What is [Thread](https://en.wikipedia.org/wiki/Thread_(computing))?

![Thread](https://upload.wikimedia.org/wikipedia/commons/a/a5/Multithreaded_process.svg)

>"A [thread](https://en.wikipedia.org/wiki/Thread_(computing)) of execution is **the smallest sequence of programmed instructions that can be managed independently by a scheduler, which is typically a part of the operating system**." ([Thread, wikipedia](https://en.wikipedia.org/wiki/Thread_(computing)))

>"[Thread](https://en.wikipedia.org/wiki/Thread_(computing)) is an **execution unit** that is part of a process." ([Process vs Thread: What’s the difference?, guru99](https://www.guru99.com/difference-between-process-and-thread.html))

>"A [thread](https://www.guru99.com/cpu-core-multicore-thread.html) is **a unit of execution on [concurrent programming](https://en.wikipedia.org/wiki/Concurrent_computing)**." ([CPU Core, Multi-Core, Thread, Core vs Threads, Hyper-Threading, guru99](https://www.guru99.com/cpu-core-multicore-thread.html))

>"**[Threads](https://en.wikipedia.org/wiki/Thread_(computing)) in the same process share the same address space**." ([Thread, wikipedia](https://en.wikipedia.org/wiki/Thread_(computing)))

>"**A Thread is a flow of execution.**" ([THREADS IN JAVA, medium](https://medium.com/nerd-for-tech/threads-in-java-b3b575d1030d))

#### What is [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture))?

![Multithreading](https://www.logicbig.com/quick-info/images/multithreading.png)

>"**[Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) is the ability of a central processing unit (CPU) (or a single core in a multi-core processor) to provide multiple [threads](https://en.wikipedia.org/wiki/Thread_(computing)) of execution **[concurrently](https://en.wikipedia.org/wiki/Concurrency_(computer_science))**, supported by the operating system**." ([Multithreading, wikipedia](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)))

>"Systems with a single processor generally implement [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) by time slicing: the central processing unit (CPU) switches between different software [threads](https://en.wikipedia.org/wiki/Thread_(computing)). This [context switching](https://en.wikipedia.org/wiki/Context_switch) usually occurs frequently enough that users perceive the [threads](https://en.wikipedia.org/wiki/Thread_(computing)) or tasks as running in parallel (for popular server/desktop operating systems, maximum time slice of a thread, when other threads are waiting, is often limited to 100-200ms). On a [multiprocessor](https://en.wikipedia.org/wiki/Multi-core_processor) or [multi-core](https://en.wikipedia.org/wiki/Multi-core_processor) system, [multiple threads](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) can execute in parallel, with every processor or core executing a separate [thread](https://en.wikipedia.org/wiki/Thread_(computing)) simultaneously; on a processor or core with hardware [threads](https://en.wikipedia.org/wiki/Thread_(computing)), separate software [threads](https://en.wikipedia.org/wiki/Thread_(computing)) can also be executed [concurrently](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) by separate hardware [threads](https://en.wikipedia.org/wiki/Thread_(computing))." ([Thread, wikipedia](https://en.wikipedia.org/wiki/Thread_(computing)))

##### What is [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is the ability of different parts or units of a program, algorithm, or problem to be executed out-of-order or in partial order, without affecting the final outcome." ([Concurrency, wikipedia](https://en.wikipedia.org/wiki/Concurrency_(computer_science)))

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is **when two or more tasks can start, run, and complete in overlapping time periods**." ([What is the difference between concurrency and parallelism?, stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

>"**A condition that exists when at least two [threads](https://en.wikipedia.org/wiki/Thread_(computing)) are making progress**. A more generalized form of parallelism that can include time-slicing as a form of virtual parallelism." ([Defining Multithreading Terms, oracle docs](https://docs.oracle.com/cd/E19455-01/806-5257/6je9h032b/index.html))

##### What is Parallelism?

>"**A condition that arises when at least two threads are executing simultaneously**." ([Defining Multithreading Terms, oracle docs](https://docs.oracle.com/cd/E19455-01/806-5257/6je9h032b/index.html))

##### What is the difference between [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) and Parallelism?

![Parallelism vs Concurrency](https://i.stack.imgur.com/mUlNV.jpg)

>"**[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is when two or more tasks can start, run, and complete in overlapping time periods**." ([What is the difference between concurrency and parallelism?, stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

>"**Parallelism is when tasks literally run at the same time, e.g., on a [multicore processor](https://en.wikipedia.org/wiki/Multi-core_processor)**." ([What is the difference between concurrency and parallelism?, stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is about structure, parallelism is about execution, [concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) provides a way to structure a solution to solve a problem that may (but not necessarily) be parallelizable." ([Concurrency, wikipedia](https://en.wikipedia.org/wiki/Concurrency_(computer_science)))

##### How to achieve [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

>"**In C++, the two most common ways of implementing [concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) are through [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) and parallelism**." ([A tutorial on modern multithreading and concurrency in C++, educative.io](https://www.educative.io/blog/modern-multithreading-and-concurrency-in-cpp))

>"**[Multi-threading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) is what usually refers to concurrent programming**." ([How to use Multithreading and Multiprocessing - A Beginner's guide to parallel and concurrent programming, mineiros.io](https://www.mineiros.io/blog/guide-to-multihreading-and-multiprocessing#multi-threading))

##### What is [Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing)?

>"[Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing) **is a form of computing in which several computations are executed [concurrently](https://en.wikipedia.org/wiki/Concurrency_(computer_science))—during overlapping time periods—instead of sequentially—with one completing before the next starts**. This is a property of a system—whether a program, computer, or a network—where there is a separate execution point or "[thread](https://en.wikipedia.org/wiki/Thread_(computing)) of control" for each process. A [concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) system is one where a computation can advance without waiting for all other computations to complete." ([Concurrent computing, wikipedia](https://en.wikipedia.org/wiki/Concurrent_computing))

##### Is [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) [concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) or parallel?

>"Threads are a software construct. I can start as many pthreads as I want, even on an old single core processor. So **multi-threading is not necessarily parallel: it's only parallel if the hardware can support it. So if you have multiple cores and/or hyperthreading, your multi-threading becomes parallel**." ([Is multithreading concurrent or parallel?, quora](https://www.quora.com/Is-multithreading-concurrent-or-parallel))

>"Threads are a software construct. I can start as many pthreads as I want, even on an old single core processor. So **multi-threading is not necessarily parallel: it’s only parallel if the hardware can support it. So if you have multiple cores and/or hyperthreading, your multi-threading becomes parallel**." ([Is threading parallel computing?, whatisany](https://whatisany.com/does-parallel-computing-use-multiple-threads/))

>"**If your threads run on physical cores at the same time then they are parallel, otherwise they are just time-sharing or [concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science))**." ([Are threads concurrent or parallel?, whatisany](https://whatisany.com/does-parallel-computing-use-multiple-threads/))

>"**You can have [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) on a single core machine, but you can only have parallelism on a [multi core](https://en.wikipedia.org/wiki/Multi-core_processor) machine (or multi proc, but I treat them the same)**." ([Threading/Concurrency vs Parallelism, danielmoth](http://www.danielmoth.com/Blog/threadingconcurrency-vs-parallelism.aspx))

###### Is Parallelism a subset of [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

>"**Sorry, but this answer is incorrect**." ([Parallelism implies concurrency but not the other way round right?, stackexchange](https://softwareengineering.stackexchange.com/questions/155109/parallelism-implies-concurrency-but-not-the-other-way-round-right))

>"**it is possible to have parallelism without concurrency (such as bit-level parallelism)**" ([Parallel computing, wikipedia](https://en.wikipedia.org/wiki/Parallel_computing))

- OK. Parallelism is NOT subset of concurrency.

# Summary

# [Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing)

## Definition

[Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing) is a type of computation in which many calculations or processes are carried out **simultaneously**.

## Why [Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing)?

- To compute more task in same amount of time or same amount of task in shorter amount of time by computing smaller problems in parallel.

## What are the types of parallelism?

- [Bit-level parallelism](https://en.wikipedia.org/wiki/Bit-level_parallelism)
- [Instruction-level parallelism](https://en.wikipedia.org/wiki/Instruction-level_parallelism)
- [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)
- [Task parallelism (Thread-level parallelism (TLP))](https://en.wikipedia.org/wiki/Task_parallelism)

## [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)

- Operate on the data in parallel.

### How to achieve [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)?

- [SIMD (Concept)](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data)
- [SSE (Implementation)](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)

## [Task parallelism (Thread level parallelism)](https://en.wikipedia.org/wiki/Task_parallelism)

- Running many different tasks simultaneously across different processors.
- Running multiple [threads](https://en.wikipedia.org/wiki/Thread_(computing)) at once.

### How to achieve [Task parallelism (Thread level parallelism)](https://en.wikipedia.org/wiki/Task_parallelism)?

- By each processor executing a different [thread](https://en.wikipedia.org/wiki/Thread_(computing)) (or process) on the same or different data simultaneously.

#### What is [Thread](https://en.wikipedia.org/wiki/Thread_(computing))?

- Unit of execution flow.

#### What is [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture))?

- Having multiple units of execution flow.

##### What is [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

- A condition when at least two [threads](https://en.wikipedia.org/wiki/Thread_(computing)) are making progress.

##### What is Parallelism?

- A condition that arises when at least two [threads](https://en.wikipedia.org/wiki/Thread_(computing)) are executing simultaneously.

##### What is the difference between [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) and Parallelism?

- [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is at least two [threads](https://en.wikipedia.org/wiki/Thread_(computing)) making progress while parallelism is at least two threads being executed simultaneously.

##### How to achieve [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

- By [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)).

##### What is [Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing)?

- Computing by two or more threads making progress.

##### Is [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) [concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) or parallel?

**[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) and parallelism are different level of category.**

It is not either [concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) or parallelism. It is either [concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) or not, and either parallel or not.
- Not concurrent (Sequential) / Not parallel
- Not concurrent (Sequential) / Parallel
- Concurrent / Not parallel
- Concurrent / Parallel

**How does [threading](https://en.wikipedia.org/wiki/Thread_(computing)) or [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) relates to [concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) and parallelism?**

Definition of thread clarifies this. [Thread](https://en.wikipedia.org/wiki/Thread_(computing)) is **"unit of execution flow"**.
This "execution flow" can be managed independently by a scheduler, which is typically a part of the operating system.

- Having a [thread](https://en.wikipedia.org/wiki/Thread_(computing)) means having one unit of execution flow.
- Having multiple [threads](https://en.wikipedia.org/wiki/Thread_(computing)) ([Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture))) means having multiple units of execution flow.

**And,**

- Having multiple units of execution flow is having multiple things making progress, which is definition of [concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)).

- Multiple units of execution flow is done by time slicing in single core hardware environment.
- Multiple units of execution flow is done in parallel in multi core hardware environment.

**In short,**

- [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)), or having multiple units of execution flow, is **[concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science))**.
- [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) itself is just having multiple units of execution flow. This has nothing to do with parallelism.

- How operating system deals with multiple units of execution flow relates to parallelism.
- Parallelism is achieved by operating system and hardware environment.

- "**Code can be [concurrent](https://en.wikipedia.org/wiki/Concurrency_(computer_science)), but not parallel**." ([Parallelism implies concurrency but not the other way round right?, stackexchange](https://softwareengineering.stackexchange.com/questions/155109/parallelism-implies-concurrency-but-not-the-other-way-round-right))

###### Is Parallelism a subset of [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

- No. It is possible to have parallelism without [concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) (such as [bit-level parallelism](https://en.wikipedia.org/wiki/Bit-level_parallelism)).

# Put together by ysoh880710

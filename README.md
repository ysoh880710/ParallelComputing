# [Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing)

## Definition

>"[Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing) is a type of computation in which many calculations or processes are carried out simultaneously." ([Parallel computing, wikipedia](https://en.wikipedia.org/wiki/Parallel_computing))

## What are advantages of [Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing)?

>"Large problems can often be divided into smaller ones, which can then be solved at the same time." ([Parallel computing, wikipedia](https://en.wikipedia.org/wiki/Parallel_computing))

>"Solve Larger Problems in a short point of time." ([Parallel computing and its advantage and disadvantage, geekboots](https://www.geekboots.com/story/parallel-computing-and-its-advantage-and-disadvantage))

More advantages can be found. However, the [speedup](https://en.wikipedia.org/wiki/Speedup) in aspect of performance is mentioned in common and seems to be the core.

>"The primary goal of parallel computing is to increase available computation power for faster application processing and problem solving." ([Parallel Computing Definition, heavy.ai](https://www.heavy.ai/technical-glossary/parallel-computing))

*Keyword note : [Speedup](https://en.wikipedia.org/wiki/Speedup), [Amdahl's law](https://en.wikipedia.org/wiki/Amdahl%27s_law)

## What are the types of parallelism?

>"There are several different forms of parallel computing: [bit-level](https://en.wikipedia.org/wiki/Bit-level_parallelism), [instruction-level](https://en.wikipedia.org/wiki/Instruction-level_parallelism), [data](https://en.wikipedia.org/wiki/Data_parallelism), and [task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)." ([Parallel computing, wikipedia](https://en.wikipedia.org/wiki/Parallel_computing))

- Data parallelism
- Task parallelism
- Bit-level parallelism
- Instruction-level parallelism

([Types of Parallelism in Processing Execution, tutorialspoint](https://www.tutorialspoint.com/types-of-parallelism-in-processing-execution))

## What is [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)?

![Data parallelism](https://upload.wikimedia.org/wikipedia/commons/a/a7/Sequential_vs._Data_Parallel_job_execution.png)

>"[Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism) is parallelization across [multiple processors](https://en.wikipedia.org/wiki/Multi-core_processor) in parallel computing environments." ([Data parallelism, wikipedia](https://en.wikipedia.org/wiki/Data_parallelism))

## How to achieve [Data parallelism](https://en.wikipedia.org/wiki/Data_parallelism)?

>"In a [multiprocessor](https://en.wikipedia.org/wiki/Multi-core_processor) system executing a [single set of instructions (SIMD)](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data), [data parallelism](https://en.wikipedia.org/wiki/Data_parallelism) is achieved when each processor performs the same task on different distributed data." ([Data parallelism, wikipedia](https://en.wikipedia.org/wiki/Data_parallelism))

### What is [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data)?

>"[Single instruction, multiple data (SIMD)](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) is a type of parallel processing in Flynn's taxonomy." ([Single instruction, multiple data, wikipedia](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data))

>"The first widely deployed desktop [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) was with Intel's MMX extensions to the x86 architecture in 1996. This sparked the introduction of the much more powerful AltiVec system in the Motorola PowerPC and IBM's POWER systems. Intel responded in 1999 by introducing the all-new [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions) system." ([Single instruction, multiple data, wikipedia](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data))

### What is [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)?

>"[Streaming SIMD Extensions (SSE)](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions) is a [single instruction, multiple data (SIMD)](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) instruction set extension to the x86 architecture, designed by Intel and introduced in 1999 in their Pentium III series of Central processing units (CPUs) shortly after the appearance of Advanced Micro Devices (AMD's) 3DNow!." ([Streaming SIMD Extensions, wikipedia](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions))

### What is the difference between [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) and [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)?

>"[SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data) is the 'concept', [SSE](https://en.wikipedia.org/wiki/Streaming_SIMD_Extensions)/AVX are implementations of the concept." ([What's the difference between SIMD and SSE?, stackoverflow](https://stackoverflow.com/questions/30282271/whats-the-difference-between-simd-and-sse))

## What is [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)?

>"[Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) is a form of parallelization of computer code across [multiple processors](https://en.wikipedia.org/wiki/Multi-core_processor) in [parallel computing](https://en.wikipedia.org/wiki/Parallel_computing) environments. [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) focuses on distributing tasks—[concurrently](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) performed by processes or [threads](https://en.wikipedia.org/wiki/Thread_(computing))—across different processors." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

>"[Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) (also known as Thread level parallelism, function parallelism and control parallelism) is a form of parallel computing for multiple processors using a technique for distributing execution of processes and threads across different parallel processor nodes. It contrasts to data parallelism as another form of parallelism." [Task parallelism, Simple English wikipedia](https://simple.wikipedia.org/wiki/Task_parallelism)

## What is [Thread level parallelism]?

>"Thread-level parallelism (TLP) is the parallelism inherent in an application that runs multiple threads at once." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

>"The exploitation of thread-level parallelism has also begun to make inroads into the desktop market with the advent of [multi-core microprocessors](https://en.wikipedia.org/wiki/Multi-core_processor)." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

## How to achieve [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)?

>"In a [multiprocessor](https://en.wikipedia.org/wiki/Multi-core_processor) system, [task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) is achieved when each processor executes a different [thread](https://en.wikipedia.org/wiki/Thread_(computing)) (or process) on the same or different data." ([Task parallelism, wikipedia](https://en.wikipedia.org/wiki/Task_parallelism))

## What is [Thread](https://en.wikipedia.org/wiki/Thread_(computing))?

![Thread](https://upload.wikimedia.org/wikipedia/commons/a/a5/Multithreaded_process.svg)

>"A [thread](https://en.wikipedia.org/wiki/Thread_(computing)) of execution is the smallest sequence of programmed instructions that can be managed independently by a scheduler, which is typically a part of the operating system." ([Thread, wikipedia](https://en.wikipedia.org/wiki/Thread_(computing)))

>"[Thread](https://en.wikipedia.org/wiki/Thread_(computing)) is an execution unit that is part of a process." ([Process vs Thread: What’s the difference?, guru99](https://www.guru99.com/difference-between-process-and-thread.html))

## What is [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture))?

![Multithreading](https://www.logicbig.com/quick-info/images/multithreading.png)

>"[Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) is the ability of a central processing unit (CPU) (or a single core in a multi-core processor) to provide multiple threads of execution concurrently, supported by the operating system" ([Multithreading, wikipedia](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)))

>"[Multithreading](https://en.wikipedia.org/wiki/Thread_(computing)) can also be applied to one process to enable parallel execution on a multiprocessing system."

## What is [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is the ability of different parts or units of a program, algorithm, or problem to be executed out-of-order or in partial order, without affecting the final outcome" ([Concurrency, wikipedia](https://en.wikipedia.org/wiki/Concurrency_(computer_science)))

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is when two or more tasks can start, run, and complete in overlapping time periods." ([What is the difference between concurrency and parallelism?, stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

I found Stackoverflow definition more understandable.

## What is the difference between [Parallelism](https://en.wikipedia.org/wiki/Parallel_computing) and [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

![Parallelism vs Concurrency](https://i.stack.imgur.com/mUlNV.jpg)

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is when two or more tasks can start, run, and complete in overlapping time periods." ([What is the difference between concurrency and parallelism?, stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

>"[Parallelism](https://en.wikipedia.org/wiki/Parallel_computing) is when tasks literally run at the same time, e.g., on a multicore processor." ([What is the difference between concurrency and parallelism?, stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

## What is [Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing)?

>"[Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing) is a form of computing in which several computations are executed concurrently—during overlapping time periods—instead of sequentially—with one completing before the next starts." ([Concurrent computing, wikipedia](https://en.wikipedia.org/wiki/Concurrent_computing))

## How can [Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing) be achieved?

>"In C++, the two most common ways of implementing concurrency are through [multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) and parallelism" ([A tutorial on modern multithreading and concurrency in C++, educative.io](https://www.educative.io/blog/modern-multithreading-and-concurrency-in-cpp))

>"[Multi-threading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) is what usually refers to concurrent programming." ([How to use Multithreading and Multiprocessing - A Beginner's guide to parallel and concurrent programming, mineiros.io](https://www.mineiros.io/blog/guide-to-multihreading-and-multiprocessing#multi-threading))

## How does [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) achieved by [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) matters with [Parallelism](https://en.wikipedia.org/wiki/Parallel_computing)?

>"Threads are a software construct. I can start as many pthreads as I want, even on an old single core processor. So multi-threading is not necessarily parallel: it's only parallel if the hardware can support it. So if you have multiple cores and/or hyperthreading, your multi-threading becomes parallel." ([Is multithreading concurrent or parallel?, quora](https://www.quora.com/Is-multithreading-concurrent-or-parallel))

>"Threads are a software construct. I can start as many pthreads as I want, even on an old single core processor. So multi-threading is not necessarily parallel: it’s only parallel if the hardware can support it. So if you have multiple cores and/or hyperthreading, your multi-threading becomes parallel." ([Is threading parallel computing?, whatisany](https://whatisany.com/does-parallel-computing-use-multiple-threads/))

>"If your threads run on physical cores at the same time then they are parallel, otherwise they are just time-sharing or concurrent." ([Are threads concurrent or parallel?, whatisany](https://whatisany.com/does-parallel-computing-use-multiple-threads/))

>"You can have multithreading on a single core machine, but you can only have parallelism on a multi core machine (or multi proc, but I treat them the same)." ([Threading/Concurrency vs Parallelism, danielmoth](http://www.danielmoth.com/Blog/threadingconcurrency-vs-parallelism.aspx))

## Conclusion

|Data parallelism|Task parallelism|
|---|---|
|123|456|

- [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) is one way to achieve concurrency, and it achieves parallelism under multi-core hardware environment.

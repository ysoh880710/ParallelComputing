# [Parallel Computing](https://en.wikipedia.org/wiki/Parallel_computing)

## Definition

>"[Parallel Computing](https://en.wikipedia.org/wiki/Parallel_computing) is a type of computation in which many calculations or processes are carried out simultaneously." (wikipedia)

## Types of parallelism

- Bit-level parallelism
- Instruction-level parallelism
- [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)
- Superword level parallelism

## What is [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism)?

>"[Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) is a form of parallelization of computer code across [multiple processors](https://en.wikipedia.org/wiki/Multi-core_processor) in parallel computing environments. [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) focuses on distributing tasks—concurrently performed by processes or threads—across different processors." (wikipedia)

## How can [Task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) be achieved?

>"In a multiprocessor system, [task parallelism](https://en.wikipedia.org/wiki/Task_parallelism) is achieved when each processor executes a different [thread](https://en.wikipedia.org/wiki/Thread_(computing)) (or process) on the same or different data." (wikipedia)

## What is [Thread](https://en.wikipedia.org/wiki/Thread_(computing))?

>"A [thread](https://en.wikipedia.org/wiki/Thread_(computing)) of execution is the smallest sequence of programmed instructions that can be managed independently by a scheduler, which is typically a part of the operating system." (wikipedia)

>"[Thread](https://en.wikipedia.org/wiki/Thread_(computing)) is an execution unit that is part of a process." ([guru99](https://www.guru99.com/difference-between-process-and-thread.html))

## What is [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture))?

>"[Multithreading] is the ability of a central processing unit (CPU) (or a single core in a multi-core processor) to provide multiple threads of execution concurrently, supported by the operating system" (wikipedia)

## What is [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is the ability of different parts or units of a program, algorithm, or problem to be executed out-of-order or in partial order, without affecting the final outcome" (wikipedia)

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is when two or more tasks can start, run, and complete in overlapping time periods." ([stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

I found Stackoverflow definition more understandable.

## What is the difference between [parallelism](https://en.wikipedia.org/wiki/Parallel_computing) and [concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science))?

>"[Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) is when two or more tasks can start, run, and complete in overlapping time periods." ([stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

>"[Parallelism](https://en.wikipedia.org/wiki/Parallel_computing) is when tasks literally run at the same time, e.g., on a multicore processor." ([stackoverflow](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism))

## What is [Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing)?

>"[Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing) is a form of computing in which several computations are executed concurrently—during overlapping time periods—instead of sequentially—with one completing before the next starts." (wikipedia)

## How can [Concurrent computing](https://en.wikipedia.org/wiki/Concurrent_computing) be achieved?

>"In C++, the two most common ways of implementing concurrency are through multithreading and parallelism" ([educative.io](https://www.educative.io/blog/modern-multithreading-and-concurrency-in-cpp))

>"[Multi-threading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) is what usually refers to concurrent programming." ([mineiros.io](https://www.mineiros.io/blog/guide-to-multihreading-and-multiprocessing#multi-threading))

## How does [Concurrency](https://en.wikipedia.org/wiki/Concurrency_(computer_science)) achieved by [Multithreading](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) matters with [Parallelism](https://en.wikipedia.org/wiki/Parallel_computing)?

>"Threads are a software construct. I can start as many pthreads as I want, even on an old single core processor. So multi-threading is not necessarily parallel: it's only parallel if the hardware can support it. So if you have multiple cores and/or hyperthreading, your multi-threading becomes parallel." ([Is multithreading concurrent or parallel?, quora](https://www.quora.com/Is-multithreading-concurrent-or-parallel))

>"Threads are a software construct. I can start as many pthreads as I want, even on an old single core processor. So multi-threading is not necessarily parallel: it’s only parallel if the hardware can support it. So if you have multiple cores and/or hyperthreading, your multi-threading becomes parallel." ([Is threading parallel computing?, whatisany](https://whatisany.com/does-parallel-computing-use-multiple-threads/))

>"If your threads run on physical cores at the same time then they are parallel, otherwise they are just time-sharing or concurrent." ([Are threads concurrent or parallel?, whatisany](https://whatisany.com/does-parallel-computing-use-multiple-threads/))

>"You can have multithreading on a single core machine, but you can only have parallelism on a multi core machine (or multi proc, but I treat them the same)." ([Threading/Concurrency vs Parallelism, danielmoth](http://www.danielmoth.com/Blog/threadingconcurrency-vs-parallelism.aspx))

## Conclusion

- Multithreading is one way to achieve concurrency, and it achieves parallelism under multi-core hardware environment.

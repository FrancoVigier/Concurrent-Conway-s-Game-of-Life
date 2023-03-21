# Concurrent-Conway-s-Game-of-Life
 Concurrent Conway's Game of Life, developed on OS I

The parallelism problem is often very complex in situations where information created in another thread must be obtained.
To solve this type of problem we propose an information management system where the sections of memory that were updated are
clearly indicated, this allows to work in parallel, simplify the code and reduce costs in terms of waiting times to other threads.
We use Conway's game of life to demonstrate this system in an application that requires to have a previous copy of the 
board to pass to the next cycle. Our algorithm improves on the current state of the art on boards densely populated by live cells.
We show that by allowing for thread lag, i.e., when threads can work over different cycles, greater efficiency of computational 
time usage can be achieved, resulting in shorter computational times. Achieving shorter execution times.

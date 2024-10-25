# Car Traffic Simulator

A car traffic simulator coded in C++ using threads, mutexes, semaphores and monitors.

## Types of roads
There are three different types of roads implemented:

1. Narrow bridges: there is only one lane, so cars can only pass in one direction at a time.
2. Ferries: All cars are loaded onto the ferry and once it is full or a set amount of time passes, the ferry leaves for its destination.
3. Crossroads: four lanes joining at a crossroads, only one lane can enter the crossroad at a time, similar to narrow bridge but with many more permutations.

For more details, read "Question.pdf".

## How to use

In the "code" folder, in a shell run: `./simulator`, however, you will have to give a long set of standardized inputs.

To run the sample inputs in the "inputs_outputs" folder, you can either copy paste them into the shell after running the simulator or pipe them like this: `./simulator < input0.txt`

To run a set of pre-defined inputs automatically for grading, run `./grader` in the "code" folder.

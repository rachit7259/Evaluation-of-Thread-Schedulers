# Evaluation-of-Thread-Schedulers
Simulation of 4 different types of thread scheduling techniques using POSIX threads.

This is a C program utilizing pthreads.

The program initially takes user input for selecting the scheduling technique.

The program gets the data from the data.txt file.
The 1st integer is the number of threads.
Then sequentially each line of values are assigned to each thread.
The values are start_time, req_time and tprio respectively.

start_time : Time allocated for the thread to be scheduled at.
req_time : Time required by the thread to execute the task.
tprio : The thread priority based on which execution will be carried out.

One can modify the values accordingly to check the results.

The output gives the global time of the scheduler and the thread that is scheduled at that time.
If no threads are scheduled there is a blank space.

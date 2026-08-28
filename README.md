# Operating Systems Lab Manual

This repository contains a collection of C programs developed as part of the Operating Systems Laboratory. The programs demonstrate fundamental concepts and algorithms related to process management, CPU scheduling, process synchronization, and file management.

The CPU Scheduling section contains implementations of First Come First Serve (FCFS), Shortest Job First (SJF), Non-Preemptive Priority Scheduling, and Round Robin scheduling. These programs demonstrate concepts such as arrival time, burst time, waiting time, turnaround time, and scheduling algorithms.

The Process Management section contains a program demonstrating the use of the `fork()`, `exec()`, and `wait()` system calls. It illustrates process creation, execution of a new program, and synchronization between parent and child processes.

The Process Synchronization section contains an implementation of the Producer-Consumer problem using POSIX threads, semaphores, and mutexes. It demonstrates concepts such as mutual exclusion, critical sections, and thread synchronization.

The File Management section contains a file-copying program that uses the UNIX system calls `open()`, `read()`, `write()`, and `close()` to perform file operations.

All programs are written in C and are intended to be compiled using GCC on a Linux/UNIX environment. These implementations are maintained for academic and laboratory purposes to provide practical understanding of fundamental Operating Systems concepts.

## Repository Structure

CPU-Scheduling/
- fcfs.c
- sjf.c
- priority_scheduling.c
- round_robin.c

Process-Management/
- fork_exec_wait.c

Process-Synchronization/
- producer_consumer.c

File-Management/
- file_copy.c

## Author

Sharmila GRaj

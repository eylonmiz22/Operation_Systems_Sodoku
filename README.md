## Description: ##
This repository includes solutions to exercises, given as part of the Operating Systems course.

The program accepts 4 files of the sodoku solution board. 
The goal is to determine whether a given solution is legal or not according to sodoku game rules and to print the result.

This assignment was done by 4 methods:
1. Working with processes -> Create 3 children processes:
	- By using exec, pipe, dup syscalls, and the stdin/out file descriptors of the father and children processes.
	- By using mmap syscall to share a memory zone between the processes.
2. Working with POSIX Threads -> Create 27 (9 rows * 9 cols * 9 smallMats) : with and without mutex locks and condition variables.

## Instructions: ##
1. Please compile the program by the gcc compiler.
2. Some input txt files are attached here.

# Analyzing-Linux-Kernel-Statistics

Identifying what system calls are being used by various applications like Broweser, excel/word, compiling redis source code and benchmarking redis, standard linux commands like ls, cat, etc.

Measure the system call activity that is happening by using the strace/perf command.
Summarizing 

1. Which are the most popular system calls across the various applications
2. How much time is being spent in these various system calls.
3. Which are the most infrequently used system calls.
4. How much time is spent in locking?
5. How many threads are being used by each process?



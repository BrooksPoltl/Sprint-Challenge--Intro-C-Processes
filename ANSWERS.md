**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**

    Created.
        this is a new state that is waiting to ready
    Ready.
        this state is ready and waiting to execute
    Running.
        chosen for execution
    Blocked.
        Incapable of running.
    Terminated.
        process has finished running or is purposely killed.
    Swapped out and waiting.
        the process is set to the side for later use.
    Swapped out and blocked.
        the process is set to blocked when the process returns

**2. What is a zombie process?**
    completed execution, so it is terminated but still within the
    system


**3. How does a zombie process get created? How does one get destroyed?**
    created by completing a execution. You can kill it by the parent dying.


**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**
    Compiled languages only have to compile, and then they can be executed, while interpreted languages have to be parsed, interpreted, and executed each
    time they run. This greatly hurts efficiency in completing processes. 

# Threads


Multiple threading is used for concurrent execution and thread is part/one among the multithreads.

Calculating Factorial for big number may take huge time.
So, we can create threads and excute the computation concurrently.

While implementing:
1) Inherit from the parent Thread class(which has run method for main thread).
2)overide the run Method.

There are two types of threa:
1)Main thread - for running the main program and which has other child threads(which we create).
2)Deamon threads- for garbage collections,...

Deamon thread is the lowest priority and it is not considerd at all(when the main thread and other higher priority thread finishes execution,JVM  will exit itself and it will not even if Deamon threads are running(Deamon threads are terminated by jvm and then it exits)).

# Mutex and Channel basics

### What is an atomic operation?
> An atomic operation is an indivisible operation. This means that database operations occur either all at once or nothing occurs. Therefore, when a thread modifies the state of some object, no intermediate state is seen by other threads. Other threads either see the object as it was before or they see it as it is after the change.

### What is a semaphore?
> A semaphore is data structure that helps solving a variety of synchronization problems. It is a non-negative integer variable and used to control access to a common object used by two processes in a concurrent system. The semaphore is a variable to achieve process synchronization. This variable is incremented, decremented or toggled by threads. It can be understood as a kind of unit for available resources, that are coupled with operations to safely record when units are available, free or required.

### What is a mutex?
> Mutual exclusion is used in concurrent programs and shall prevent race conditions. If one thread is accessing a critical section due to execution, this critical section is locked for other threads, so that changes from two threads to the same part of the critical section cannot happen at the same time.

### What is the difference between a mutex and a binary semaphore?
> The binary semaphore is restricted to the values 0 and 1. This means it is only possible to secure a SINGLE shared resource, because the binary semaphore can only be incremented to 1.
A mutex gives the permission to access the critical section to only one process. Only the thread that locked the mutex can unlock it.

### What is a critical section?
> The critical section is a protected resource section (for example a data structure). It cannot be processed by more than one process at a time, because the resources in this section are shared between multiple processes. Simultaneous access of multiple processes to the same critical section could lead to unexpected or erroneous behaviour.

### What is the difference between race conditions and data races?
 > Race condition: The systems behaviour is dependent on the sequence or timing of processes or threads.
 Data race: When two threads are accessing the same memory section/ shared data at the same time and at least one of them is a write operation.

### List some advantages of using message passing over lock-based synchronization primitives.
> *Your answer here*

### List some advantages of using lock-based synchronization primitives over message passing.
> *Your answer here*

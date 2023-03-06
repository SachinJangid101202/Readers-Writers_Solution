# Readers-Writers_Solution
Starve free solution to Readers-Writers problem
#Description of Solution
2 integer variables are declared : currentlyReading represents number of readers that are currently in Critical Section.WaitingWriters to represent number of writers waiting to enter critical section.
2 boolean variables are declared : readersTurn represents whether there is any reader ready to enter critical section.writing represents whether any writer is there in critical section.
2 classes are declared for readers and writers respectively.
"readers" class has 2 function defined within its scope."doReading" function describes the possibility of a reader to enter critical section."freeReaders" function removes a particular reader from ready queue as it has completed its execution.
"writers" class has 2 function defined within its scope."doWriting" function makes a particular writer to wait or execute depending upon whether there is any reader or writer in critical section or no one is there in critical section."freeWriters" function frees a writers after it has completed its execution and permits a waiting reader to enter critical section.

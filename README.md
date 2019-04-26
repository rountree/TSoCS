# TSoCS
Notes, assignments, slides and errata for the The Science of Computer Science class

Insmix
======

Easy:
-----
0. What do each of the columns mean in the insmix.out file?  In the bblcount file?

1. Which of the options work?

2. What is the most-used instruction for /bin/ls?

3. Insmix doesn't appear to count memory instructions.  Modify Insmix to optionally capture 
and report these.  


Medium:
-------
1. Modify pin so that only a single routine is measured.

2. How much overhead does this pin tool add?


Hard:
-----
1.  Bus error.  [CANNOT REPRODUCE]
This works:     ./pin -t ./insmix.so -- ./FIRESTARTER -t 1 -n 1
This doesn't:   ./pin -t ./insmix.so -- ./FIRESTARTER -t 10 -n 1
Find and fix the bug.

2. Modify Insmix so that it is thread safe (and test on firestarter)

3. Which registers get used the most?  Modify Insmix to optionally report register counts.

4. Fix a broken option or two.

5. Make pin scale better over more threads.  

# ThreadBare

there are 5 example classes in this project.
Each one gets slightly more complex. The last one, ThreadTwoHashMapBroken, is pretty wrong,
and if you understand how it's different from ThreadTwoHashMap, you can probably figure out why it is broken.

read through each class, and run the main().
Look at how each one if different.
Yes, that's the point of this lab.

How many times do you have to run ThreadTwoHashMapBroken before you get
an exception? Just once.


WHY does it continue and exit with a 0 even after
the exception gets thrown? 
Because the Interrupted Exception thrown by the doDBProcessing method is handled??
Thrown when a thread is waiting, sleeping, or otherwise occupied, and the thread is interrupted, either before or during the activity.

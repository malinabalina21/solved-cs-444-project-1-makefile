Download Link: https://assignmentchef.com/product/solved-cs-444-project-1-makefile
<br>



<ol>

 <li>Create a single Makefile that will build all of the below C programs. Place them all in a single directory (no sub-directories). If you don’t have a Makefile, your submission will not be graded. If your Makefile does not build a portion of your assignment, that portion will receive a zero grade. I expect to build all the programs below by using the following two commands: make clean make all</li>

</ol>

If this does not work, it will be bad for your grade on this assignment.




<ol start="2">

 <li>Write a C program that calls fork(). Before calling fork(), have the parent process assign the value 100 to int called xx. What value is the value of xx in the child process? Have the parent process assign the value 999 to xx and have the child process assign the value 777 to xx. What happens to xx variable when both the child and parent change the value of xx? Have both processes print the value of xx.</li>

</ol>




<ol start="3">

 <li>Write a C program that opens a file name “JUNK.txt” (with the fopen() function call). Have the parent process print “before fork” into the file. The parent process should call fork() to create a new process. Have the parent process perform a for loop that prints “parent” into the open file 10 times. Have the child process perform a for loop that prints “child” into the open file</li>

</ol>

10 times. What happens when they are writing to the file concurrently, i.e., at the same time (answer this in the comments in your code)?




<ol start="4">

 <li>Write a C program using fork(). The child process should print “hello” to stdout; the parent process should print “goodbye” to stdout. <strong>Make sure that the child process always prints first</strong>. Can you do this without the parent calling wait() in the parent (and NOT using some big loop in the parent)?</li>

</ol>




<ol start="5">

 <li>Write a C program that calls fork() and then the child process calls each of the following exec() functions to run the program “ls -l -F -h”: execl(), execlp(), execv(), and execvp(). The parent process must wait until the child process is complete before it exits. Describe the differences of the exec functions in your code as comments.</li>

</ol>

<strong>Final note</strong>

The programming projects in this course are intended to give you basic skills. In later programming projects, we will <strong><em>assume</em></strong> that you have mastered the skills introduced in earlier programming projects. <strong>If you don’t understand, ask questions.</strong>



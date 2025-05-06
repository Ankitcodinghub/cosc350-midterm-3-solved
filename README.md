# cosc350-midterm-3-solved
**TO GET THIS SOLUTION VISIT:** [COSC350 Midterm 3 Solved](https://www.ankitcodinghub.com/product/cosc350-midterm-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97753&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC350 Midterm 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# Midterm 3 Programs

## Problem 1

Write two separate C programs: parent program (parent.c) and child program (child.c):

* child.c takes three command line arguments: the first one is a character (+ or -) followed by two integers. Depending on the value of the first parameter, child.c will perform addition (if + is passed in) or minus (if – is passed in) and display the result of the calculation.

* parent.c reads in two integers from the standard input and forks two child processes to run child.c. The first child process will run child.c with ‘+’ and the two integers read in from the standard input.The second child process will run child.c with ‘-‘ and the two integers read in from the standard input.

## Problem 2

Write a C program to act as the following:

* The child process sends the message “Hi, Mom” over a pipe to its parent process. The parent process reads the message from the pipe and prints it out to the standard input as “my child said” and the message fom the child, in this case, “Hi mom”. Then parent process senddss the message “I love you” over a pipe to its child.

* The child process reads the message and prints it to the standard output as “My mom said” and then the message from the parent process, in this case, “I love you”.

## Problem 3

Write two separate C programs: parent program (parent.c) and child program (child.c):

* The parent forks a child process to read messages from a pipe. The parents repeats this process infinitely: has an alarm clock that set of every 10 seconds. Whenever the alarm sets off, the parent writes a message “I am here, baby\n” to a pipe and sends a SIGUSR1 signal to its child.

* The child program, used by the above parent program, always waits for SIGUSR1. When SIGUSR1 arrives, the child reads the parent’s message from the pipe and displays it on the screen and goes back to wait for more SIGUSR1 signals.

## Problem 4

Write a C program to create three threads and each thread runs its own function fun1, fun2, and fun3 respectively.

* The first thread gets a command line integer value (from argv[1]) and multiply that value by 10.

* The second thread takes the result of the first thread and add 20 to it.

* The third thread takes the result of the second thread and divides it by 4.

* Then, the original program (main thread) prints the final results returned from each thread in the end.

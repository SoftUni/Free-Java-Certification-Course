<h1 align="center">7. For Loops</h1>

#### 1. Lesson Summary

In this lesson, we continue with the <strong>Java Basics Tutorial</strong>. That is the seventh part of this series, and if you want to see the complete list of lessons, you can do it <a href="https://softuni.org/free-courses/java-basics/">here</a>.

<span>In programming, a loop is used to repeat a block of code until a specified condition is met. The<strong> For Loop</strong> is best when you want to do something for a fixed number of times.</span>
<br>
How does <strong>For Loop</strong> work?</span>
<ol>
 	<li>Control falls into the <strong>For Loop</strong>. <strong>Initialization</strong> is done.</li>
 	<li>The flow jumps to the <strong>Condition.</strong></li>
 	<li>The <strong>Condition</strong> is tested.
<ol>
 	<li>If it is <strong>true</strong>, the flow goes into the body.</li>
 	<li>If it is <strong>false</strong>, the flow goes outside the loop.</li>
</ol>
</li>
 	<li>The statements inside the body of the loop get executed.</li>
 	<li>The <strong>update</strong> takes place, and the flow goes to Step 3 again.</li>
 	<li>The <strong>For Loop</strong> has ended, and the flow has gone outside.</li>
</ol>
<span>This process goes on until the test expression is <strong>false</strong>. When the test expression is <strong>false</strong>, the loop terminates.</span>
<p>Say we want to loop over a range of numbers and print out each one along the way. We can do this best with a <strong>For Loop</strong>. We will start from the first number, print it out, move to the next number to do the same thing, and continue until we’ve printed each number. Let’s print the numbers zero through nine:</p>
Let’s look at the first line of the <strong>For Loop</strong> and the three parts necessary to make it work. First, we have an<strong> initialization</strong> expression, then <strong>termination</strong> expression, and <strong>increment</strong> expression in the end.
<br>
<br>
The <strong>initialization</strong> expression initializes the loop and is only executed once when the loop starts. That is where you must declare and initialize a variable, usually of type int, to hold an initial number that will be used to loop until it reaches a specific value. That can be thought of as the start of the range to iterate over. In our case, we started at 0.
<br>
<br>
The <strong>For Loop</strong> will continue looping until the <strong>termination</strong> expression evaluates to <strong>false</strong>. The <strong>termination</strong> expression is evaluated before each iteration of the loop, and it must return a <strong>boolean</strong> to decide whether or not to continue looping. If the <strong>boolean</strong> returned is equal to <strong>true</strong>, we will run the body of our <strong>For Loop</strong> again. In our case, the loop terminates after it prints 9.
<br>
<br>
The increment expression is executed after each iteration of the loop. To increment the variable, we initialize it by using the<strong> ++</strong> operator. That allows the <strong>termination</strong> expression to know how many times the loop loops. The <strong>initialization</strong> variable count, in our example, starts at 0, and it’s printed out. Then the <strong>incrementer</strong> increments it, and the next iteration of the loop runs to print the new value and continues that way until it prints 9.
<br>
<br>
In conclusion, you should use a <strong>For Loop</strong> when you know how many times the loop should run. There are other more<strong> advanced iteration structures</strong> that we will look at in the next article.


#### 2. Table of Contents
* [1. Lesson Summary](#1-Lesson-Summary)
* [2. Table of Content](#2-Table-of-Content)
* [3. YouTube Video](#3-YouTube-Video)
* [4. Lesson Topics](#4-Lesson-Topics)
* [5. Resources](#5-Resources)
* [6. Practical Exercises](#6-Practical-Exercises)
* [7. Navigation](#7-Navigation)

#### 3. Lesson Video
<p align="center">
<a href="https://youtu.be/VyoaWLnbDi0">
    <img src="" alt="YouTube Thumbnail">
 </a>
</p>

#### 4. Lesson Topics
In this lesson we cover the following topics:
* Increment adn Decrement
* For Loops
* Loops with a Step
* Iterating over Characters
* Infinite Loops

#### 5. Resources
<p>Remember that coding is a skill, which should be practiced. To learn to code, you should write code every day for a long time. Watching tutorials is not enough. You should code! </p>

| Resources | Link |
| ----- | ----- |
| Lesson Video| [YouTube](https://youtu.be/VyoaWLnbDi0) |
| Lesson Content | [SoftUni](https://softuni.org/code-lessons/java-basics-tutorial-part-7-for-loops) |

#### 6. Practical Exercises
<a href="https://softuni.org/checkout/join-community">Register</a> now and take your free resources right away! You will get access to **automated exercises** which will sharpen your coding skills. Become a member of the SoftUni Global Community and communicate with other students and mentors and get help for **FREE**.
Please watch the video and solve the exercise problems. Writing code is the only way to master the skill of coding. Submit your code at the SoftUni Judge.

| Resources | Link |
| ----- | ----- |
| Problem Descriptions | [Available after Free Registration](https://softuni.org/code-lessons/java-basics-tutorial-part-7-for-loops) |
| Submit Solutions for Evaluation | [Available after Free Registration](https://softuni.org/code-lessons/java-basics-tutorial-part-7-for-loops) |

#### 7. Navigation

<p align="center">
    « Previous Lesson &nbsp; | &nbsp; <a href="https://github.com/SoftUni/Free-Java-Certification-Course">Home</a> &nbsp; | &nbsp; <a href="https://github.com/SoftUni/Free-Java-Certification-Course/tree/main/lessons/02-InteliJ-IDEA.md">Next Lesson »</a>
</p>

<p align="center">
    <a href="https://github.com/SoftUni/Free-Java-Certification-Course/blob/main/lessons/06-Advanced-Conditional-Statements.md">« Previous Lesson</a> &nbsp; | &nbsp; <a href="https://github.com/SoftUni/Free-Java-Certification-Course">Home</a> &nbsp; | &nbsp; <a href="https://github.com/SoftUni/Free-Java-Certification-Course/blob/main/lessons/08-While-Loops.md">Next Lesson »</a>
</p>
<h1 align="center">6. Advanced Conditional Statements</h1>

#### 1. Lesson Summary

<p>There may be a situation when you want to check for another condition after a condition resolves to true. In such a situation, you can use <strong>nested conditional statements</strong>. In them, you can have a statement inside another statement and so on.</p><p>A <strong>Switch Statement</strong> is usually more efficient than a set of <strong>nested</strong> <strong>ifs</strong>. When we have to choose which one to use, it's based on readability and the expression that the statement is testing. We use a <strong>switch statement</strong> to test the value of a variable against a list of case values, while we use an <strong>if-else statement</strong> for taking a decision.</p><p><strong>If-else statement</strong> evaluates <strong>integer</strong>, <strong>character</strong>, <strong>pointer</strong>, <strong>floating-point type</strong>, or <strong>boolean type</strong>. On the other hand, the <strong>switch statement</strong> evaluates only character or an integer datatype. It’s known to be hard to edit <strong>if-else statements</strong> since it’s tedious to trace where the correction is required. Many people agree that it’s much simpler to correct <strong>switch statements</strong> since they’re easy to trace.</p><p>There can be any number of case statements within a <strong>switch statement</strong>. Each case is followed by the value to be compared to and after that a colon. When the variable being <strong>switched on</strong> is equal to a case, the statements following that case will execute until a <strong>break</strong> statement is reached. If that happens, the <strong>switch</strong> terminates, and the flow of control jumps to the next line following the<strong> switch statement</strong>. Not every case needs to contain a <strong>break</strong>. If no <strong>break</strong> appears, the flow of control will fall through until a <strong>break</strong> is reached. all the <strong>case statements</strong> will get executed as soon as the compiler finds a comparison to be <strong>true</strong>.</p><p>A<strong> switch statement</strong> can have an optional <strong>default case</strong>, which must appear at the end of the <strong>switch</strong>. The <strong>default case</strong> can be used to perform a task when none of the cases are <strong>true</strong>. No <strong>break</strong> is needed in the <strong>default case</strong>. The <strong> switch statement</strong> works much faster than an equivalent <strong>if-else statement</strong>. During execution, instead of checking which case is matching, it only decides which case has to execute. It’s more readable compared to <strong>if-else statements</strong>.</p>

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
<a href="https://youtu.be/sXM31yfsj04">
    <img src="" alt="YouTube Thumbnail">
 </a>
</p>

#### 4. Lesson Topics
In this lesson we cover the following topics:
* What is coding and how to write code in Java?
* Online coding environments and how to use repl.it to write Java code.
* Writing commands in Java
* Coding concepts
  * Programming
  * Commands
  * Code
  * Algorithms
  * IDEs
* Coding Exercises

#### 5. Resources
<p>Remember that coding is a skill, which should be practiced. To learn to code, you should write code every day for a long time. Watching tutorials is not enough. You should code! </p>

| Resources | Link |
| ----- | ----- |
| Lesson Video| [YouTube](https://youtu.be/sXM31yfsj04) |
| Lesson Content | [SoftUni](https://softuni.org/code-lessons/java-basics-tutorial-part-1-getting-started-with-java/) |

#### 6. Practical Exercises
<a href="https://softuni.org/checkout/join-community">Register</a> now and take your free resources right away! You will get access to **automated exercises** which will sharpen your coding skills. Become a member of the SoftUni Global Community and communicate with other students and mentors and get help for **FREE**.
Please watch the video and solve the exercise problems. Writing code is the only way to master the skill of coding. Submit your code at the SoftUni Judge.

| Resources | Link |
| ----- | ----- |
| Problem Descriptions | [Available after Free Registration](https://softuni.org/code-lessons/java-basics-tutorial-part-1-getting-started-with-java/) |
| Submit Solutions for Evaluation | [Available after Free Registration](https://softuni.org/code-lessons/java-basics-tutorial-part-1-getting-started-with-java/) |

#### 7. Navigation

<p align="center">
    <a href="https://github.com/SoftUni/Free-Java-Certification-Course/blob/main/lessons/05-Conditional-Statements.md">« Previous Lesson</a> &nbsp; | &nbsp; <a href="https://github.com/SoftUni/Free-Java-Certification-Course">Home</a> &nbsp; | &nbsp; <a href="https://github.com/SoftUni/Free-Java-Certification-Course/blob/main/lessons/07-For-Loops.md">Next Lesson »</a>
</p>

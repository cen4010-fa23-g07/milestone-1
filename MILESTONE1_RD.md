
# This will be an outline of the milestone 1 submission, it will also include the rough draft of each section.

Contents:

1. Executive Summary.
2. Competitive Analysis
3. Data Definition
4. Overview, Scenarios, Use-Cases.
5. Initial List of High Level Functional Requirements.
6. List of Non-Functional Requirements.
7. High Level System Architecture
8. Team
9. Checklist

***This document has been converted to markdown for ease of editing, the final document will be converted back to ODT and then PDF.***

## Executive Summary. One page.

*This will be a summary of our project and what makes it good. I will include some starting text to help grow this page. Feel free to add or make changes to what is here.*

The project name is Clever Calc, a Math utility designed to help aid students learning how to solve algebraic equations in the terms of a desired variable. The user enters an equation they would like to solve. If the equation is valid, the program will ask for a variable in which the equation is to be solved for or for which the equation is to be put in terms of. The equation solver will then ‘solve’ the equation, printing out each step it performs as it functions. When the solution is reached, the student will have a step by step instruction on how to solve that equation. Additionally, the software can be paused at any point in the solution path to give the student the opportunity to figure out the problem on their own. This software may also solve simple systems of equations if it is needed. Tools of a similar caliber already exist on the market, but often come with one or more of three caveats. Programs either solve the equation through approximation or brute force, don’t provide the specific instructions to the user, or charge users a membership fee to view the solution. In regards to the last caveat, even those programs, which display the necessary solution, only show the raw changes in the equations. Not specifying the exact method of each step. Our project acts as a training utility. Students can enter training mode, in which the student will tell the program what the next step in solving the equation is. The program will correct any errors and then continue to the next step. Our software will run completely offline as an executable file, but more importantly, will be included as a C++ source-code library. In short, this allows other educational software designers to implement our tool as part of their own learning software.

## Competitive Analysis

*Here will be a table demonstrating the advantages of competitor products vs our own. This is unfinished. We can add more competitors and more feature checks to make ourselves look better.*


|                 | Step by Step Solutions? | Offline use? | Software integration? | Pausable solutions? | Guided learning? |
| --------------- | ----------------------- | ------------ | --------------------- | ------------------- | ---------------- |
| **Keisan**      | No.                     | No.          | No.                   | No.                 | No.              |
| **Wolfram**     | Only with Premium.      | Yes.         | Yes.                  | No.                 | No.              |
| **Symbolab**    | Yes.                    | No.          | No.                   | No.                 | No.              |
| **Mathway**     | Only with Premium.      | Yes.         | No.                   | No.                 | No.              |
| **Clever Calc** | Yes.                    | Yes.         | Yes.                  | Yes.                | Yes.             |

Our product "Clever Calc" will do everything our competitors' products can do and more. All of these products can solve equations step-by-step, but ours gives users reasoning for which steps have been taken, as well as the ability to pause during solving. The ability to pause allows users to finish the rest of the problem on their own, even if they were stuck on one part. Our product will also feature easy plotting -- all that is needed to do is save the equation and use the plotting functionality, while our competitors' products force users to go to another page. Our product also includes software integration, meaning that it can be included in other programs if desired.


## Data Definition

*Dictionary and important terms/phrases.*

**Algebra** - The expression of problems as math equations.  
**Linear Equation** - Equation in terms of one variable with only a coefficient and constant.  
**Variable** - An placeholder for numeric data, to be filled in by the user or solved by the program’s algorithm.  
**Software Library** - A set of code designed to be incorporated into and compiled with a user software.  
**Command line** - A developer-focused application that can be used to execute programs whilst providing a syntax to provide those same programs with parameters and options.  
**Memory** – Storing solved math equations (for later usage if needed)  
***Etc - add more definitions as needed.***  

## Overview, scenarios, and use-cases.

*Tell a story / set of steps regarding the usage of our software*

*IE little jimmy jimmy used our software to get an A, Albanian software company uses our library to design an education software for their schools, etc. etc. Maybe some specific descriptions about ideal uses. Ie steps to use it (click this type that).*




Primary usage of our software will be through the user interface, where a student (our user, in this case) will use the program to learn the steps required to solve for linear equations. The prospective student will open up our software, and select the solving mode. Our student wishes to learn how to solve a linear equation. So, the student selects the linear equation mode, and enters the linear equation. If any errors were made, our software reminds the student to make a correction, and then  proceed. Once ready, the student can pick their desired operation mode. We suspect that the step mode will be very popular. The student clicks each step and reads very carefully. They sudy each step and make sure to understand how to solve their math equations with better confidence. Once the student feels ready, they can activate quiz mode, and then test themselves against the computer. If the student, teacher, or parent wants to see the progress they're making, the stats will always be saved.

Additionally, the code can also be used as a library: If a developer needs a simple and efficient library to compute and solve for linear equations, he or she can import the code onto their project(s), and make use of the simple library provided. There are two main ways in which the project can be used:

1. The developer makes use of it as a library: By importing the C++ code as a library to their project(s), developers can take advantage of the preexisting code written in this project. Using a simple and comprehensive API, they can proceed to use it to solve linear equations as an embedded system. After importing the library, the developer can have access to the methods and functions, which he or she can then invoke and compose to accomplish his or her goals.
2. The program can be invoked from the command line: By executing a specific command on the command line, developers or consumers can quickly gain access to the tool. Using the interactive menu, the consumer can choose from a list of useful options and decide what operation they would like to perform, be it solving linear equations or creating a simple visual graph.



## Initial list of high-level requirements.

*Numbered list of required functionality of 4-5 line desc.*

1. Set usage functionality (linear equation, system of equations, etc)
    - Set the program functionality for different types of equations.
    - Base options will include linear equations and systems of equations.
    - Chosen via a selection menu, default will be linear equations.
    - Future functionality may include limits, derivatives, and integrals.
2. Enter equation.
    - User will type the equation using variables, one equality operator, and various required operator symbols.
    - In system of equations, the user will enter multiple equations.
    - Once are equations are valid, the user may select a solve mode.
3. Solve mode.
    - Several solve modes are included, and can be chosen from by the user.
    - Instant mode: Once activated, the entire solution and required steps are revealed to the user.
    - Step mode: Reveals one step of the solution to the user after each activation.
    - Quiz mode: Prompts the user for the next step towards the solution, and checks for accuracy.
4. History
    - Each equation is stored in the history, for the user to revisit.
    - Over time old solutions are culled.
    - User accuracy in the quiz mode will be saved to user's stats. This can be cleared at any time.
5. Plotting
    - Ask user if the linear expression needs to be graphed for visual understanding.
6. Source-code Library
    - All essential functions of the software will be avaliable as a C++ source-code library.
    - Usage of all primary functions, including the usage type, equation solving, and history/retreval will be avaliable.

## Non-Member
    i. The system prompts the user to create which allow for the user to save solutions 

## List of non-functional requirements.

*Self explanatory, like func requirements.*

1. Performance
    - Fast must be fast
2. Library
    - Usable as a library.
3. Desktop compatible
4. 24/7 usage uptime
5. Usability
    - To be able to use with a relatively understandable interface.
6. Maintenance
    - A lot of debugging, testing, and overall modifications implemented onto our product

## High-level system architecture

**Languages:** C++  
**Tools:** g++, Visual Studio  

## Team

Scrum Master  
- Dante Ricketts

Product Owner  
- Yurixander Ricardo Silva

Developers  
- Clinton Hoang
- Lauren Morlock
- Zee Fisher


## Checklist

*Copied from milestone assignment*

1.  Team decided on basic means of communications: **Done.**
2.  Team found a time slot to meet outside of the class: **Done.**
3.  Front and back end team leads chosen: **Done.**
4.  Github master chosen: **Done.**
5.  Team ready and able to use the chosen back and front-end frameworks: **Done.**
6.  Skills of each team member defined and known to all: **Done.**
7.  Team  lead  ensured  that  all  team  members  read  the  final  M1  and agree/understand it  before submission: **Done.**

 


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

The project name is a Math utility designed to help aid students learning how to solve algebraic equations in the terms of a desired variable. The user enters an equation they would like to solve. If the equation is valid, the program will ask for a variable in which the equation is to be solved for or for which the equation is to be put in terms of. The equation solver will then ‘solve’ the equation, printing out each step it performs as it functions. When the solution is reached, the student will have a step by instruction on how to solve that equation. Additionally, the software can be paused at any point in the solution path to give the student the opportunity to figure out the problem on their own. This software may also solve simple systems of equations if it is needed. Tools of a similar caliber already exist on the market, but often come with one or more of three caveats. Programs either solve the equation through approximation or brute force, don’t provide the specific instructions to the user, or charge users a membership fee to view the solution. In regards to the last caveat, even those programs, which display the necessary solution, only show the raw changes in the equations. Not specifying the exact method of each step. Our project acts as a training utility. Students can enter training mode, in which the student will tell the program what the next step in solving the equation is. The program will correct any errors and then continue to the next step. Our software will run completely offline as an executable file, but more importantly, will be included as a C++ source-code library. In short, this allows other educational software designers to implement our tool as part of their own learning software.

## Competitive Analysis

*Here will be a table demonstrating the advantages of competitor products vs our own. This is unfinished. We can add more competitors and more feature checks to make ourselves look better.*


|                 | Step by Step Solutions? | Can it be used offline? | Can it be worked into other softwares? |
| --------------- | ----------------------- | ----------------------- | -------------------------------------- |
| **Wolfram**     | Only with Premium.      | Yes.                    | Yes.                                   |
| **Symbolab**    | Yes.                    | No.                     | No.                                    |
| **Our Product** | Yes.                    | Yes.                    | Yes.                                   |

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

The tool can be used to quickly compute linear equations, through a high-level interface. Developers specifically can take advantage of this; by embedding it into the terminal as a command, it is easily and quickly accessible. Additionally, the code can also be used as a library: If a developer needs a simple and efficient library to compute and solve for linear equations, he or she can import the code onto their project(s), and make use of the simple API provided. There are two main ways in which the project can be used:

1. The developer makes use of it as a library: By importing the C++ code as a library to their project(s), developers can take advantage of the preexisting code written in this project. Using a simple and comprehensive API, they can proceed to use it to solve linear equations as an embedded system. After importing the library, the developer can have access to the methods and functions, which he or she can then invoke and compose to accomplish his or her goals.
2. The program can be invoked from the command line: By executing a specific command on the command line, developers or consumers can quickly gain access to the tool. Using the interactive menu, the consumer can choose from a list of useful options and decide what operation they would like to perform, be it solving linear equations or creating a simple visual graph.

Adding on, if the answer given satisfies the user and is in need in another execution somewhere else, then we can have the answer given memory stored (if the consumer so desires) in order to be used at a later arithmetic expression.

## Initial list of high-level requirements.

*Numbered list of required functionality of 4-5 line desc.*

1. Set usage functionality (linear equation, system of equations, etc)
    - This will be performed by doing (). It will appear as () to the user. They will (). Etc.
2. Enter equation.
    - Done by typing equations and defining vars, performed by doing (), or by (). Includes the option of (). Autofill new equation option etc. etc.
3. Solve mode.
    - Solve fast, solve slow, against the computer, timer, etc. etc.
4. Memorize
    - After solving, put the answer into memory for later usage or even collecting data.
5. Plotting
    - Ask user if the linear expression needs to be graphed for visual understanding.
6. Maybe more stuff added here. And beyond.

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

## Team

Scrum Master  
- Name

Product Owner  
- Yurixander Ricardo Silva

Developers  
- Clinton Hoang


## Checklist

*Copied from milestone assignment*

1.  Team decided on basic means of communications
2.  Team found a time slot to meet outside of the class
3.  Front and back end team leads chosen
4.  Github master chosen
5.  Team ready and able to use the chosen back and front-end frameworks
6.  Skills of each team member defined and known to all
7.  Team  lead  ensured  that  all  team  members  read  the  final  M1  and agree/understand it  before submission

 

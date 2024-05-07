# Unified Software Development Process
Simulation of a real unified software development process (skiping the actual coding of the project)

## Table of Contents
1. [About](#about)
2. [Full Document](#full-document)
3. [Project Goal and Requirements](#project-goal-and-requirements)
   * [Business Model & Requirements](#business-model--requirements)
   * [Analysis](#analysis)
   * [Design](#design)
   * [Implementation](#implementation)
   * [Test](#test)
4. [Key Learnings](#key-learnings)
5. [Credits](#credits)

## About
This project is our coursework assignment for the **"Software Analysis & Design"** course at Universidad Siglo 21, aimed at demonstrating our understanding in the unified process for software development and various UML diagrams.

## Full Document
If you want to take a look at the whole assignment where we carry out the whole unified process you can check this [PDF Document](https://drive.google.com/file/d/15fQvwXxpJI14_KzwigPEppETJDYhXhHS/view?usp=sharing)

## Project Goal and Requirements
The **full assignment description** is available to download in this [PDF document](https://drive.google.com/file/d/1G32OW6swVtnQwvlGCfs_VZZQCVRMvv71/view?usp=sharing).

The project aim is to choose a well-known application (such as Facebook, Spotify or similar) and imagine a brand new feature for it.
Once decided the feature we have to follow the _Unified Software Development Process_ throughout all it's stages developing the specified artifacts (such as **UML Diagrams** using [draw.io](https://draw.io)) for each workflow in the process:
  1. ### Business Model & Requirements
      Here we have to explain our chosen feature and why we think it's going to add value to the app. And also describe the system's and user's needs at a high abstraction level. The main artifacts for this workflow are:
     * **The requirement's backlog**: This [document](Business%20Model%20%26%20Requirements/Requirements%20Backlog.pdf) lists all functional and non-functional requirements that our feature should have.
     * **The use case model**: This [UML diagram](Business%20Model%20%26%20Requirements/Use%20Case%20Diagram.PNG) describes the users's needs, the interactions between the users and the system, and the required behavior of the system to satisfy these needs.
     * **Traceability matrix**: This [matrix](Business%20Model%20%26%20Requirements/Traceability%20Matrix.pdf) assigns each requirement a corresponding code to mantain traceability and follow-up for each requirement in future artifacts.
  2. ### Analysis
      Here, based on the previous artifcats, we have to continue the process by removing and abstraction layer while we still hide implementation details, such as the chosen programming language. The aim of this workflow is to establish and validate the system architecture. The main artifcats are:
     * **Analysis's class diagram**: This [diagram](Analysis/Analysis%27s%20class%20diagram.PNG) describe the system following the **Entity-Control-Boundary** pattern, specifying its relations and functionalities without specifiying implementation details.
     * **Collaboration diagram**: This [artifact](Analysis/Collaboration%20diagram.PNG) uses the identified classes, we have to make an UML collaboration diagram explain how this classes will be able to perform some of the identified use cases in the previous workflow.
  3. ### Design
      In this workflow we remove another abstraction layer and we describe the actual realizations of the use cases in a specified enviorment (in this case a **Java** application). We get out of the _Entity-Control-Boundary_ pattern used in the analysis model and think about how we are going to implement it in the real world. The primary artifacts we have to develop are:
     * **Design's class diagram**: This [diagram](Design/Design%27s%20class%20diagram.pdf) shows class relationships, attributes and functions in an specified language, it is especially useful for communicating class hierarchies and collaborations to accomplish the defined use cases. Here we have to specify the classes access modifiers, the functions parameters and classes relation's multiplcities.
     * **Sequence diagram**: Diagrams the classes's interactions arranged in time sequence. This [diagram](Design/Sequence%20diagram.PNG) depicts the processes and objects involved and the sequence of messages (functions) exchanged needed to carry out the specified use case.
  4. ### Implementation
     Since the aim of this course isn't to code a functional application and just simulate the unified process we are going to skip the most relevant artifact in this workflow, the source code itself, instead we are going to explain decisions we've took on **data persistence**, **cybersecurity measures**, **testing** and **application hosting** without actually implementing them in an application. The main artifact we have to develop in this workflow is:
     * **Deployment diagram**: This [UML diagram](Implementation/Deployment%20diagram.PNG) illustrates the mapping of the previous generated software components onto the physical resources of a real system, such as servers, processors, storage devices, and network infrastructure
  5. ### Test
     The aim of the test workflow is to ensure that the system provides the required functionality. As the required functionality was originally captured in the form of the use cases, the system should be tested against the use cases that we've originally identified.
     
     In a real scenario, in the test workflow we should test the source code of the program by doing unit testing, user acceptance testing and so on, but since we hadn't developed the application we are going to simulate it by writing test cases and testing procedures without actually using them. Main artifacts:
     * **Test plan**: This [document](Test/Test%20plan.PNG) (in this case is simulated by a table) outlines the objective, strategies, procedures, goals, estimation, and resources needed for the successful testing of all the use cases.
     *  **Test procedure**: This [artifact](Test/Test%20procedure.PNG) is a detailed set of instructions that a tester (wether it's a human or an algorithm) follows to execute a specific test. It is a focused set of activities that are performed to achieve a particular testing objective. Therefore eliminating the possibility of overlooking crucial aspects
     *  **Test evaluation**: In this [artifact](Test/Test%20evaluation.pdf) we document all the test cases and it's results and we compare them against the results we expected. Since we didn't acutally test any software, we made up a table to represent what a real test evaluation might look in the real world.

To see all the explained diagrams and the documentation of the whole process, you can [download the PDF document](https://drive.google.com/file/d/15fQvwXxpJI14_KzwigPEppETJDYhXhHS/view?usp=sharing) of the assignment.


## Key Learnings
* Collaboration and effective **communication** with classmates.
* **Documenting** the whole process in a word document following APA format style.
* Creating **UML diagrams** using [draw.io](https://draw.io).
* Understanding all the stages of the **Unified Software Development Process**
* Designing system architectures based on **client's requirements** and analysis.
* Recognized the importance of adhering to specified and documented processes in software development.
* How to go through all the **workflows** in the process while maintaing traceability.

## Credits
Authors:
* [Tomas Temporelli](github.com/tototempo)
* [Ignacio Garcia](github.com/nachog2000)
* [Alejandro Zdut](github.com/alezdut)
* Nicolas Luccatto

# Unified Software Development Process
Simulation of a real unified software development process (skiping the actual coding of the project)

## Table of Contents
1. [About](#about)
2. [Full Document](#full-document)
3. [Project Goal and Requirements](#project-goal-and-requirements)
4. [Key Learnings](#key-learnings)
5. [Credits](#credits)

## About
This project is coursework for the **"Software Analysis & Design"** course at Universidad Siglo 21, aimed at demonstrating our understanding in the unified process for software development and different UML diagrams.

## Full Document
If you want to take a look at the whole assignment where we carry out the whole unified process you can check this [PDF Document](https://drive.google.com/file/d/15fQvwXxpJI14_KzwigPEppETJDYhXhHS/view?usp=sharing)

## Project Goal and Requirements
The **full assignment description** is available to download in this [PDF document](https://drive.google.com/file/d/1G32OW6swVtnQwvlGCfs_VZZQCVRMvv71/view?usp=sharing).

The project aim is to choose a well-known application (such as Facebook, Spotify or similar) and imagine a brand new feature for it.
Once decided the feature we have to follow the _Unified Software Development Process_ throughout all it's stages developing the specified artifacts (such as **UML Diagrams** using [draw.io](https://draw.io)) for each workflow in the process:
  1. **Business Model & Requirements:** Here we have to explain our chosen feature and why we think it's going to add value to the app. And also describe the system's and user's needs at a high abstraction level. The main artifacts for this workflow are:
     * _The requirement's backlog_: Lists all functional and non-functional requirements that our feature should have.
     * _The use case model_: Describes the users's needs, the interactions between the users and the system, and the required behavior of the system to satisfy these needs.
     * _Traceability matrix_: Assigns each requirement a corresponding code to mantain traceability and follow-up for each requirement in future artifacts.
  2. **Analysis:** Here, based on the previous artifcats, we have to continue the process by removing and abstraction layer while we still hide implementation details, such as the chosen programming language. The aim of this workflow is to establish and validate the system architecture. The main artifcats are:
     *_Analysis class diagram_: Describe the system following the **Entity-Control-Boundary** pattern, specifying its relations and functionalities without specifiying implementation details.
     * _Collaboration diagram_: Using the identified classes, we have to make an UML collaboration diagram explain how this classes will be able to perform some of the identified use cases in the previous workflow.
  3. **Design:** In this workflow we remove another abstraction layer and we describe the actual realizations of the use cases in a specified enviorment (in this case a **Java** application). We get out of the _Entity-Control-Boundary_ pattern used in the analysis model and think about how we are going to implement it in the real world. The primary artifacts we have to develop are:
     *_Design class diagram_: This diagram shows class relationships, attributes and functions in an specified language, it is especially useful for communicating class hierarchies and collaborations to accomplish the defined use cases. Here we have to specify the classes access modifiers, the functions parameters and classes relation's multiplcities.
     *_Sequence diagram_: Diagrams the classes's interactions arranged in time sequence. This diagram depicts the processes and objects involved and the sequence of messages (functions) exchanged needed to carry out the specified use case.
  4. **Implementation**:
  5.     

To see all the explained diagrams and the documentation of the whole process, you can [download the PDF document](https://drive.google.com/file/d/15fQvwXxpJI14_KzwigPEppETJDYhXhHS/view?usp=sharing) of the assignment.


## Key Learnings
* **Team work** and communication.
* **Documentation** and explanation of the project in a word document following APA format style.

## Credits
Authors:
* [Tomas Temporelli](github.com/tototempo)
* [Ignacio Garcia](github.com/nachog2000)
* [Alejandro Zdut](github.com/alezdut)
* Nicolas Luccatto

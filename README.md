# Learn Geometry with Augmented Reality

## Table of Contents
1. [Introduction](#1-introduction)
   - [Problem Statement](#11-problem-statement)
2. [Aim and Objective](#2-aim-and-objective)
3. [Motivation](#3-motivation)
4. [Literature Review](#4-literature-review)
   - [Existing System](#41-existing-system)
   - [Proposed System](#42-proposed-system)
5. [Project Description](#5-project-description)
   - [Modules](#51-modules)
   - [Project Scheduling](#52-project-scheduling)
6. [Analysis](#6-analysis)
   - [Functional Requirements](#61-functional-requirements)
   - [Non-Functional Requirements](#62-non-functional-requirements)
7. [Software Requirements](#7-hardware-and-software-requirements)
8. [System Diagram](#8-system-diagram)
   - [Flowchart](#81-flowchart)
   - [AR Block Diagram](#82-ar-block-diagram)
9. [Implementation Methodology](#9-implementation-methodology)
   - [Database](#91-database)
   - [Application](#92-application)
10. [Result](#10-result)
11. [Conclusion](#11-conclusion)

## 1. Introduction
### 1.1 Problem Statement

3D Geometry is considered one of the most difficult areas of mathematics. To understand this topic, various skills like visualization and spatial reasoning are required. These skills allow you to deal with three-dimensional shapes. However, it is much more difficult for kids to grasp the notion of three-dimensional objects, and often spatial geometry remains abstract to them for the rest of their education. Augmented Reality (AR) can play a vital role in teaching solid geometry to school students by providing an interactive and visual learning experience.

## 2. Aim and Objective
The project aims to present 3 Dimensional Geometrical figures in Augmented Reality view for a better understanding of the shapes. The objective is to make school students understand the 3D Geometrical shapes in the best possible way, i.e., by the application of Augmented reality. This will be a mobile application where the user can make his/her profile and track his 3D Geometry learning. In this app, users will be provided with an option to choose between different shapes for viewing in Augmented Reality space along with its details. Also, the user has an option to take a quiz to evaluate his/her learning.

## 3. Motivation
When it comes to learning some concepts in mathematics like 3D Geometry, it becomes difficult for students to visualize and understand the Geometrical figures by their 2D representation in books. It's difficult to visualize and get a clear understanding of a given 3D shape according to its 2D representation. Hence, having a mobile application for providing the actual 3D view of the given shape using Augmented Reality would make it easier for school students to understand the 3 Dimensional figure, its properties, and concepts related to it.

## 4. Literature Review
### 4.1 Existing System
Currently, school students learn 3D Geometry through books where 3D shapes are represented in 2D pages. Hence, students find it difficult to visualize and understand the actual 3D shape through its representation in books. Learning 3D geometry through this approach doesn't necessarily clear one's concept around the given Geometrical figure.

### 4.2 Proposed System
In this mobile application, the user is provided with options to view the given 3D Geometrical shape in AR view and to evaluate the learning by giving the quiz/test. For viewing the 3D Geometrical shape in the AR view, the user is provided with options to choose between different shapes and view it in its AR view along with its details. All the required information regarding the shape is provided with the AR view itself so the concepts related to any given geometrical shape get cleared after which the user can give the quiz to test the learned concepts and a score for the quiz is provided at the end of the test.

## 5. Project Description
### 5.1 Modules
The project consists of the following modules:
- Android: Implements the activity lifecycle and user interface for the mobile application.
- Augmented Reality: Utilizes Markerless AR technology to present 3D geometrical shapes in an AR view.
- ARCore SDK: Provides motion tracking, environmental understanding, and depth understanding to integrate virtual content with the real world.

### 5.2 Project Scheduling
The project is divided into covering tasks such as app wireframe creation, content planning, database setup, AR implementation, testing, and documentation.

## 6. Analysis
### 6.1 Functional Requirements
The application will include the following functionalities:
- User Sign in (Using Google account)
- User Log out
- Quiz section with quiz results
- Augmented reality view of 3D solids
- Descriptions and formulae related to 3D shapes

### 6.2 Non-Functional Requirements
Various non-functional requirements, such as performance, scalability, security, usability, and data integrity, need to be considered for the application.

## 7. Software Requirements
A list of technologies used within the project
* Kotlin
* Firebase
* ARCore
* Sceneform

## 8. System Diagram
### 8.1 Flowchart
![Flowchart](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/Flowchart.png)

### 8.2 AR Block Diagram
![AR Block Diagram](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/AR%20Block%20Diagram.png)

## 9. Implementation Methodology
### 9.1 Database
The application uses Firebase as the backend platform, providing a real-time database and authentication. The database includes collections for user information and quiz data.

### 9.2 Application
The Android application is coded in Kotlin, utilizing various activities, DAOs, models, and utility classes. Each activity follows the activity lifecycle and interacts with the database and AR functionality.

## 10. Result
The application is tested on both an Android emulator and a physical device. Users can sign in with their Google account, attempt quizzes, and view 3D shapes in the AR environment. Screenshots of the application in action are provided.

#### Screenshots
| Main Menu | Solids Menu |
|:-:|:-:|
| ![First](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/mainmenu.jpeg) | ![Sec](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/solidsmenu.jpeg) |

| Quiz Question | Quiz Result |
|:-:|:-:|
| ![Third](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/quiz.jpeg) | ![Fourth](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/quizresult.jpeg) |

| Info about Solid | Solid in AR view |
|:-:|:-:|
| ![Fifth](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/solidinfo.jpeg) | ![Sixth](https://github.com/SahilChowkekar/Augmented-Reality-for-the-learning-of-3D-geometry/blob/master/images/arcuboid.jpeg) |

## 11. Conclusion
The application Learn Geometry with AR utilizes Augmented Reality to improve the learning experience of 3D Geometry for school students. By providing an interactive and visual representation of 3D shapes, it aims to enhance spatial reasoning and understanding. Further research and assessment of learning effectiveness are recommended for future improvements.

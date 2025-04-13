# Engineering Joint Seat Allocation System

A software system designed to automate and optimize the seat allocation process for engineering college admissions in India, based on the real-world model of JoSAA (Joint Seat Allocation Authority). The system ensures fair and transparent allocation of seats based on candidate ranks, preferences, and institute eligibility.

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [System Features](#system-features)
- [Modules](#modules)
- [Architecture and Flowcharts](#architecture-and-flowcharts)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)

## Introduction

The Engineering Joint Seat Allocation System aims to simplify the complex process of counselling and admission for two sets of institutions (e.g., IITs and NITs), offering multiple branches with limited seats. It takes into account candidate ranks in JEE-Main and JEE-Advanced, and their preferences, to allocate seats in a fair and efficient manner.

## Problem Statement

Develop a software system for the engineering counselling and admission process involving:
- Two types of institutions (e.g., IITs and NITs)
- Multiple branches per institution
- Seat allocation based on JEE Mains/Advanced ranks
- Preference list submitted by candidates
- Constraints such as rank order, seat availability, and eligibility

## System Features

- Secure login system for students and admin
- Branch and college-wise choice filling by students
- Eligibility checks based on rank lists
- Fair and transparent seat allocation algorithm
- College-wise seat allotment report
- Handles multiple rounds until all seats are filled

## Modules

1. Login System
2. Choice Filling
3. Seat Allocation Algorithm
4. Display Allotted Seat
5. College-wise Seat Status Viewer

## Architecture and Flowcharts

The system design includes:
- Data Flow Diagrams (DFD Levels 0, 1, and 2)
- Overall Architecture Diagram
- Flowcharts for each module

Diagrams and flowcharts are available in the `/docs` folder.

## Technologies Used

- Language: Python
- File Handling: CSV for data persistence
- Data Structures: Dictionaries and Lists for efficient access
- IDE: VS Code / Jupyter / IDLE (any preferred)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/seat-allocation-system.git
   cd seat-allocation-system
2. Make sure Python 3 is installed on your system.

3. Place the following CSV files in the working directory:

    student_rank.csv – Contains student ranks (Main/Advanced)
    
    seat_matrix.csv – Initial seat availability for colleges and branches
    
    student_allocation.csv – Will be generated after allocation

4. Run the main Python file:
   python main.py

  

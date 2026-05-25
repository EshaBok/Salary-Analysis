
# Employee Salary Analysis (Java)

## Overview

This project is a Java-based data analysis tool that processes a real-world employee salary dataset from a CSV file. It extracts, organizes, and analyzes employee earnings to uncover salary trends across departments and divisions.

The goal of this project is to practice core Java programming skills while simulating a simplified data engineering workflow.

---

## Features

- Reads and parses a large CSV dataset
- Converts raw data into structured `Employee` objects
- Calculates salary statistics such as:
  - Average base salary
  - Highest and lowest salaries
  - Overtime pay analysis
- Analyzes trends by division and department
- Handles large datasets using Java collections

---

## Dataset

The project uses a Kaggle dataset:

- Employee Salaries Analysis Dataset  
- Columns include:
  - Department
  - Department Name
  - Division
  - Gender
  - Base Salary
  - Overtime Pay
  - Longevity Pay
  - Grade

Source: https://www.kaggle.com/datasets/sahirmaharajj/employee-salaries-analysis

---

## Technologies Used

- Java
- File I/O (BufferedReader, FileReader)
- Object-Oriented Programming (OOP)
- ArrayLists
- Basic data processing

---

## Project Structure
src/
│
├── Main.java # Runs the program and outputs results
├── CSVReader.java # Reads and parses the CSV file
├── Employee.java # Employee data model
│
└── Department_Salaries_File.csv

---

## Future Improvements

- Add filtering by department and division
- Export analysis results to a file
- Compute total compensation (base + overtime + longevity)
- Add interactive user input menu
- Integrate database storage (PostgreSQL)
- Build visual charts for salary trends

---

## What I Learned

- How to read and process CSV files in Java
- How to structure data using classes and objects
- How to perform basic data analysis using Java collections
- How to think in terms of data pipelines (load → transform → analyze)

---

## Author

Built by a student learning Java with the goal of becoming a data engineer / backend software engineer.

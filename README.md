# Task-4
Functions for Reusable Data Tasks

Project Overview

This project focuses on creating reusable Python functions for calculations, data transformation, and basic statistical operations. It demonstrates how functions make code easier to organize, reuse, and maintain.

This project is part of the VEDA Technology – Data Science Track.

Objectives

- Understand how to define and use Python functions.
- Improve code organization and reusability.
- Perform basic statistical calculations using functions.
- Understand function parameters and return values.

Technologies Used

- Python
- Jupyter Notebook

Features

This project includes at least five custom Python functions:

1. Mean Calculation – Calculates the average of a list of numbers.
2. Maximum Value – Finds the largest number in a list.
3. Minimum Value – Finds the smallest number in a list.
4. Percentage Calculation – Calculates the percentage based on obtained and total marks.
5. Data Transformation – Transforms data, such as converting values to uppercase or processing a list of numbers.

Sample Dataset

The project can use either of the following datasets:

- Student Marks Dataset
- Employee Dataset

Example Python Code

def calculate_mean(numbers):
    return sum(numbers) / len(numbers)

def find_maximum(numbers):
    return max(numbers)

def find_minimum(numbers):
    return min(numbers)

def calculate_percentage(obtained, total):
    return (obtained / total) * 100

def square_numbers(numbers):
    return [n * n for n in numbers]

marks = [80, 90, 75, 85, 70]

print("Mean:", calculate_mean(marks))
print("Maximum:", find_maximum(marks))
print("Minimum:", find_minimum(marks))
print("Percentage:", calculate_percentage(80, 100))
print("Squared values:", square_numbers(marks))

Sample Output

Mean: 80.0
Maximum: 90
Minimum: 70
Percentage: 80.0
Squared values: [6400, 8100, 5625, 7225, 4900]

How to Run the Project

1. Install Python or open Jupyter Notebook.
2. Create a new notebook.
3. Copy the Python functions into notebook cells.
4. Run the cells to see the results.
5. Try different values and datasets to test the functions.

Key Learnings

- Defining functions using "def".
- Using parameters and arguments.
- Returning calculated values using "return".
- Performing basic statistical calculations.
- Writing reusable and organized Python code.

Conclusion

This project demonstrates how Python functions can simplify repetitive tasks and make data analysis more efficient. These concepts provide a foundation for further learning in data science and machine learning.

Author

Data Science Track Student
VEDA Technology

# CODTECH-TASK2
Name:Devarakonda Lakshmi Sai Teja
Company:CODTECH IT SOLUTIONS
ID:CT08DS7164
Duration:Aug 17th,2024 - Sep 17th,2024

The provided program is a simple Python script designed to compute and display a letter grade based on the average score from multiple subjects. Here’s a detailed description:

Language and Modules
Programming Language: Python
Modules Used: None (standard Python built-in functions are used)
Description
Purpose: The program calculates the average score from grades entered by the user for a number of subjects and converts this average into a letter grade based on predefined grade boundaries.

Components:

Function get_letter_grade(avg): This function takes a numeric average score as input and returns a letter grade based on the score.
Grade Boundaries:
A for scores 90 and above
B for scores 80 to 89
C for scores 70 to 79
D for scores 60 to 69
F for scores below 60
Main Function main():
Prompts the user to input the number of subjects.
Collects grades for the specified number of subjects.
Computes the average grade.
Determines the letter grade using the get_letter_grade function.
Prints out the average grade and corresponding letter grade.
Functionality:

User Input: The program asks the user how many subjects they have grades for and then prompts for each grade.
Calculation:
The total of the grades is accumulated and then divided by the number of subjects to find the average.
This average is passed to the get_letter_grade function to determine the letter grade.
Output:
The average grade is printed with two decimal precision.
The letter grade corresponding to the average is printed.
Error Handling:

The program assumes that the user inputs valid numerical grades and does not handle potential errors such as non-numeric input or division by zero (if the user inputs 0 subjects).
User Interaction:

The interaction is through the console. The user is prompted to input values, and the results are displayed on the console.
Challenges and Considerations
Input Validation:

The program currently lacks validation for user input. For example, it does not handle cases where the user might input non-numeric values or negative grades. Adding validation could improve robustness.
Edge Cases:

Zero Subjects: If the user inputs 0 for the number of subjects, a division by zero error will occur. Implementing a check to handle this case would be beneficial.
Non-Numeric Inputs: Handling cases where the user might input invalid data (e.g., text instead of numbers) is important for user experience and program stability.
Usability:

The program is straightforward and easy to use but could be enhanced with additional features such as input prompts for invalid entries or clearer instructions.
Feature Enhancements:

Possible enhancements might include more flexible grading scales, user-friendly prompts, and additional error handling to make the program more robust and user-friendly.
Summary
This Python script is a basic example of how to process user input, perform calculations, and provide feedback in a console-based application. It effectively demonstrates the use of functions, arithmetic operations, and conditional statements to achieve its purpose. With some enhancements in input validation and error handling, it could be made more robust and user-friendly.

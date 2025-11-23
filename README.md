# Timed Math Challenge 
___Name___ : Thondavarapu Bharadhwaj

___Reg No.___ : 25BAI10897

___Course___ : CSE1021-Introduction To Problem Solving And Programming

This is a small Python project which provides a simple, interactive console application for users to test and improve their mental math speed and accuracy.

## Overview
__Goal__: Test mental math speed and accuracy using 10 random problems 

Operators used :<br>
 Addition<br>
  Subtraction<br>
  Multiplication

  The user is presented with a fixed number of randomly generated addition, subtraction, and multiplication problems, and the script tracks the total time taken and the final score.

  ## Features
  __Timed Challenge__: Accurately measures the duration taken to complete all questions using _time.perf_counter()_.

__Random Problems__: Generates 10 questions mixing addition (+), subtraction (-), and multiplication (*) problems.

__Input Handling__: Gracefully handles non-numeric input without crashing the program.
        
__Score Tracking__: Calculates and displays the final score.

__Review Option__: Allows the user to review the details (user answer, correct answer, and result) of every question at the end.

### Prerequisites

To run this script, you only need:

Python software

## How to Run

__Save the Code__: Save the provided code into a file named timed_math_challenge.py.

__Open Terminal/Command Prompt__: Navigate to the directory where you saved the file.

__Execute the Script__: Run the script using the Python interpreter

## Function Details

___Parameters___:
num_questions (int, optional): The total number of math problems to present. Defaults to 10.

___Logic___:

* Initializes internal dictionaries (OPERATORS) for easy calculation.

* Loops through the required number of questions, generating random numbers between 1 and 20.

* Prompts the user for input and tracks correct answers.

* Calculates and prints final score and time.

## Conclusion

This simple script is a great way to practice mental arithmetic and track your speed.It is constructed using basic Python concepts like functions, file handling, and modular programming








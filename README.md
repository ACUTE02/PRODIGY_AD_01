# TASK 1- Creating a Basic Calculator
# Overview
As part of my initial assignment during the internship at Prodigy InfoTech I developed a Python program that contains a basic calculator implementation in Python using the Tkinter library for the graphical user interface (GUI). The calculator allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.
## Calculator Algorithm
The calculator algorithm is based on a simple finite state machine that processes user input and performs calculations accordingly. The algorithm can be broken down into the following steps:
User Input: The user enters a number or an operator (+, -, *, /) using the GUI buttons.
Tokenization: The input is tokenized into individual characters, which are then processed by the algorithm.
Expression Evaluation: When the user enters the "=" button, the algorithm evaluates the expression by performing the following steps:
Lexical Analysis: The algorithm breaks down the input expression into individual tokens, such as numbers and operators.
Syntax Analysis: The algorithm checks the syntax of the input expression to ensure that it is valid.
Semantic Analysis: The algorithm performs the actual calculation by evaluating the expression.
Result Display: The result of the calculation is displayed on the GUI.


## Calculator Components
The calculator consists of the following components:
- **GUI:** The graphical user interface is implemented using Tkinter and provides a simple and intuitive way for users to interact with the calculator.
- **Calculator Logic:** The calculator logic is implemented in the Calculator class and is responsible for processing user input and performing calculations.
- **Button Handlers:** The button handlers are responsible for processing user input and updating the GUI accordingly.


## Features

The calculator has the following features:

- **Basic Arithmetic Operations:** The calculator supports basic arithmetic operations such as addition, subtraction, multiplication, and division.

- **GUI**: The calculator has a simple and intuitive GUI that allows users to interact with the calculator.

- **Error Handling:** The calculator has basic error handling capabilities, such as displaying an error message when the user enters an invalid input.

## Requirements

- Python 3.x
- Tkinter

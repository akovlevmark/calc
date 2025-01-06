Simple Calculator in C++

Overview

This is a simple console-based calculator written in C++. It allows the user to perform basic arithmetic operations such as:

Addition

Subtraction

Multiplication

Division

The calculator runs in a loop and will terminate when the user chooses the "Exit" option.

Features

User-friendly text-based menu.

Handles division by zero gracefully with an error message.

Infinite loop for repeated usage until explicitly exited by the user.

How to Use

Prerequisites

A C++ compiler such as GCC (g++) or MSVC.

Steps to Compile and Run

Clone this repository or download the calculator.cpp file.

Open a terminal or command prompt.

Navigate to the directory where the file is located.

Compile the code using the following command:

g++ -o calculator calculator.cpp

Run the compiled program:

./calculator

Example Usage

Run the program.

Select an operation by entering the corresponding number (1 for addition, 2 for subtraction, etc.).

Input two numbers when prompted.

View the result.

Repeat or choose option 5 to exit.

Example Output

Simple Calculator
====================
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exit
====================
Enter your choice: 1
Enter the first number: 5
Enter the second number: 10
Result: 15

Error Handling

If the user enters an invalid option, the program will prompt them to try again.

Division by zero is prevented with a clear error message: "Error: Division by zero is not allowed."

License

This project is licensed under the MIT License. You are free to use, modify, and distribute this code.

Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request with any improvements or additional features.

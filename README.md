# Week1Q5
The Calculator provides basic arithmetic operations: addition, subtraction, multiplication, and division.
The main function interacts with the user to perform these operations based on user input. The program prompts the user to enter two numbers and the desired arithmetic operation. Based on the user's input, calls the corresponding function (add, subtract, multiply, divide) to perform the calculation. If an invalid operation is entered, displays an error message.

Header files included are:
#include <iostream>: Includes the standard input-output stream library.
#include "calculator.h": Includes the header file for calculator functions.

Variables used:
double num1, num2: to store the numbers input by the user.
char operation: to store the arithmetic operation input by the user.
double result: to store the result of the calculation.

Functions included in "calculator.h":
double add(double a, double b): Returns the sum of a and b.
double subtract(double a, double b): Returns the difference of a and b.
double multiply(double a, double b): Returns the product of a and b.
double divide(double a, double b): Returns the quotient of a divided by b. Throws an error if b is zero to prevent division by zero.

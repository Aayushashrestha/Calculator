# Simple Calculator

This is a simple calculator program written in Java that performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

Supports four basic arithmetic operations: +, -, *, and /.

Takes user input for operator selection and two numbers.

Handles division by zero gracefully.

## Prerequisites

Java Development Kit (JDK) installed (JDK 8 or later).

A Java-compatible IDE (such as IntelliJ IDEA, Eclipse, or VS Code) or a command-line terminal.

# Installation & Usage

## Clone the Repository
 git clone https://github.com/yourusername/SimpleCalculator.git
 cd SimpleCalculator

 ## Compile the code 
 javac -d bin src/calculator/Main.java src/calculator/Program.java

 ## Run the program
java -cp bin calculator.Program

 ## Example Usage
 Enter the operator (+, -, *, /):
+
Enter the two numbers one by one:
5
3
5.00 + 3.00 = 8.00

## Project Structure
SimpleCalculator/
│── src/
│   ├── calculator/
│   │   ├── Main.java
│   │   ├── Program.java
│── bin/ (compiled files)
│── README.md

RUST COMPILER
Project Overview
Welcome to the Rust Compiler project! This project is a simple compiler designed to interpret a Rust-like programming language. Built from scratch, it utilizes fundamental concepts from compiler design, including:

Lexical Analysis:
The one.py file contains a lexer that tokenizes the input source code into meaningful symbols, such as keywords, identifiers, operators, and literals.
Parsing:

The two.py file implements a parser that takes the tokens produced by the lexer and constructs an Abstract Syntax Tree (AST). This tree represents the hierarchical structure of the source code, allowing for easier manipulation and analysis.

Intermediate Representation Generation:
The ir_gen.py file generates three-address Code (TAC) from the AST. This intermediate representation simplifies the code, making it easier to optimize and translate it into machine code.

Interpretation:
The three.py file interprets the generated TAC, executing the instructions and producing output based on the input source code.

Features
The project allows users to write simple programs in a Rust-like syntax, which can include:
Variable declarations
Assignments
Control flow statements (if, while, for)
Print statements

The compiler processes the input code, generates intermediate code, and executes it, providing output directly to the console.

Author Information
Name: PRINCE ARORA
Roll Number: 22000408

Instructions to Run the Code
To run this project, follow these steps:

Open Terminal:
Navigate to the project folder where all the files are located.
Run the Compiler:

Type the following command in the terminal:
python three.py

Input Your Code:
After running the command, you will be prompted to enter your Rust-like code. You can type or paste your code directly into the terminal.

End Input:
To terminate the input, use:
Ctrl + D (on Unix/Linux/Mac)
Ctrl + Z (on Windows)

View Output:
The compiler will process your input code, generate the intermediate representation, and execute it. The output will be displayed in the terminal.

Termination of the Code
To terminate the execution of the program at any time, you can simply close the terminal window or use the keyboard shortcuts mentioned above to end the input. 

If the program is running and you wish to stop it, you can use:
Ctrl + C to interrupt the execution.

File to Run for Output
The main file to run for output is three.py. This file serves as the entry point for the compiler, handling user input, invoking the parser, generating intermediate code, and executing the instructions.

Thank you for exploring the Rust Compiler project! Happy coding!
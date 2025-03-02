# JavaCC Compiler Project

This project is a simple compiler built using JavaCC (Java Compiler Compiler). It includes a grammar file (`JavaGrammar.jj`) and a test file (`Simple.java`) to demonstrate the functionality of the compiler.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Downloading and Installing JavaCC](#downloading-and-installing-javacc)
4. [Setup and Installation](#setup-and-installation)
5. [Running the Project](#running-the-project)
6. [Testing the Compiler](#testing-the-compiler)

---

## Project Overview

The project consists of the following files:
- **` JavaGrammar.jj`**: The JavaCC grammar file that defines the syntax and rules for the compiler.

This project involves creating a compiler module using JavaCC to implement lexical analysis and parser grammar for the 
Java programming language. The module will do the following: 
1. Perform lexical analysis by breaking the source code into tokens. 
2. Parse the tokenized input to validate the syntax according to Java grammar. 
3. Take the Java source code from the text file as input. 
4. Output either syntax validation results or error reports for invalid code.
 
- **`Simple.java`**: A simple Java file used to test the compiler.

---

## Project Timeline

- **19/12/2024**: Project created. Initial commit includes the following files:
  - `JavaGrammar.jj`: The main grammar file for the compiler.
  - `Simple.java`: A test file to validate the compiler's functionality.

---

## Prerequisites

Before running the project, ensure you have the following installed:
- **Java Development Kit (JDK)**: Required to compile and run Java programs.
- **JavaCC**: A tool for generating parsers and lexical analyzers in Java.

---

## Downloading and Installing JavaCC

To download and install JavaCC, follow these steps:

1. **Download JavaCC**:
   - Visit the official JavaCC website to download the latest version: [JavaCC Download](https://javacc.github.io/javacc/).

2. **Install JavaCC**:
   - Once you have downloaded the files, navigate to the download directory and unzip the source file. This will create a JavaCC installation directory.
   - Move the binary file `javacc-7.0.14.jar` (or the version you downloaded) from the download directory to a new `target/` directory under the installation directory. Rename it to `javacc.jar`.
   - Add the `scripts/` directory in the JavaCC installation directory to your `PATH`. The JavaCC, JJTree, and JJDoc invocation scripts/executables reside in this directory.

---

## Setup and Installation

1. **Clone or Download the Project**:
   - Clone this repository or download the project files (`JavaGrammar.jj` and `Simple.java`) to your local machine.

2. **Navigate to the Project Directory**:
   - Open a terminal or command prompt and navigate to the folder where the project files are located.

---

## Running the Project

Follow these steps to run the project:

1. **Generate the Parser**:
   - Run the following command to generate the parser using JavaCC:
     ```bash
     javacc JavaGrammar.jj
     ```

2. **Compile the Generated Java Files**:
   - Compile all the generated Java files using the following command:
     ```bash
     javac *.java
     ```

3. **Test the Compiler**:
   - Test the compiler by running the following command:
     ```bash
     java JavaGrammar Simple.java
     ```
When you run the command for the first time, this message will appear: "Syntax validation successful!" try removing a ; or data type of a variable and see the result in your terminal by yourself.

---

## Testing the Compiler

The `Simple.java` file is provided as a test case for the compiler. You can modify this file or create new Java files to test the functionality of the compiler.

---

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure your code follows the project's coding standards.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments

- **JavaCC**: Thanks to the JavaCC team for providing a powerful tool for building compilers.
- **Developers**: Special thanks to all contributors who helped make this project possible.

---

## Contact

For any questions or feedback, please contact:
- **Your Name**: [abdelrahmanhelwaitsme@gmail.com]
- **GitHub**: [https://github.com/MrHelwa]

---


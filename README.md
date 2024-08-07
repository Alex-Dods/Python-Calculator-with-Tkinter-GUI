# Python-Calculator-with-Tkinter-GUI
A Calculator built with Python and Tkinter GUI interface
# Simple Calculator

This is a simple calculator application I built using Python and Tkinter.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division
- Percentage calculation
- Clear (C) button to reset the input
- Parentheses for complex expressions
- Responsive and user-friendly interface

## Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/Alex-Dods/Python-Calculator-with-Tkinter-GUI/tree/main
    ```
    Replace `yourusername` with your GitHub username.

2. **Navigate to the Project Directory**:
    ```sh
    cd simple-calculator
    ```

3. **Ensure you have Python Installed**:
    - You can download Python from [here](https://www.python.org/downloads/).

4. **Install Tkinter** (if not already installed):
    - Tkinter is included with Python installations on Windows and macOS. On some Linux distributions, you might need to install it manually:
    ```sh
    sudo apt-get install python3-tk
    ```

## Usage

1. **Open the Project in Visual Studio Code**:
    - Navigate to the project directory and open it with VS Code:
    ```sh
    code .
    ```

2. **Run the Script**:
    - Open a terminal in VS Code (`Ctrl+``) and run the following command:
    ```sh
    python calculator.py
    ```

3. **Interacting with the Calculator**:
    - Use the buttons on the calculator interface to perform arithmetic operations.
    - The `C` button clears the input.
    - The `=` button evaluates the expression.

## Code Overview

- `calculator.py`: The main Python script containing the Tkinter GUI and the calculator logic.

### Main Components

1. **Calculator Class**:
    - `__init__(self, master)`: Initializes the calculator interface.
    - `show(self, value)`: Updates the input field with the button pressed.
    - `clear(self)`: Clears the input field.
    - `solve(self)`: Evaluates the expression and displays the result.

## Contributing

Feel free to fork this repository and submit pull requests. 


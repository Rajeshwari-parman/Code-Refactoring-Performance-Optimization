# Code-Refactoring-Performance-Optimization

🧮 Overview

The Matrix Calculator is a Python-based desktop application developed using the Tkinter library. It offers a clean, interactive graphical interface to perform a wide range of matrix operations efficiently and accurately. Designed with simplicity and usability in mind, this application is ideal for students, teachers, and professionals who frequently work with matrices in subjects like mathematics, physics, computer science, or engineering.

Manual matrix calculations can often be tedious and error-prone, especially as the matrix size increases or when performing advanced operations like matrix inversion or determinant calculation. This tool significantly reduces the effort involved by automating those tasks through a user-friendly interface. With clearly labeled buttons, pop-up input dialogs, and real-time result displays, users can focus on understanding the operations rather than worrying about computation accuracy.

The application supports several key features: addition of matrices, scalar multiplication, matrix multiplication, transposition, determinant and inverse calculations—each designed to handle a variety of input sizes and edge cases. Users can also switch between light and dark mode themes, allowing for a comfortable experience during extended use. A splash screen welcomes users upon launch, adding a touch of professionalism and polish to the user journey.

A standout feature of this calculator is its operation history log, which records each operation performed during the session. This log can be exported as a .txt or .csv file, providing a way to review or submit work. Additionally, users can clear the history at any time if needed.

The graphical interface is powered by gui.py, while all core matrix operations are modularized in matrix.py, making the codebase well-organized and easy to maintain or extend. The project structure also includes main.py as the entry point and a detailed report on code changes and performance impact.

This application not only simplifies matrix math but also serves as a great example of how Python and Tkinter can be combined to create useful desktop tools. Whether you're looking to explore GUI development or need a practical matrix utility, Matrix Calculator provides a robust solution that is easy to install, run, and use.

✨ Features

Matrix Addition: Add two matrices of the same dimensions element-wise.

Scalar Multiplication: Multiply all elements of a matrix by a constant.

Matrix Multiplication: Multiply two compatible matrices using standard matrix rules.

Transpose: Transpose a matrix across its diagonal.

Determinant Calculation: Compute the determinant of a square matrix.

Inverse Calculation: Find the inverse of a square matrix (if it exists).

Dark Mode: Toggle between light and dark themes for better visibility.

Operation History: Keep track of all operations during a session.

Export History: Save session history as .txt or .csv.

Clear History: Erase all operation history with a click.

Splash Screen: Brief animated welcome screen on startup.

🖥️ User Interface

The GUI is clean and user-friendly. Users can input matrix dimensions and values via dialog boxes. Results are displayed in responsive pop-up windows. The theme auto-adjusts based on user preference (light or dark mode).

🗂️ Project Structure

matrix_calculator/

├── matrix.py      # Core matrix operations

├── main.py        # Main launcher script

├── gui.py         # GUI built with Tkinter

├── README.md      # Project documentation

└── report.pdf     # Performance and refactoring report

⚙️ Requirements

Python 3.x (Recommended: 3.8 or higher)

Tkinter (Usually bundled with Python)

matrix.py – Custom module for matrix logic

To install Tkinter (if not already available):

    pip install tk

▶️ How to Run

Step 1: Clone the Repository

    git clone https://github.com/shashanksaranr/CODE-REFACTORING-AND-PERFORMANCE-OPTIMIZATION.git

    cd CODE-REFACTORING-AND-PERFORMANCE-OPTIMIZATION

Step 2: Launch the App

    python gui.py
    
The application will open with a splash screen, followed by the main calculator interface where you can begin matrix operations.

## Output



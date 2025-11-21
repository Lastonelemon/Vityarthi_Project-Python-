# Vityarthi_Project-Python-
Intro to problem Solving with python(Vityarthi)

Technical Documentation: Hospital Management System (HMS)
This documentation outlines the setup and structure for a basic Python program designed to simulate
core operations of a Hospital Management System. The project uses only fundamental Python
concepts (functions, lists, loops, and conditionals) as data structures and logic controls.
1. Prerequisites and Dependencies
The HMS script relies solely on the core Python installation.
Software Requirements: Python: Version 3.x or higher. Operating System: Any OS that supports Python
(Windows, macOS, Linux).
Dependencies: No external libraries are required. The program is self-contained using only built-in
Python features.
2. Program Structure and Core Logic
The program manages patient records in memory and is driven by a simple menu loop.
Section A. Data Structures (Lists) The patients List is a global list ( patients = [] ) used to store all
patient records. Each patient is represented as a list itself, adhering to the format: [ID, Name,
Disease] . The current_id Counter is a global integer variable ( current_id = 1 ) that tracks the
next available sequential Patient ID, ensuring unique IDs.
Section B. Core Functions (The Logic)
Function 1. register() : Logic: Takes user input for Name and Disease. Appends the new record [ID,
Name, Disease] to the global patients list. Increments the current_id counter. Concepts Used:
Global variable access, list append() .
Function 2. view() : Logic: Checks if the patients list is empty (Conditional). If not empty, it uses a
for loop to iterate through the list and prints each patient's details by concatenating the data fields
( str(p[0]) + "\t" + p[1] + ... ). Concepts Used: Conditionals ( if/else ), for loop, list
indexing, string concatenation.
Function 3. discharge() : Logic: Prompts for a Patient ID. Uses a for loop to search for the ID within
the patients list (Conditional check: if patients[i][0] == pid ). If found, calculates a simple bill
based on user-inputted days stayed (basic arithmetic) and removes the record using
patients.pop(i) . Concepts Used: Conditionals ( if/else ), for loop, list indexing, list pop() .
3. Installation and Setup Instructions
The setup requires no installation steps other than running the script.
Section A. Environment Setup Verify Python: Ensure Python 3.x is available on your system.
Section B. Script Installation Download/Create the Script: Save the code into a file named
hospital_management.py .
4. Usage and Execution
Section A. Running from the Command Line To run the program, execute the
hospital_management.py script:
python hospital_management.py
The program will immediately present the main menu in the console:
1. Register 2. View 3. Discharge 4. Exit
Option:
Section B. Menu Options
1. Register: Creates a new patient record and assigns an ID.
2. View: Displays all current patient records in a list format.
3. Discharge: Processes a bill for a patient ID and removes them from the system.
4. Exit: Terminates the application.


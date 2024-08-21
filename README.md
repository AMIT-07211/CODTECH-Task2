**Name:** Amit Kumar Giri
**Company:** CODTECH IT SOLUTIONS
**ID:**CT08DS5843
**Domain:** Python Programming
**Duration:** August to September 2024
**Mentor:** NEELA SANTHOSH KUMAR

Certainly! Here’s an overview of the Student Grade Tracker program:

### **Overview**

The Student Grade Tracker program is a console-based application written in Python to manage and track grades for a predefined set of students. The key features of the program include:

#### **1. Classes and Structure:**

- **`Student` Class:**
  - **Purpose:** Represents an individual student and their grades.
  - **Attributes:**
    - `name`: Stores the name of the student.
    - `grades`: A list to store the grades of the student.
  - **Methods:**
    - `add_grade(grade)`: Adds a grade to the student's list of grades.
    - `average_grade()`: Calculates the average of the student's grades.
    - `__str__()`: Returns a string representation of the student, including their name and average grade.

- **`GradeTracker` Class:**
  - **Purpose:** Manages a collection of `Student` objects and provides functionality to interact with them.
  - **Attributes:**
    - `students`: A dictionary mapping student names to `Student` objects.
  - **Methods:**
    - `add_grade(name, grade)`: Adds a grade for a specific student if they exist.
    - `view_student(name)`: Displays the information of a specific student if they exist.
    - `view_all_students()`: Displays the information of all students.

#### **2. Main Program Flow:**

- **Initialization:**
  - The program starts by creating a `GradeTracker` instance with a predefined list of student names: `['Amit', 'Rohan', 'Sohan', 'Anup', 'Suprit']`.

- **User Interface:**
  - **Menu Options:**
    - **Add Grade:** Allows the user to input a grade for a specific student.
    - **View Student:** Displays the average grade for a specific student.
    - **View All Students:** Shows the average grades for all students.
    - **Exit:** Terminates the program.
  - The user interacts with the program through a text-based menu, entering choices to perform different actions.

- **Error Handling:**
  - The program checks if the student exists before adding grades or viewing information. It provides error messages if the student is not found or if the input is invalid.

#### **3. Example Interaction:**

- **Adding Grades:** Users can add grades for students like Amit and Rohan. Grades are appended to each student’s list.
- **Viewing Information:** Users can view individual student records or see the average grades for all students.
- **Exiting the Program:** Users can exit the program when they are done.

#### **Key Features:**

- **Predefined Students:** The program comes with a predefined list of students, simplifying initial setup.
- **Grade Management:** Allows adding multiple grades and calculates averages for each student.
- **Interactive Menu:** Provides a user-friendly way to interact with the system through a simple text-based menu.

This program is a basic implementation that can be extended with additional features like editing grades, removing students, or saving data to a file. It’s designed to be straightforward and easy to use for managing student grades in a console environment.

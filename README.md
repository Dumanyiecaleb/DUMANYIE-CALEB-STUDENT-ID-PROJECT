# DUMANYIE-CALEB-STUDENT-ID-PROJECT
A CODE THAT STORES STUDENTS NAME,MATRIC NUMBER ,LEVEL AND OTHER DETAILS

# Student ID Card Management System

NAME: DUMANYIE CALEB BARISUA
MATRIC NO : 24/15078
DEPARTMENT : COMPUTER - SCIENCE


## Project Overview

The **Student ID Card Management System** is a simple console-based Python application designed to **register students, generate student ID cards, and verify student IDs**. This project demonstrates a full implementation of a real-life system while following proper **Software Development Life Cycle (SDLC)** practices.

---

## SDLC of the Project

### 1. Requirement Analysis

* Identify the need for a system to manage student ID cards.
* Key requirements:

  * Register students with basic details (Name, Matric Number, Department, Level).
  * Generate student ID cards for all registered students.
  * Verify a student’s ID using their Matric Number.
  * Simple and terminal-based system to run without external libraries.

### 2. System Design

* **Modules / Components:**

  1. `StudentRegistrationModule` – handles student registration.
  2. `IDCardGenerationModule` – generates and displays ID cards.
  3. `IDVerificationModule` – verifies a student ID.
  4. `MainMenu` – allows user navigation between modules.
* **Data Storage:** In-memory list `students` (no external database required).
* **Design Nomenclature:** Module names in the design match the function names in the code.

### 3. Implementation

* Implemented as a single Python file (`student_id_system.py`).
* Uses **Python’s built-in `input()` function** for user interaction.
* Stores students in a **list of dictionaries** in memory.
* Functions for each module correspond directly to the design components.

### 4. Testing

* Manual testing performed by running the program:

  * Registering multiple students.
  * Viewing generated ID cards.
  * Verifying valid and invalid student IDs.
* Ensured all menu options work as intended.

### 5. Deployment

* The program is terminal-based and can run on any system with **Python 3 installed**.
* No external dependencies required.

### 6. Maintenance

* Easy to extend:

  * Could add file-based persistence or a database.
  * Could add GUI interface in future versions.

---

## Project Modules

| Module Name                 | Functionality                                                         |
| --------------------------- | --------------------------------------------------------------------- |
| `StudentRegistrationModule` | Registers new students by taking Name, Matric, Department, and Level. |
| `IDCardGenerationModule`    | Displays a formatted student ID card for each registered student.     |
| `IDVerificationModule`      | Checks if a student exists in the system using their Matric Number.   |
| `MainMenu`                  | Provides a terminal-based menu to access all modules.                 |

---

## How to Run the Project

1. Ensure you have **Python 3** installed.
2. Save the project file as:

```
student_id_system.py
```

3. Open terminal / command prompt and navigate to the folder containing the file.
4. Run the program:

```bash
python student_id_system.py
```

5. Use the menu to:

* Register students (`1`)
* Generate ID cards (`2`)
* Verify student IDs (`3`)
* Exit the program (`4`)

---

## Example Run

```
=== Student ID Card Management ===
1. Register Student
2. Generate ID Cards
3. Verify Student ID
4. Exit
Enter your choice (1-4): 1

--- Register Student ---
Enter Full Name: DUMANYIE CALEB BARISUA
Enter Matric Number: 24/15078
Enter Department: Computer Science
Enter Level: 200
Student Registered Successfully!
```

---

## GitHub Instructions

1. Initialize Git in your project folder:

```bash
git init
git add student_id_system.py
git commit -m "Initial commit - Student ID Card Management System"
```

2. Link your GitHub repository:

```bash
git remote add origin https://github.com/Dumanyiecaleb/DUMANYIE-CALEB-STUDENT-ID-PROJECT
git branch -M main
git push -u origin main
```

---

## Notes

* This is a **terminal-based project**, no external libraries required.
* Module names in the design and implementation are **consistent** for easy understanding.
* Can be extended to support **file storage, databases, or GUI interfaces**.

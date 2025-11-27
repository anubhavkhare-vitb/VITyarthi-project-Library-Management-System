## Project Statement
Library Management System (Build Your Own Project)

1. Problem Definition

For my project, I decided to create a simple Library Management System because I noticed that small student libraries and classroom book collections often have to manage everything manually. Even in clubs or small groups, maintaining books, tracking who borrowed what, and knowing what is available becomes confusing without a proper system.
I wanted to build something lightweight, easy to run, and beginner-friendly that doesn't require databases or installation. So, I created a menu-based Python application that handles books, borrowers, issuing, and returns.

---

2. Scope of the Project

The scope of my system is intentionally kept small and focused so that it remains simple and clean to use.

In Scope:

* Adding books with basic details
* Managing borrowers
* Issuing and returning books
* Showing reports like availability, active issues, and borrower history
* Simple command-line interface
* Modular Python structure

Out of Scope (Future Enhancements):

* Full GUI interface
* Login/authentication
* Integration with database systems like SQLite
* Cloud backup or multi-user system
* Fine or penalty calculations

I designed the system in a way that these additions can be made later without rewriting the whole program.

---

3. Project Objectives

The main objectives I had while planning and building this project were:

* To understand and apply modular programming in Python
* To create a practically useful program with a clear workflow
* To learn to structure files and functions properly
* To use Git and maintain a clear commit history
* To prepare documentation clearly and professionally

This project was a good opportunity to convert my Python basics into a proper application.

---

4. Tools and Technologies Used

I wrote this project in Python 3 and used a basic code editor (VS Code).
Git and GitHub were used to track progress and organize the project versions.
For documentation, I used Markdown for the README and statement, and I prepared a detailed PDF report according to the BYOP guidelines.
I kept the project simple so no additional frameworks or libraries were required.

---

5. Target Users

The system is mainly useful for small-scale or beginner-level library setups, such as:

* Students maintaining personal or group book collections
* Teachers handling classroom research books
* Clubs and student communities
* Anyone learning how a library system works technically

The interface is simple, so even non-technical users can understand the options easily.

---

6. High-Level Features

The main features I implemented are:

Book Management
Users can add books, search for them, and view total vs available copies.

Borrower Management
Borrower profiles with auto-generated IDs.

Issue/Return Flow
Books can only be issued if copies are available, and on return, availability is updated.

Reports
Shows available books, books currently issued, and borrower-specific issue history.

I designed these features to cover the core functions of a basic library system.

---

7. Deliverables

The project submission includes:

* The complete Python source code
* README.md explaining how to run the project
* This statement.md file
* A fully detailed project report in PDF format following the official guidelines
* The GitHub repository link showing all project commits and iterations

These collectively represent the full project package.

---

8. System Overview

The system is divided into modules to make it cleaner:

model.py stores the data structures.
operations.py contains book, borrower, issue, and return logic.
cli.py handles the main menu and user interaction.
LMS.py runs the program.

This modular separation helped me maintain clarity and also makes future improvements easier.

---

9. Conclusion

Overall, this project allowed me to build a fully functional Library Management System using Python while practicing good coding habits like readability, modularity, and version control.
It also helped me understand how to convert a simple idea into a structured application with proper documentation.

I plan to extend this system in the future with data persistence, a graphical interface, and more advanced features as I keep learning.



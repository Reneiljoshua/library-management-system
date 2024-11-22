# Library Management System by RENEIL

This is a Library Management System built using Python, Tkinter for the graphical user interface (GUI), and SQLite as the database backend. It allows users to manage library books, issue books to students and employees, and manage user accounts.

## Features

- **User Authentication**: Allows employees and students to log in using their unique credentials.
- **Book Management**: Employees can add, update, or delete books from the system's catalog.
- **Book Issuing**: Employees can issue books to students and employees.
- **Return System**: Students and employees can return books.
- **Overdue Management**: Tracks overdue books and notifies users to return them on time.
- **SQLite Database**: Stores all the details of employees, students, books, and issued books in a local SQLite database.

## Technology Stack

- **Python**: The primary programming language.
- **Tkinter**: Used for building the graphical user interface (GUI).
- **SQLite**: A lightweight database for storing the system’s data locally.

## Requirements

- Python 3.x
- Tkinter (Usually comes pre-installed with Python)
- SQLite (Pre-installed with Python)

## Setup and Installation

1. Clone or download the repository to your local machine.
2. Ensure Python 3.x is installed on your system.
3. Run the script by executing the following command:

   ```bash
   python library_management_system.py
   Database Structure
## The following tables are created in the SQLite database:
- **empdetail:** Stores employee details (empid, name, password).
- **studetail:** Stores student details (rollno, name, password).
- **books:** Stores book details (bid, title, subject, author, status).
- **issuedetail:** Tracks issued books (bid, issueto, issueby).
## Functionality
- **Login Screen:** Allows employees and students to log in by entering their ID and password.
- **Employee Dashboard:** Empowers employees to manage books (add, update, delete) and issue books to users.
- **Student Dashboard:** Allows students to search for books and see their issued books.
- **Logout:** Log out and return to the main screen.
## Screenshots
.

## Future Enhancements
- Add book search functionality for both students and employees.
- Implement password encryption for better security.
- Improve error handling and form validations.
- Implement a due date reminder system to notify students about overdue books.
  
### How to use:

1. Replace `"library_management_system.py"` with the actual filename of your Python script.
2. Add screenshots or additional features to the README if necessary.
3. Update the contact information to include your own details if you'd like.



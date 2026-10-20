Student Management System

Project Overview

The Student Management System is a web-based application developed using HTML, CSS, and JavaScript. It provides a simple interface for registering users and managing student information.

Features

User Account Features

- User registration with name, email, and password
- Login using registered account details
- Password confirmation during registration
- Validation for already registered email addresses
- Session-based dashboard access protection
- Logout functionality

Student Management Features

- Add student records
- Display student records in a table
- Edit existing student records
- Delete student records
- Prevent duplicate roll numbers
- Prevent duplicate email addresses
- Save student records using browser Local Storage
- Retain student records after refreshing the page

Technologies Used

- HTML — webpage structure
- CSS — webpage styling
- JavaScript — application functionality and validation
- Local Storage — saves user accounts and student records in the browser
- Session Storage — maintains the current login session
- Git — version control
- GitHub — source code hosting

Project Files

- "index.html" — student dashboard and student record management
- "login.html" — user login page
- "register.html" — user registration page
- "README.md" — project documentation

How to Run

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Install the Live Server extension if it is not already installed.
4. Right-click "index.html" and select Open with Live Server.
5. Register a user account.
6. Log in using the registered email and password.
7. Add, edit, view, and delete student records.

Project Status

The basic web application has been implemented and tested. It includes user registration, login, logout, dashboard session protection, student record management, duplicate validation, and browser-based data persistence.

Limitations

- User accounts and student records are stored in the browser.
- Authentication is implemented on the client side for demonstration purposes.
- Passwords are not securely protected because this version does not use a backend authentication system.
- Data is not shared between different browsers or devices.

Future Improvements

- Implement a backend using Node.js.
- Add a database for storing users and student records.
- Implement secure server-side authentication.
- Improve the user interface and add more student information fields.

Author

Student Project — Web Application Development (WAD)
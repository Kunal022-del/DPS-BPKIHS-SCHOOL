# School App Management System

This project is a **School Application Management System** built with Python and Tkinter. It provides functionalities for student login, payment methods, and account management.
"Student viewing an app inteface and code in python"

---

## Features

### 1. **Login System**
- User authentication with `Student ID`, `Password`, and `Class`.
- Access control based on valid credentials.

### 2. **Account Section**
- Displays student details including:
  - Name
  - Class
  - Section
  - Total due amount (fetched from the database).
- Allows payment for dues via various methods.

### 3. **Payment Methods**
- Supports popular payment options like:
  - Esewa
  - Khalti
  - Mobile Banking

---

## Database Configuration
- **Host**: `localhost`
- **User**: `root`
- **Password**: Your database password
- **Database Name**: `school_app`

Ensure the database is set up with the required tables and fields. The application uses the `jayesh` table to fetch the `due_bill` amount for the student.

---

## Setup Instructions
1. **Install Required Packages**:
   - `pymysql`
   - `Pillow`
   - `tkcalendar`
   - Use the command:
     ```bash
     pip install pymysql pillow tkcalendar
     ```

2. **Database Setup**:
   - Create a MySQL database named `school_app`.
   - Create a table `jayesh` with a column `due_bill`.
   - Populate the `due_bill` field with appropriate data.

3. **Run the Application**:
   - Save the Python file.
   - Execute the script:
     ```bash
     python your_script_name.py
     ```

---

## Notes
- Customize the database credentials to match your local setup.
- Ensure MySQL is installed and running on your system.
- The GUI is optimized for a resolution of 1280x720.

---

Enjoy managing your school data effortlessly!


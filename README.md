### School Application Management System

This project is a **School Application Management System** built with Python and Tkinter. It provides a comprehensive platform for students to access various features such as account details, assignments, report cards, reading materials, and feedback, all within an interactive user-friendly interface.

---

## Features

### 1. **Login System**
- Secure user authentication using:
  - `Student ID`
  - `Password`
  - `Class`
- Grants access only to users with valid credentials.

### 2. **Account Section**
- Displays student-specific details, including:
  - Name
  - Class
  - Section
  - Total due amount (retrieved from the database).
- Supports payment of dues through multiple payment methods.

### 3. **Payment Options**
- Integrated with popular payment gateways:
  - **Esewa**
  - **Khalti**
  - **Mobile Banking**

### 4. **Settings**
- Options include:
  - **Log out**
  - **Calendar Integration**
  - **Switch between Light/Dark Mode**

### 5. **Assignments and Report Card**
- View and manage assignments.
- Access report cards for academic progress.

### 6. **Reading Materials**
- Access curated reading materials for additional learning.

### 7. **Feedback System**
- Submit feedback to improve the application and services.

---

## Database Configuration

- **Host**: `localhost`
- **User**: `root`
- **Password**: (Your database password)
- **Database Name**: `school_app`

The application uses the `jayesh` table to fetch the `due_bill` field for displaying outstanding payment amounts.

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

- Update the database credentials in the script to match your local setup.
- The application’s GUI is optimized for a screen resolution of 1280x720.
- Ensure all dependencies are installed before running the application.

---


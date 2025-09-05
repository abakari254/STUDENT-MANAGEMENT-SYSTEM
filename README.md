#Student Management System

A Simple Python-based application designed to simplify how educational institutions manage student records.it is a capstone project for the RITA Africa Python fundamentals course. It provides user authentication, student record managemenT(CRUD), and reporting features and file based data persistence.

🚀 Features

🔐 User Authentication – secure login for system access

📚 CRUD Operations – add, update, delete, and view student records

🕒 Activity Logging – tracks user actions with timestamps

📊 Reporting Module – generates insights for better decision-making


🛠 Tech Stack

Language: Python 3.x

Modules Used: os, getpass(for hidden password entry), datetime(for logging timestamps)

Storage: Text files (users.txt, students.txt, activity_log.txt)

📂 Project Structure
├── users.txt          # Stores user credentials  
├── students.txt       # Stores student records  
├── activity_log.txt   # Stores activity logs with timestamps  
├── student_mgmt.py    # Main application file  
⚙️ How to Run the Project

Clone this repository:

git clone https://github.com/abakari254/student-management-system.git
cd student-management-system


Run the Python script:

python student_mgmt.py

📖 Example Usage

Login: Enter username & password to access system.

Manage Records: Add, update, or delete student details.

View Logs: Review recorded user actions for accountability.
log out:when done activity will be logged off.

📌 Future Improvements

Transition to a database (SQLite/MySQL)

GUI interface for better usability

Role-based access (Admin/Teacher)

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

⚙️ How to Run the Project

Clone this repository:

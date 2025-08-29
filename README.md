Student Management System
A simple console-based Student Management System built in Java that allows you to manage student records with persistent data storage.
Features

➕ Add new students with ID, name, age, and course
👀 View all registered students
🗑️ Delete students by ID
💾 Automatic data persistence (saves to file)
🔄 Data restoration (loads previous data on startup)

How to Run

Compile the program:
bash

javac StudentManagementApp.java

Run the program:
bash

java StudentManagementApp


Data Storage
The application automatically saves student data to students.txt file in CSV format. Data is:

💾 Auto-saved when you add or delete students
🔄 Auto-loaded when you start the program
📝 Persistent between program runs

Sample Usage
===== Student Management System =====
1. Add Student
2. View Students
3. Delete Student
4. Exit
Enter your choice: 1

Enter ID: 101
Enter Name: John Doe
Enter Age: 20
Enter Course: Computer Science
✅ Student added successfully!
Technical Details

Language: Java
Storage: File-based persistence (CSV format)
Data Structure: ArrayList for in-memory storage
File: students.txt for permanent storage
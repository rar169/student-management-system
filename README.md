# Student Management System

A simple **Java console app** to manage student records with file-based storage.

## Features
- ➕ Add students (ID, Name, Age, Course)  
- 👀 View all students  
- 🗑️ Delete students by ID  
- 💾 Data saved to `students.txt` (CSV)  
- 🔄 Data loaded on startup  

## Run
bash

javac StudentManagementApp.java
java StudentManagementApp

Sample Usage
=== Student Management System ===
1. Add Student
2. View Students
3. Delete Student
4. Exit
Enter your choice: 1

Enter ID: 123
Enter Name: Rey
Enter Age: 23
Enter Course: Computer Science
✅ Student added successfully!
Technical Details

Language: Java
Storage: File-based persistence (CSV format)
Data Structure: ArrayList for in-memory storage

File: students.txt for permanent storage

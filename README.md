# 🎓 Student Management System in C

A console-based Student Management and Grade Analysis System developed using the C programming language.

The program allows users to manage student records and perform basic academic analysis such as calculating grades, class average, topper, and pass/fail statistics.

## 🚀 Features

- ➕ Add student records
- 📋 Display student records
- 🔍 Search student by roll number
- ✏️ Update student details
- 🗑️ Delete student records
- 📝 Calculate student grades
- 📊 Calculate class average
- 🏆 Find class topper
- ✅ Count pass and fail students
- 💾 File handling for storing records

## 🧠 Concepts Used

- Structures
- Arrays
- Functions
- Pointers
- Strings
- Loops
- `if-else`
- `switch`
- File handling
- Input validation

## 🏗️ Student Structure

```c
struct Student {
    int roll;
    char name[50];
    float marks;
};

Each student record stores:

->Roll number
->Name
->Marks

▶️ How to Run
Compile:
gcc student_management.c -o student
Run:
./student
Windows:
student.exe

📸 Sample Output
<img width="397" height="390" alt="image" src="https://github.com/user-attachments/assets/09ada2f0-6370-49f4-a500-c0cc21a13a09" />


🔮 Future Improvements
Add multiple subjects
Add attendance management
Generate student report cards
Add sorting by marks or roll number
Export records to CSV
Add login authentication
Connect the system to a database

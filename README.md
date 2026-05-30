# Student Grade Tracker
 
A simple console-based Java application that collects student names and grades, then generates a summary report with average, highest, and lowest scores.
 
Built as part of the [CodeAlpha](https://www.codealpha.tech/) Java internship program.
 
---
 
## Features
 
- Enter any number of students and their grades
- Displays a formatted report listing each student's name and score
- Calculates and shows:
  - Average score
  - Highest score
  - Lowest score
## Demo
 
```
Enter number of students: 3
 
Enter student name: Alice
Enter grade: 88
 
Enter student name: Bob
Enter grade: 74
 
Enter student name: Carol
Enter grade: 95
 
===== STUDENT REPORT =====
Name: Alice | Grade: 88
Name: Bob   | Grade: 74
Name: Carol | Grade: 95
 
Average Score: 85.67
Highest Score: 95
Lowest Score:  74
```
 
## Getting Started
 
### Prerequisites
 
- Java Development Kit (JDK) 8 or higher
### Run locally
 
```bash
# Clone the repository
git clone https://github.com/anshusahu2007/CodeAlpha_Student-Grade-Tracker.git
cd CodeAlpha_Student-Grade-Tracker
 
# Compile
javac StudentGradeTracker.java
 
# Run
java StudentGradeTracker
```
 
## Project Structure
 
```
CodeAlpha_Student-Grade-Tracker/
└── StudentGradeTracker.java   # Main application file
```
 
## How It Works
 
1. The program prompts for the number of students.
2. For each student, it reads a name and an integer grade via the console.
3. It tracks the running total, highest, and lowest grades as input is collected.
4. After all entries are complete, it prints a full report with per-student details and aggregate statistics.
The `Student` class is a simple data holder with `name` and `grade` fields. All students are stored in an `ArrayList<Student>` and iterated for the final report.
 
## Technologies Used
 
- Java (core — `ArrayList`, `Scanner`)
- Console I/O
## Author
 
**Anshu Sahu** — [@anshusahu2007](https://github.com/anshusahu2007)
 
## License
 
This project is open source and available under the [MIT License](LICENSE).
 

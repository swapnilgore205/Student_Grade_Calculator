# 🎓 Student Grade Calculator (Java Console Application)

A simple Java console application to calculate grades based on subject marks entered by the user. This program supports calculating total, average, and assigning grades.

---

## 🧮 Features

- Input student details: name, roll number, and marks
- Supports multiple subjects (user-defined)
- Calculates:
  - Total marks
  - Average marks
  - Final grade (A+, A, B, C, D, F)
- Input validation for empty and invalid entries
- Clean text-based output

---

## 🛠 Technologies Used

- Java (Core)
- Object-Oriented Programming
- Scanner (for user input)
- Console-based UI

---

## 🚀 How to Run

### ▶️ Option 1: Run via Command Line
1. Clone or download the project
2. Navigate to the project folder
3. Compile:
   ```bash
   javac StudentGradeCalculator.java
Run:

bash
Copy code
java StudentGradeCalculator
💻 Option 2: Run in Eclipse IDE
Open Eclipse

Create a new Java project: StudentGradeCalculator

Create a new package (e.g., com.student.app)

Create a new class: StudentGradeCalculator.java

Paste the code

Right-click the file → Run As → Java Application

🧠 Grade Logic
90+ ➤ A+

80–89 ➤ A

70–79 ➤ B

60–69 ➤ C

50–59 ➤ D

<50 ➤ F (Fail)

📸 Sample Output
yaml
Copy code
Enter student name: Swapnil
Enter roll number: 101
Enter number of subjects: 3
Enter marks for subject 1 (0-100): 85
Enter marks for subject 2 (0-100): 90
Enter marks for subject 3 (0-100): 87

===== Student Report =====
Name        : Swapnil
Roll Number : 101
Total Marks : 262/300
Average     : 87.33
Grade       : A
===========================

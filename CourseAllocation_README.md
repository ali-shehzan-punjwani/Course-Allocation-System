# Student Course Allocation System using Discrete Mathematical Principles

## 📌 Project Overview

The **Student Course Allocation System** is a Java-based project developed using **Object-Oriented Programming (OOP)** and **Discrete Mathematical Principles**. The system automates the process of allocating university courses to students based on eligibility criteria such as prerequisites, academic year, and course capacity.

The project simulates a real university enrollment environment by ensuring that students can only register for courses they qualify for while preventing over-enrollment in courses with limited seats.

---

# 🎯 Objectives

The main objectives of this project are:

- Implement a rule-based course allocation system
- Verify student eligibility dynamically
- Apply prerequisite checking
- Enforce course capacity constraints
- Prevent invalid course enrollment
- Generate allocation summaries
- Demonstrate the use of discrete structures in real-world systems

---

# 🧠 Discrete Mathematics Concepts Used

This project applies several concepts of **Discrete Structures**, including:

- **Sets**
  - Used for storing prerequisites, completed courses, and allocated courses

- **Relations**
  - Relationship between students and eligible courses

- **Functions**
  - Eligibility checking functions

- **Logic**
  - Decision-making using conditional statements

- **Graph-like Dependency**
  - Course prerequisite chains

- **Constraint Handling**
  - Capacity limitation and allocation restrictions

---

# 🚀 Features

## ✅ Dynamic Eligibility Verification

The system checks:
- Student academic year
- Completed prerequisite courses
- Previously allocated courses

before allowing enrollment.

---

## ✅ Capacity Monitoring

Each course has limited seats.

The system:
- Tracks enrolled students
- Prevents over-allocation
- Displays remaining capacity

---

## ✅ Interactive Course Allocation

Users can:
- Select students
- View eligible courses
- Allocate multiple courses
- Stop allocation anytime

---

## ✅ Real-Time Validation

The system immediately provides:
- Successful allocation messages
- Invalid selection warnings
- Capacity full alerts
- Missing prerequisite restrictions

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Core Programming Language |
| OOP | System Design |
| Collections Framework | Data Storage |
| Scanner Class | User Input |
| LinkedHashSet | Maintaining Ordered Sets |
| ArrayList | Dynamic Course Lists |

---

# 📂 System Components

## 1️⃣ Course Class

The `Course` class stores:
- Course ID
- Capacity
- Minimum Year
- Prerequisites
- Enrolled Students

### Functions:
- `isEligible()`
- `hasCapacity()`

---

## 2️⃣ Student Class

The `Student` class stores:
- Student Name
- Academic Year
- Completed Courses
- Allocated Courses

---

## 3️⃣ Main Allocation System

The main system:
- Displays students
- Shows eligible courses
- Performs allocation
- Checks constraints
- Generates summary reports

---

# ⚙️ System Workflow

## Step 1 — Initialize Courses

Courses are created with:
- Capacity limits
- Prerequisites
- Academic requirements

---

## Step 2 — Initialize Students

Students are added with:
- Academic year
- Completed courses

---

## Step 3 — Select Student

User selects a student from the list.

---

## Step 4 — Determine Eligible Courses

The system checks:
- Prerequisites
- Capacity
- Previously allocated courses

---

## Step 5 — Allocate Course

If all conditions are met:
- Course is allocated
- Capacity updates automatically

---

## Step 6 — Display Summary

Final allocations are displayed for all students.

---

# 📊 Example Scenarios

## ✅ Case 1 — Missing Prerequisite

If a student has not completed required prerequisite courses, the system blocks enrollment.

### Example:
- DSA requires OOPs
- Student without OOPs cannot enroll in DSA

---

## ✅ Case 2 — Course Full

If course capacity is reached:
- Enrollment is denied
- Warning message displayed

---

## ✅ Case 3 — Successful Allocation

When:
- Student is eligible
- Seats are available

The course is allocated successfully.

---

## ✅ Case 4 — No Eligible Courses

If no courses are available:
- System displays proper message
- Prevents invalid operations

---

# 📁 Project Structure

```bash
CourseAllocationSystem/
│
├── CourseAllocationSystem.java
├── README.md
└── report/
    └── CCP_Report.pdf
```

---

# 🔧 Installation & Execution

## Clone Repository

```bash
git clone https://github.com/your-username/course-allocation-system.git
```

## Open Project Folder

```bash
cd course-allocation-system
```

## Compile Java Program

```bash
javac CourseAllocationSystem.java
```

## Run Program

```bash
java CourseAllocationSystem
```

---

# 📈 Output Features

The program displays:
- Available students
- Eligible courses
- Capacity status
- Allocation success/failure
- Final allocation summary

---

# 🔍 Sample Functionalities

✔ Eligibility Checking  
✔ Prerequisite Validation  
✔ Capacity Management  
✔ Interactive Allocation  
✔ Dynamic Course Lists  
✔ Final Reporting

---

# 💡 Future Improvements

Future enhancements may include:
- GUI-based interface
- Database integration
- Web-based portal
- Priority-based allocation
- Admin login system
- Timetable conflict handling
- Automatic waitlist generation

---

# 📚 Learning Outcomes

This project helped in understanding:
- Discrete Mathematical Structures
- Java OOP Concepts
- Real-world Constraint Problems
- Rule-Based Systems
- Data Structures in Java
- Interactive Console Applications

---

# 📖 References

1. K. Kumar, *University Course Allocation Systems*, International Journal of Computer Applications, 2022.

2. J. Smith and L. Brown, *Automating Academic Enrollment*, Academic Press, 2021.

3. R. Gupta, *Prerequisite-based Course Registration*, Journal of Educational Technology, 2023.

4. P. Johnson, *Capacity Constraints in University Courses*, Higher Education Management Review, 2020.

---

# 📫 Contact

**Ali Shehzan Punjwani**  
🎓 BSCS Student @ Iqra University  
📍 Karachi, Pakistan  
📧 shehzansohail5637@gmail.com  
🔗 https://www.linkedin.com/in/ali-shehzan-punjwani/

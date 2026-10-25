# 📊 Student Marks Report System

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success.svg?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

A clean, efficient Python project designed to automate student performance tracking. This script processes student academic records, calculates averages and grades, generates class-wide statistical insights, and highlights top achievers.

---

## ✨ Features

- 📐 **Individual Score Calculation:** Computes total scores and average marks across all subjects for each student.
- 🏅 **Automated Grading System:** Assigns letter grades based on the following standard scale:
  - **A:** Average $\ge 90\%$
  - **B:** Average $\ge 80\%$
  - **C:** Average $\ge 70\%$
  - **D:** Average $\ge 60\%$
  - **F:** Average $< 60\%$
- 📈 **Class Analytics:** Calculates the overall class average and counts how many students perform above the benchmark.
- 🏆 **Topper Identification:** Automatically detects and displays the highest-scoring student.
- 💻 **Clean Terminal Output:** Provides formatted academic summary reports directly in your console.

---

## 🛠️ Tech Stack & Requirements

- **Language:** Python 3.8+
- **Dependencies:** None (Uses standard Python standard library only)

## 📊 Sample Output

```text
==================================================
           STUDENT PERFORMANCE REPORT           
==================================================
Name          Total     Average     Grade
--------------------------------------------------
Rahul         278       92.67       A
Priya         205       68.33       D
Amit          269       89.67       B
Sneha         173       57.67       F
Vikram        249       83.00       B
--------------------------------------------------
Overall Class Average         : 78.27
Students Above Class Average  : 3
Top Academic Performer        : Rahul (92.67%)
==================================================
```

---

## 📚 Core Programming Concepts Practiced

- **Data Structures:** Lists, Tuples, and Dictionaries for organizing records.
- **Control Flow:** `for` loops and conditional branches (`if`/`elif`/`else`).
- **Functions:** Modular code design for clean calculation and display logic.
- **String Formatting:** Formatted string literals (`f-strings`) for aligned reports.

---

## 🎯 Learning Objectives

This project was built as a practical exercise to:
1. Practice refactoring unstructured or legacy Python code into clean, readable scripts.
2. Implement fundamental algorithms for aggregate metrics (averages, maximums, counting).
3. Design human-readable terminal reports using string formatting techniques.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

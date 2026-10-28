# Python Basics - Data Technician Bootcamp (Week 6)

## 📌 Overview
This repository contains my completed practical exercises for **Week 6 (Python Basics - Day 1 & Day 2)** of the Data Technician bootcamp. The work covers core programming fundamentals, including variables, input/output, type casting, conditional branching, and loops[cite: 1].

## 🔗 Google Colab Notebooks
* **Day 1 Exercises**: [Access Notebook via Colab](https://colab.research.google.com/drive/1BxtUCpDHDO9KsTLEtpWeJCz7_7IWIdez?usp=sharing)[cite: 2]
* **Day 2 Exercises**: [Access Notebook via Colab](https://colab.research.google.com/drive/1lU_-rLedrmLX2mFJ_HNMnnknjyPF_r2K?usp=sharing)[cite: 2]

---

## 🛠️ Key Skills & Concepts Covered
1. **Variables & Data Types**: Storing strings, integers, and floats securely following standard naming practices.
2. **Input/Output Operations**: Utilizing `print()` for console outputs and `input()` for dynamic user interactions.
3. **Type Conversion (Type Casting)**: Explicitly transforming string inputs into integers or floats for accurate mathematical evaluations.
4. **Conditional Logic**: Implementing `if`, `elif`, and `else` statements to handle branching workflows based on dynamic user parameters.
5. **Loops**: Automating repetitive tasks and scanning sequences using `for` and `while` loops.

---

## 💻 Featured Implementation: FizzBuzz Challenge
As part of Day 2 tasks, I implemented the classic **FizzBuzz** algorithm using loops and conditional structures to process integers from 1 to 100:

```python
for i in range(1, 101):
    if i % 3 == 0 and i % 5 == 0:
        print("fizzbuzz")
    elif i % 3 == 0:
        print("fizz")
    elif i % 5 == 0:
        print("buzz")
    else:
        print(i)
```
---

* **Logic breakdown:** The script checks if numbers are divisible by both 3 and 5 first (fizzbuzz), then checks individual divisibility by 3 (fizz) or 5 (buzz), and defaults to printing the number itself.

## 📷Screenshots

---

## ✨About the Author
Tymofii Moshkovskyi

Data Technician Bootcamp Student[cite: 1]

Building foundational programming and data analytics competencies through hands-on practice.

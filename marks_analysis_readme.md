# 🧮 Student Marks Analyzer Using NumPy

This mini-project uses NumPy to simulate and analyze the marks of multiple students across subjects. It showcases core NumPy features like slicing, array operations, aggregation, and memory handling (views vs. copies).

## 📌 Features

- Generates a 2D array (4 students × 5 subjects) with random marks.
- Displays each student’s individual scores.
- Calculates:
  - Subject-wise average (`np.mean`)
  - Total marks per student (`np.sum`)
- Finds the top scorer using `np.argmax`.
- Applies a grace curve using `np.clip`.
- Demonstrates the difference between views and copies in NumPy.

## 🧠 NumPy Concepts Used

- Array creation and reshaping
- Indexing and slicing
- Aggregation: `mean()`, `sum()`
- Max index: `argmax()`
- Value limiting: `clip()`
- Memory behavior: view vs. copy

## 🚀 How to Run

1. Make sure you have Python and NumPy installed.
2. Run the script using:
   ```bash
   python your_script_name.py

Sample Output:


Student 1 has score [85 90 88 79 95]
...
Subject-wise average: [82.5 87.0 90.2 85.7 91.3]
Top scorer: Student 3 with 450 marks
...

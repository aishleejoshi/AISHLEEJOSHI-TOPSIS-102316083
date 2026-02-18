# AISHLEEJOSHI-TOPSIS-102316083


# TOPSIS Assignment

Name: Aishlee Joshi  
Roll Number: 102316083  

---

## 📌 Project Description

This project implements the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method in Python.

TOPSIS is a multi-criteria decision-making technique used to rank alternatives based on their closeness to the ideal solution.

The program takes a CSV file as input along with weights and impacts, computes TOPSIS scores, and generates ranked output.

---

## ⚙️ Technologies Used

- Python 3
- NumPy
- Pandas

---

METHODOLOGY USED:

The TOPSIS method is implemented using the following steps:

Read input data from CSV file.

Validate inputs (file, weights, impacts, numeric values).

Normalize the decision matrix.

Multiply normalized values with weights.

Determine ideal best and ideal worst values.

Calculate distance from ideal best and worst.

Compute TOPSIS score.

Rank alternatives based on scores.

Higher score indicates better alternative.
----
RESULT TABLE:

After execution, the output file contains:

Alternative	Criteria	Topsis Score	Rank
M1	...	0.82	1
M2	...	0.75	2
M3	...	0.60	3

Two new columns are added:

Topsis Score

Rank
---
RESULT GRAPH:
TOPSIS Score
^
|     *
|   *
| *
|____________> Alternatives





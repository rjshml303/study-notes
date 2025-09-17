# Samb Sada Shiv

# Study Notes

Welcome to the **Study Notes** repository! This repository contains helpful notes, summaries, and resources for various subjects/topics.

## 🧠 Topics Covered
1. Python Basics
2. NumPy
3. Pandas
4. Data Analysis
5. (I'll add more once watch videos)

## 📂 Folder Structure

## 📌 Creating a 1D Array

```python
import numpy as np

a = [1, 2, 3, 4, 5]     # Normal Python list
a = np.array(a)         # Convert to NumPy array
print(a)                # Output: [1 2 3 4 5]

a = np.array([1, 2, 3, 4, 5])
print(a)                # Output: [1 2 3 4 5]

🔢 Basic Array Functions
print(max(a))           # 5
print(min(a))           # 1
print(np.mean(a))       # 3.0 (Average)

🧮 2D Array Operations (Row-wise)
a = np.array([1, 2, 3, 4, 5])
b = np.array([2, 3, 4, 5, 6])

r = np.array([
    a + b,
    a - b,
    a * b,
    np.round(a / b)
])
print(r)
**Output:**
[[ 3  5  7  9 11]
 [-1 -1 -1 -1 -1]
 [ 2  6 12 20 30]
 [ 0  1  1  1  1]]

✍️ More NumPy topics coming soon...







## About
These notes are for personal learning and quick reference.

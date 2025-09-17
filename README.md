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

virat= [31,81,89,50]
dhoni=[151,171,178,121]
sachin=[52,3,99,202]

player= [[31,81,89,50],[151,171,178,121], [52,3,99,202]]
player=np.array(player)
print(player)

print(player[0:2,0]) # 0:2 ye row and , k bad coloumn hai 


# 🧠 NumPy Random Functions – Summary

## 1️⃣ `np.random.randint()`

```python
import numpy as np

# Directly printing random integers
print(np.random.randint(1, 100, 5))

# Storing in a variable
a = np.random.randint(1, 100, 5)  # 1 to 100 is the range, and 5 numbers will be generated
print(a)

np.random.uniform()
a1=np.random.uniform(1,100,5)
print(a1) # if need only flot value up to 2 then need to use **round**
print(np.round(a1))

✅ Key Points:
Generates random integers
Range = [low, high) → upper bound excluded
size parameter decides how many numbers to generate

2️⃣ np.random.uniform()
# Generating random floating-point numbers
a1 = np.random.uniform(1, 100, 5)
print(a1)

# If you need only 2 decimal places
print(np.round(a1, 2))

✅ Key Points:

Generates random float values
Range = [low, high)
Use np.round(..., decimals) to control decimal places

3️⃣ np.round()
b1= np.array([100.5, 101.345, 20.5129, 23.609])
print(b1) # just to print to give as it is
print(np.round(b1))  # if need only flot value then need to use **round**
print(np.round(b1,3))  # if need to print after .3 value then need to use **round and after variable,3**

📝 Summary Table
Function	Output Type	Range	Use Case
np.random.randint()	Integers	[low, high)	Random whole numbers
np.random.uniform()	Floats	[low, high)	Random decimal numbers
np.round()	Floats/Ints	-	Round values (control decimals)

🔑 Shortcut:

Integers chahiye → randint()
Floats chahiye → uniform()
Floats me decimals control chahiye → np.round(..., decimals)

np.arange()
print(np.arange(1, 11))         # 1 se 10 tak numbers
print(np.arange(109, 121))      # 109 se 120 tak numbers
print(np.arange(109, 121, 3))   # 109 se 120 tak, step = 3

**string functions**
np.char.lower() → sab ko lowercase me convert karega
np.char.upper() → sab ko uppercase me convert karega
np.char.title() → first letter capital karega
np.char.strip() → extra spaces hataega
np.char.add() → strings concatenate karega

import numpy as np

ll = ['AyUsH', 'NanDU', 'suJATA', 'HaRsH']
arr1 = np.array(ll)
print(arr1)

# Convert all to lower case
print(np.char.lower(arr1))

# Convert all to upper case
print(np.char.upper(arr1))

# Convert to title case
print(np.char.title(arr1))




✍️ More NumPy topics coming soon...







## About
These notes are for personal learning and quick reference.

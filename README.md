# 🆔 Duplicate Identifier Detection using Python
This project implements a simple yet powerful duplicate detection algorithm in Python. It reads a list of student IDs from user input and flags repeated entries efficiently using hashing.

## 🚀 Features
 Duplicate Detection Logic using Python set

 Real-time Input Parsing via command line

 Boolean Mask Output as NumPy array

 Minimal and efficient code (~10 lines)

## 🛠 Tech Stack
**Python 3**

**NumPy** – For boolean array output

## 📂 File

duplicate_identifier.ipynb   # Notebook with ID duplication checker

## ✅ How It Works
Accepts space-separated student IDs via input

Flags each ID as True if it’s a duplicate, otherwise False

Outputs a NumPy array for further use in analytics or preprocessing

**Example:**

vbnet
Input : 1 0 0 3 0 2 4 2 2 2
Output: [False False  True False  True False False  True  True  True]

 ## 📚 Use Cases
Data validation for student records

Preprocessing in ML pipelines

Cleansing survey or form submissions


🔢 NumPy Analyzer


A Python project that integrates NumPy functionalities and Object-Oriented Programming (OOP) principles to perform data operations, statistical analyses, and mathematical computations on datasets using NumPy arrays.


📌 Project Info

FieldDetailsProject NameNumPy AnalyzerLanguagePython 3Libraries UsedNumPyInterfaceMenu-driven Console (Jupyter Notebook / Google Colab)OOP ConceptsClass, Encapsulation, Constructor, @classmethod, @staticmethod


🎯 Objective

Develop a NumPy Analyzer toolkit that allows users to:


Create and manage 1D, 2D, and 3D NumPy arrays
Perform mathematical and statistical computations
Search, sort, and filter array data
Use Object-Oriented Programming principles throughout



✅ Features & Requirements Covered

1. 🏗️ Class and Object Structure


DataAnalytics class encapsulates all functionalities
Private attribute __array (Encapsulation)
Constructor __init__ for initializing arrays


2. 📐 Array Management


Create 1D, 2D, 3D arrays
Indexing — access specific elements by index
Slicing — access rows, columns, or sub-sections
Combining — vstack() (vertical) and hstack() (horizontal)
Splitting — split array into smaller sub-arrays


3. ➕ Mathematical Operations


Element-wise Addition, Subtraction, Multiplication, Division
Dot Product for 1D arrays
Matrix Multiplication for 2D arrays
Division-by-zero protection built-in


4. 🔍 Search, Sort, and Filter


Search for specific values (returns indices)
Sort in ascending or descending order (works for all dimensions)
Filter arrays based on user-defined conditions (>, <, >=, <=, ==)


5. 📊 Aggregating Functions


Sum, Mean, Median, Standard Deviation, Variance


6. 📈 Statistical Functions


Minimum and Maximum values
Percentile calculation
Correlation coefficients between two arrays


7. 🧠 Object-Oriented Programming (OOP)


@classmethod → from_range() — create array from a range
@staticmethod → display_array() — display any array
Private methods for internal computations (encapsulation)


8. 🖥️ User Interface (UI)


Menu-driven interface with 6 options
Same array is reused across all operations (no re-entry needed)
Warning shown if operations are attempted before creating an array
Accepts both space-separated and comma-separated input


9. 🛡️ Exception Handling


Invalid integer/float input caught and re-prompted
Array reshape mismatches handled gracefully
Division-by-zero detected and reported clearly
Index out-of-bounds errors caught



💻 Example Console Interaction

Welcome to the NumPy Analyzer!
==========================================

Choose an option:
1. Create a Numpy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
Enter your choice: 1

Select the type of array to create:
1. 1D Array
2. 2D Array
3. 3D Array
Enter your choice: 2

Enter the number of rows: 2
Enter the number of columns: 3
Enter 6 elements for the array separated by space: 10 20 30 40 50 60

Array created successfully:
[[10 20 30]
 [40 50 60]]



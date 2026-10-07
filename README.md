# Data-Analysis-With-Python
# Data Analysis with Python

A comprehensive Python notebook demonstrating core data analysis concepts, data structures, and mathematical operations using standard libraries like **NumPy** and **Pandas**.

---

## 📌 Project Overview

This repository contains practical examples and implementations of fundamental data manipulation techniques in Python. It covers everything from multi-dimensional array operations to advanced Pandas Series and DataFrame manipulations using real-world statistical models (such as G7 country metrics).

---

## 🧪 Key Topics Covered

### 1. NumPy Fundamentals
* **Array Creation & Types**: Initializing 1D, 2D, and 3D arrays, specifying explicit `dtype` values (`int8`, `int64`, `float64`).
* **Dimensions & Shapes**: Working with array shapes, dimensions (`ndim`), and matrix structures.
* **Indexing & Slicing**: Subsetting 2D matrices, slice indexing, and element mutation.
* **Summary Statistics**: Calculating totals (`sum`), arithmetic means (`mean`), and variance (`var`) across different axes.
* **Vectorized Operations & Broadcasting**: Performing element-wise mathematical operations without explicit loops.
* **Boolean Indexing**: Filtering arrays using logical conditions and conditional masks.
* **Linear Algebra**: Matrix multiplication (`dot`, `@` operator) and array transposition (`.T`).

### 2. Pandas Essentials
* **Pandas Series**:
  * Custom indexing, series naming, and value extraction.
  * Accessing elements via position-based (`.iloc`) and label-based (`.loc`) indexing.
  * Index slicing behavior (including endpoint inclusive behavior).
  * Filtering and modifying Series values dynamically using Boolean logic.
* **Pandas DataFrames**:
  * Constructing DataFrames from Python dictionaries.
  * Structural inspection via `.columns`, `.index`, and `.values`.
  * Analyzing demographic, geographical, and economic metrics (Population, GDP, Surface Area, HDI, Continent).

---

## 🛠️ Requirements & Setup

### Prerequisites
Make sure you have Python 3.x installed along with the required libraries:

```bash
pip install numpy pandas 

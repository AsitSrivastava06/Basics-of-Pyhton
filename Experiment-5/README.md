# 🧪 Experiment: Study of Sets in Python

---

## 🎯 Aim
To study the concept of **Sets in Python**, understand their properties, and implement fundamental set operations for handling collections of unique elements.

---

## 📌 Objectives
- ✅ To understand the definition and characteristics of sets in Python  
- ✅ To learn how sets store unique values and eliminate duplicates  
- ✅ To study operations such as union, intersection, difference, and symmetric difference  
- ✅ To understand the concept and applications of immutable sets (**frozenset**)  

---

## 📖 Theory

### 🐍 Introduction to Sets
A **set** is one of the built-in collection data types in Python used to store multiple values in a single variable.  
Sets are particularly important when working with collections where **uniqueness of elements** must be maintained.

Unlike lists and tuples, sets are based on mathematical set theory and are widely used in data handling, filtering, and comparison operations.

---

### ✨ Characteristics of Sets

#### 📍 (a) Unordered Collection
Sets do not follow a fixed sequence.  
The elements are stored in an unordered manner, therefore the output order may vary.

---

#### 🔁 (b) Unique Elements
A set does not allow duplicate values.  
If duplicate entries are provided, Python automatically removes repeated values.

This property makes sets highly useful for removing redundancy in data.

---

#### 🔢 (c) Unindexed Structure
Sets are not indexed, meaning elements cannot be accessed using positions like lists or tuples.

---

#### 🔄 (d) Mutable Nature
A set is mutable, so elements can be added or removed after creation.  
However, individual elements cannot be modified directly.

---

#### ⚡ (e) Efficient Membership Testing
Sets provide faster membership testing compared to lists due to their internal hashing mechanism.  
This makes them suitable for searching and filtering operations.

---

### ⚙️ Set Operations
Python supports several mathematical operations on sets:

- ➕ **Union**: Combines all elements of two sets  
- ✖️ **Intersection**: Returns only common elements  
- ➖ **Difference**: Returns elements present in one set but not in another  
- 🔀 **Symmetric Difference**: Returns elements that are in either set but not in both  

These operations are useful in solving real-world problems involving group comparisons.

---

### ❄️ Frozenset
A **frozenset** is an immutable version of a set.

#### Features of Frozenset:
- 🔒 Once created, elements cannot be added or removed  
- ✅ Supports all set operations like union and intersection  
- 🗝️ Can be used as dictionary keys due to immutability  

Frozensets are useful when a fixed collection of unique elements is required.

---

## 🛠 Tools / Software Used
- 🐍 Python 3.x  
- 📓 Jupyter Notebook / Google Colab  
- 💻 Any standard Python IDE  

---

## 📂 Program File
- 📄 `practical5.py` – Implementation of set concepts and operations

---

## 🌍 Applications of Sets
Sets are widely used in:
- 🧹 Removing duplicate entries from datasets  
- 🔍 Membership testing and filtering  
- ➗ Performing mathematical set operations  
- 👥 Comparing groups such as students, subjects, or event participants  

---

## 🏁 Conclusion
Sets in Python provide an efficient method for storing and processing collections of unique values.  
They support powerful mathematical operations such as union, intersection, and difference, which are essential for solving real-world programming problems.

This experiment successfully establishes an understanding of sets, their properties, and their applications in Python programming.

---

## 👤 Author
**Asit Srivastava**  
🎓 Electronics & Telecommunication Engineering (ENTC)  
🏫 Symbiosis Institute of Technology, Pune


# 🐍 Python Fundamentals Project (`proyek-python-dasar`)

This repository serves as a comprehensive documentation of my learning journey in **Python** programming fundamentals—ranging from basic syntax, control flow, data structures, and file/exception handling to modularization (modules & packages) and Object-Oriented Programming (OOP) principles. Each topic includes hands-on practice scripts and execution screenshots.

---

## 📑 Table of Contents
- [Project Directory Structure](#-project-directory-structure)
- [System Prerequisites](#-system-prerequisites)
- [Installation & Setup Guide](#-installation--setup-guide)
- [Curriculum Summary & Modules](#-curriculum-summary--modules)
  - [1. Basic Syntax & Variables](#1-basic-syntax--variables)
  - [2. Operators & Control Flow](#2-operators--control-flow)
  - [3. Data Structures](#3-data-structures)
  - [4. Functions, Modules & Packages](#4-functions-modules--packages)
  - [5. File & Exception Handling](#5-file--exception-handling)
  - [6. Object-Oriented Programming (OOP)](#6-object-oriented-programming-oop)
- [Running the Programs](#-running-the-programs)
- [Screenshot Documentation](#-screenshot-documentation)

---

## 📂 Project Directory Structure

```text
proyek-python-dasar/
├── python-dasar/                 # Main directory containing all Python practice scripts
│   ├── my_package/               # Custom Python package example
│   │   ├── __init__.py
│   │   ├── geometri.py
│   │   └── operasi.py
│   ├── hello.py                  # First Python program (Hello World)
│   ├── struktur_dasar.py         # Basic Python program structure & indentation
│   ├── variable.py               # Variable declaration & assignment
│   ├── constants.py              # Defining and using constants
│   ├── tipe_data.py              # Primitive data types (int, float, str, bool)
│   ├── operator.py               # Arithmetic, comparison, and logical operators
│   ├── control_flow.py           # Conditional branching (if, elif, else) & loops
│   ├── list_tuple_set.py         # Sequence & set collections (List, Tuple, Set)
│   ├── dictionary.py             # Key-value pair collections (Dictionary)
│   ├── function.py               # Defining and calling reusable functions
│   ├── matematika.py             # Custom module for mathematical operations
│   ├── module.py                 # Importing and utilizing custom/built-in modules
│   ├── package.py                # Importing modules from a custom package
│   ├── file_handling.py          # Reading and writing external text files
│   ├── contoh.txt                # Sample text file for file handling practice
│   ├── data.txt                  # Sample data file for file I/O operations
│   ├── exception_handling.py     # Error handling using try, except, else, and finally
│   ├── class_object.py           # OOP basics: Classes and Objects
│   ├── encapsulation.py          # OOP principle: Encapsulation & access modifiers
│   ├── inheritance.py            # OOP principle: Inheritance & method overriding
│   ├── polymorphism.py           # OOP principle: Polymorphism
│   └── abstraction.py            # OOP principle: Abstraction (ABC module)
├── screenshot/                   # Execution screenshots (#1.png to #19.png)
├── .gitignore                    # Git ignore rules (venv/, __pycache__/, etc.)
├── README.md                     # Main project documentation
└── requirements.txt              # Project dependencies list
```

---

## 💻 System Prerequisites

Before running the scripts in this repository, ensure your environment meets the following requirements:
- **Python 3.x** (Python 3.10 or newer is recommended) installed and configured in your system *PATH*.
- **PIP** (*Python Package Installer*) available for package management.
- **Code Editor / IDE** such as PyCharm or Visual Studio Code.
- **Git** for version control.

---

## ⚙️ Installation & Setup Guide

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd proyek-python-dasar
```

### 2. Create & Activate a Virtual Environment (`venv`)
Using a virtual environment keeps project dependencies isolated from your global Python installation.

- **Windows (Command Prompt / PowerShell):**
  ```bash
  python -m venv venv
  venv\Scripts\activate
  ```

- **Linux / macOS:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Install Dependencies
Install any required packages listed in `requirements.txt`:
```bash
pip install -r requirements.txt
```

---

## 📚 Curriculum Summary & Modules

### 1. Basic Syntax & Variables
- **`hello.py` & `struktur_dasar.py`:** Introduction to Python syntax, comments, indentation rules, and standard output using `print()`.
- **`variable.py` & `constants.py`:** Storing and updating values in dynamically typed variables, as well as naming conventions for constants.
- **`tipe_data.py`:** Working with fundamental data types including integers (`int`), floating-point numbers (`float`), strings (`str`), and booleans (`bool`).

### 2. Operators & Control Flow
- **`operator.py`:** Implementing arithmetic (`+`, `-`, `*`, `/`, `%`, `**`), comparison (`==`, `!=`, `<`, `>`, `<=`, `>=`), and logical (`and`, `or`, `not`) operators.
- **`control_flow.py`:** Controlling execution flow using conditional statements (`if`, `elif`, `else`) and iterative loops (`for` and `while`).

### 3. Data Structures
- **`list_tuple_set.py`:** Creating, indexing, slicing, and modifying mutable `list` collections, immutable `tuple` sequences, and unordered unique `set` collections.
- **`dictionary.py`:** Managing structured `key: value` pairs, accessing elements safely, updating entries, and iterating over keys and values.

### 4. Functions, Modules & Packages
- **`function.py`:** Writing modular and reusable code blocks using `def`, parameters, return values, and various argument patterns.
- **`matematika.py` & `module.py`:** Creating a custom Python module (`matematika.py`) and importing its functions into another script (`module.py`).
- **`my_package/` & `package.py`:** Structuring multi-file modules inside a package directory (`__init__.py`, `geometri.py`, `operasi.py`) and importing them cleanly.

### 5. File & Exception Handling
- **`file_handling.py` (`contoh.txt`, `data.txt`):** Performing file input/output (I/O) operations—reading (`r`), writing (`w`), and appending (`a`) text files safely using context managers (`with open(...)`).
- **`exception_handling.py`:** Gracefully catching and handling runtime errors using `try`, `except`, `else`, and `finally` blocks.

### 6. Object-Oriented Programming (OOP)
- **`class_object.py`:** Defining blueprints (`class`), initializing attributes via constructors (`__init__`), creating object instances, and defining methods.
- **`encapsulation.py`:** Protecting internal object state using private/protected attributes and getter/setter methods.
- **`inheritance.py`:** Creating parent-child class hierarchies to reuse and extend existing attributes and methods.
- **`polymorphism.py`:** Implementing unified interfaces where different classes define their own behavior for the same method name.
- **`abstraction.py`:** Defining abstract base classes and abstract methods using Python's `abc` module to enforce structure in subclasses.

---

## ▶️ Running the Programs

Ensure your terminal is in the root project directory (`proyek-python-dasar/`) with your virtual environment activated, then run any script inside `python-dasar/`:

```bash
# Basics & Data Types
python python-dasar/hello.py
python python-dasar/struktur_dasar.py
python python-dasar/variable.py
python python-dasar/constants.py
python python-dasar/tipe_data.py

# Operators & Control Flow
python python-dasar/operator.py
python python-dasar/control_flow.py

# Data Structures
python python-dasar/list_tuple_set.py
python python-dasar/dictionary.py

# Functions, Modules & Packages
python python-dasar/function.py
python python-dasar/module.py
python python-dasar/package.py

# File & Exception Handling
python python-dasar/file_handling.py
python python-dasar/exception_handling.py

# Object-Oriented Programming (OOP)
python python-dasar/class_object.py
python python-dasar/encapsulation.py
python python-dasar/inheritance.py
python python-dasar/polymorphism.py
python python-dasar/abstraction.py
```

---

## 🖼️ Screenshot Documentation

All execution outputs and progress checkpoints (`#1.png` through `#19.png`) are documented and stored inside the [`screenshot/`](./screenshot/) directory.
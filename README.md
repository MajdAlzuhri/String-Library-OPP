# 📚 String Library - C++ OOP

C++ OOP Algorithms Status

A custom **C++ String Utility Library** implemented using **Object-Oriented Programming (OOP)** principles.

This library contains a collection of commonly used string manipulation algorithms organized inside a reusable class called **clsString**.

The goal of this project is to demonstrate how string-processing algorithms can be transformed into a clean, reusable, and maintainable C++ library.

---

# 📑 Table of Contents

- Project Overview
- Features
- Concepts Applied
- Project Structure
- Example Usage
- Example Output
- Future Improvements
- Learning Source

---

# 🚀 Project Overview

String manipulation is one of the most frequently used tasks in software development.

Instead of creating separate functions every time a string operation is needed, this project gathers many useful string algorithms into a single reusable class.

The library provides an organized and object-oriented approach to handling string operations while improving code readability, maintainability, and reusability.

---

# ⚙️ Features

The **clsString** class provides a wide range of string utilities.

## 📝 Word Operations

- Count words in a string
- Print words
- Split string into words
- Join words into a single string
- Reverse words order
- Extract words from text

## 🔤 Letter Operations

- Convert string to Uppercase
- Convert string to Lowercase
- Capitalize first letter of each word
- Lowercase first letter of each word
- Invert character case

## 🔍 Character Analysis

- Count capital letters
- Count small letters
- Count vowels
- Print vowels
- Count specific characters

## ✂️ String Cleaning

- Trim left spaces
- Trim right spaces
- Trim entire string
- Remove punctuation

## 🔄 String Editing

- Replace words
- Replace characters
- Reverse string content
- Modify characters by position

## 🧩 Validation & Utilities

- Compare strings
- Search for substrings
- Static utility functions

---

# 🧠 Concepts Applied

- Object-Oriented Programming (OOP)
- Encapsulation
- Classes and Objects
- Static Methods
- Function Reusability
- Algorithm Design
- Clean Code Practices

---

# 📂 Project Structure

```text
Project-8-String-Library-OOP
│
├── clsString.h
│   String utility library containing all string algorithms
│
└── main.cpp
    Example application demonstrating library usage
```

---

# 💻 Example Usage

```cpp
#include <iostream>
#include "clsString.h"

using namespace std;

int main()
{
    clsString String1("welcome to cpp programming");

    cout << "Original String: "
         << String1.Value << endl;

    cout << "Words Count: "
         << String1.CountWords() << endl;

    String1.UpperFirstLetterOfEachWord();

    cout << "After Capitalizing: "
         << String1.Value << endl;

    return 0;
}
```

---

# 🎓 Learning Source

This project was implemented while following the Programming Advices Roadmap.

### Instructor

**Dr. Mohammed Abu-Hadhoud**

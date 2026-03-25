# 📘 C++ Operators

---

## 🌟 Overview

Operators are symbols that perform operations on variables and values. For example, `+` is an operator used for addition, while `-` is an operator used for subtraction.

---

## 🔑 Types of Operators in C++

Operators in C++ can be classified into 6 types:

- ➕ Arithmetic Operators  
- 📝 Assignment Operators  
- 🔍 Relational Operators  
- 🧠 Logical Operators  
- ⚙️ Bitwise Operators  
- 🧩 Other Operators  

---

## 1️⃣ ➕ C++ Arithmetic Operators

Arithmetic operators are used to perform arithmetic operations on variables and data.

```cpp
a + b;
```

Here, the `+` operator is used to add two variables `a` and `b`.

### 📊 Operators Table

| Operator | Operation |
|----------|----------|
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |
| % | Modulo Operation |

---

### 💻 Example 1: Arithmetic Operators

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 7, b = 2;

    cout << "a + b = " << (a + b) << endl;
    cout << "a - b = " << (a - b) << endl;
    cout << "a * b = " << (a * b) << endl;
    cout << "a / b = " << (a / b) << endl;
    cout << "a % b = " << (a % b) << endl;

    return 0;
}
```

---

## ⚠️ Division Behavior

- `7 / 2 = 3`
- `7.0 / 2 = 3.5`

---

## 🔁 Increment and Decrement Operators

- `++` increases value by 1  
- `--` decreases value by 1  

```cpp
int num = 5;
++num; // 6
```

---

## 2️⃣ 📝 C++ Assignment Operators

Used to assign values to variables.

```cpp
a = 5;
```

### 📊 Operators Table

| Operator | Example | Equivalent |
|----------|--------|------------|
| = | a = b | a = b |
| += | a += b | a = a + b |
| -= | a -= b | a = a - b |
| *= | a *= b | a = a * b |
| /= | a /= b | a = a / b |
| %= | a %= b | a = a % b |

---

## 3️⃣ 🔍 C++ Relational Operators

Used to compare values.

| Operator | Meaning |
|----------|--------|
| == | Equal to |
| != | Not equal to |
| > | Greater than |
| < | Less than |
| >= | Greater than or equal |
| <= | Less than or equal |

---

## 4️⃣ 🧠 C++ Logical Operators

Used to combine conditions.

| Operator | Meaning |
|----------|--------|
| && | Logical AND |
| || | Logical OR |
| ! | Logical NOT |

---

## 5️⃣ ⚙️ C++ Bitwise Operators

Operate on bits.

| Operator | Description |
|----------|------------|
| & | AND |
| | | OR |
| ^ | XOR |
| ~ | Complement |
| << | Left Shift |
| >> | Right Shift |

---

## 6️⃣ 🧩 Other C++ Operators

| Operator | Description |
|----------|------------|
| sizeof | Size of data type |
| ?: | Ternary operator |
| & | Address of variable |
| . | Member access |
| -> | Pointer access |
| << | Output |
| >> | Input |

---

## 🏁 Summary

✨ C++ operators:

- Perform operations on data  
- Are essential for logic building  
- Help in decision making and computation  

---


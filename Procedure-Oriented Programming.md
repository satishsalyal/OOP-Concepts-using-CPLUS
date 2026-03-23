# 📘 Procedure-Oriented Programming (POP)

---

## 🔰 Introduction

**Procedure-Oriented Programming (POP)** is a programming paradigm that focuses on **procedures or functions** to perform tasks.

In POP, a program is divided into smaller parts called **functions**, where each function performs a specific task.

> 💡 The main aim is to solve problems using **step-by-step instructions (algorithms)**.

📌 It follows a **Top-Down Approach**, where a complex problem is broken into smaller sub-problems.

---

## 📖 Definition

**Procedure-Oriented Programming** is a programming approach where programs are structured into procedures (functions), and data is processed through these procedures.


---

# 🎯 Simple Visual (No Mermaid – Works Everywhere)

```markdown
## 📌 POP Structure (Simple Representation)

        +-------------------+
        |     Main Program  |
        +-------------------+
           /      |      \
          /       |       \
+-----------+ +-----------+ +-----------+
| Function1 | | Function2 | | Function3 |
+-----------+ +-----------+ +-----------+
        \        |        /
         \       |       /
          +----------------+
          |   Shared Data  |
          +----------------+
---
## ⚙️ Key Characteristics

- 🔹 Focus on **functions/procedures**
- 🔹 Uses **top-down design approach**
- 🔹 Data is **globally shared**
- 🔹 Functions operate on shared data
- 🔹 Emphasis on **logic and algorithms**

---

## 🧩 Basic Structure of POP

A typical POP program consists of:

1. 📥 **Input** – Accepting data  
2. ⚙️ **Processing** – Performing operations using functions  
3. 📤 **Output** – Displaying results  

---

## 💻 Example (C++)

```cpp
#include <iostream>
using namespace std;

// Function to add two numbers
int add(int a, int b) {
    return a + b;
}

int main() {
    int x = 10, y = 20;
    int result = add(x, y);

    cout << "Sum = " << result;
    return 0;
}

``` 
---
## 📌 🧠 Explanation

✨ In Procedure-Oriented Programming (POP):

🧩 Program is divided into functions
🔄 Data is passed between functions
🎯 Focus is on procedure (function execution)
🚀 🌟 Features of POP
🔸 1. 🧭 Top-Down Approach

Breaks a complex problem into smaller sub-problems.

🔸 2. 🧱 Function-Based Structure

Programs are organized using functions/modules.

🔸 3. 🌐 Global Data Sharing

Data can be accessed by multiple functions.

🔸 4. ⏩ Sequential Execution

Instructions execute step-by-step.

🔸 5. 🧩 Modular Programming
---
---
## Program is divided into smaller manageable modules.

## ✅ 👍 Advantages
- ✔️ Simple and easy to learn
- ✔️ Suitable for small programs
- ✔️ Easy debugging
- ✔️ Less memory usage
- ✔️ Faster execution


## ❌ 👎 Disadvantages
- ❌ Lack of data security
- ❌ Difficult for large programs
- ❌ No data hiding
- ❌ Limited code reusability
- ❌ Difficult maintenance

---

| 🔍 Feature       | 🧩 POP    | 🧱 OOP    |
| ---------------- | --------- | --------- |
| 🎯 Focus         | Functions | Objects   |
| 🧭 Approach      | Top-down  | Bottom-up |
| 🔐 Data Security | Low       | High      |
| ♻️ Reusability   | Limited   | High      |
| 🛠 Maintenance   | Difficult | Easy      |

---
## 🌍 💡 Applications of POP

- 🖥 System Programming (C language)
- 🔌 Embedded Systems
- 📊 Scientific Calculations
- 📐 Algorithm-based Programs
- 🧪 Small-scale Applications
---
---
### ⚠️ 🚧 Limitations

- ❌ Not suitable for large systems
- ❌ Poor real-world modeling
- ❌ Data can be modified easily
- ❌ Not ideal for modern development
---



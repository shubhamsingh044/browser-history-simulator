# 🌐 Browser History Simulator

### DSA Minor Project — Browser History using Stack

A simple and interactive **Browser History Simulator** that demonstrates how the **Stack data structure (LIFO)** can be used to implement browser navigation features such as **Back** and **Forward**.

---

## 👨‍💻 Team Members

1. **Shubham Kumar Singh**
2. **Adarsh Kumar Singh**
3. **Aman Kumar**
4. **Swapnil Gupta**
5. **Sachin Kumar**

### 🎓 College

**Rungta College of Engineering and Technology**  
Department of Computer Science & Engineering  
B.Tech – Computer Science & Engineering  
Batch: **2024–2028**

---

## 📌 Project Overview

In a web browser, users can move between previously visited pages using the **Back** and **Forward** buttons.

This project simulates that functionality using **two Stack data structures**:

- 🔙 **Back Stack**
- 🔜 **Forward Stack**

The project visually demonstrates how elements are pushed and popped from stacks during browser navigation.

---

## 🎯 Objectives

- Understand the practical use of the **Stack data structure**.
- Demonstrate the **LIFO (Last In, First Out)** principle.
- Simulate browser **Back** and **Forward** operations.
- Visualize PUSH and POP operations.
- Understand the time and space complexity of stack-based navigation.

---

## 🧠 Data Structure Used

### Stack

A Stack follows the:

> **LIFO – Last In, First Out**

The last element inserted into the stack is the first element removed.

### Stack Operations

| Operation | Description | Complexity |
|---|---|---|
| PUSH | Adds an element to the stack | O(1) |
| POP | Removes the top element | O(1) |
| PEEK | Returns the top element | O(1) |
| isEmpty | Checks whether stack is empty | O(1) |
| size | Returns number of elements | O(1) |

---

## 🔄 How Browser History Works

The simulator uses two stacks.

### 🔙 Back Stack

Stores previously visited pages.

### 🔜 Forward Stack

Stores pages that can be reached after moving backward.

### Example

Suppose the user visits:

```text
Google → YouTube → GitHub → Wikipedia

# 🐍 Day 04 - Rock Paper Scissors

## 📚 Concepts Covered

### 🎲 Random Module
- Imported `random`
- Used `random.randint(0,2)` to generate a random number
- Used that number as an **index** to select from a list

### 📦 Lists
- Created a list:
  ```python
  x = ["rock", "paper", "scissors"]
  ```
- Accessed list items using index
- Learned about **offset (index starting at 0)**

### 🔢 Index & Offset
- Python lists start at index **0**
- Example:
  - `x[0]` → rock
  - `x[1]` → paper
  - `x[2]` → scissors

If you try:
```python
x[3]
```
It causes an **IndexError** because the list only has 3 items.

---

### ➕ Appending to Lists
Learned how to add items using:
```python
x.append("new_item")
```

---

### 🧱 Nested Lists
Understood that lists can exist inside other lists:
```python
nested = [ ["a", "b"], ["c", "d"] ]
```

---

## 🛠 Project: Rock Paper Scissors Game

### 🎯 What This Program Does
- Takes user input (0,1,2)
- Randomly generates computer choice
- Uses conditionals to determine winner
- Displays ASCII art for each choice

---

## 💻 Code Overview

- Used `random.randint()` for computer decision
- Used list indexing for selection
- Used multiple `if-elif` conditions
- Handled invalid input

---

## 🚀 Key Learnings

- How randomness works in Python
- How list indexing works internally
- Why IndexError happens
- How to structure game logic
- Importance of clean conditional logic

---

## 🧠 Improvements for Future

- Convert user input to integer
- Reduce repeated if-else blocks
- Use lists for ASCII art instead of multiple variables
- Handle errors more cleanly

---

> Day 04 Completed ✅  
> Small project. Big learning.
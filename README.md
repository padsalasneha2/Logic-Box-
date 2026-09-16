# Pattern Generator and Number Analyzer

## 📌 Project Description

**Pattern Generator and Number Analyzer** is a simple Python menu-driven program created for learning Python programming concepts.

This program allows the user to:

1. Generate a star (`*`) pattern.
2. Analyze a range of numbers as **Even or Odd**.
3. Calculate the **sum of all numbers** in a given range.
4. Exit the program.

---

## 🎯 Purpose of the Program

The main purpose of this project is to practice basic Python concepts such as:

* `while` loop
* `for` loop
* `if-elif-else`
* `break` statement
* `range()`
* `input()` and `print()`
* Integer conversion using `int()`
* Modulus operator `%`
* Arithmetic operations
* Menu-driven programming

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **File Type:** `.py`
* **Required Software:** Python 3.x

---

## 📂 Program Features

### 1. Generate a Pattern

The user selects option `1` and enters the number of rows.

The program generates a star pattern according to the number of rows entered.

**Example:**

If the user enters:

```text
Enter the number of rows for the pattern: 5
```

Output:

```text
Pattern:
*
**
***
****
*****
```

---

### 2. Analyze a Range of Numbers

The user selects option `2` and enters a starting and ending number.

The program:

* Checks every number in the range.
* Identifies whether each number is **Even** or **Odd**.
* Calculates the total sum of all numbers.

**Example:**

Input:

```text
Enter the start of the range: 1
Enter the end of the range: 5
```

Output:

```text
Number 1 is Odd
Number 2 is Even
Number 3 is Odd
Number 4 is Even
Number 5 is Odd

Sum of all numbers from 1 to 5 is: 15
```

---

### 3. Exit the Program

When the user selects option `3`, the program stops running.

Output:

```text
Exiting the program. Goodbye!
```

The `break` statement is used to exit the `while` loop.

---

## 💻 Complete Program Output

### Example 1 — Generate Pattern

```text
Welcome to the Pattern Generator and Number Analyzer!

Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit

Enter your choice: 1
Enter the number of rows for the pattern: 5

Pattern:
*
**
***
****
*****
```

---

### Example 2 — Analyze Numbers

```text
Welcome to the Pattern Generator and Number Analyzer!

Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit

Enter your choice: 2

Enter the start of the range: 1
Enter the end of the range: 10

Number 1 is Odd
Number 2 is Even
Number 3 is Odd
Number 4 is Even
Number 5 is Odd
Number 6 is Even
Number 7 is Odd
Number 8 is Even
Number 9 is Odd
Number 10 is Even

Sum of all numbers from 1 to 10 is: 55
```

---

### Example 3 — Invalid Choice

If the user enters a number other than `1`, `2`, or `3`:

```text
Enter your choice: 5
Invalid choice! Please select 1, 2, or 3.
```

---

### Example 4 — Exit

```text
Enter your choice: 3
Exiting the program. Goodbye!
```

---

## 🔄 How the Program Works

The program runs inside a `while True` loop, so the menu continues to appear until the user selects option `3`.

### Program Flow

```text
Start
  ↓
Display Menu
  ↓
Enter Choice
  ↓
 ┌───────────────┬──────────────────────┬──────────────┐
 ↓               ↓                      ↓
Choice 1       Choice 2               Choice 3
 ↓               ↓                      ↓
Pattern        Number Analysis        Exit
 ↓               ↓                      ↓
Display        Even/Odd + Sum         break
Pattern
 ↓               ↓
Return to Menu ←─┘
```

---

## 🧠 Important Python Concepts Used

### `while True`

Used to continuously display the menu.

```python
while True:
```

### `if-elif-else`

Used to check the user's choice.

```python
if choice == 1:
elif choice == 2:
elif choice == 3:
else:
```

### `for` Loop

Used to repeat operations for a specific range.

```python
for i in range(1, rows + 1):
```

### Modulus `%`

Used to check whether a number is even or odd.

```python
if i % 2 == 0:
```

If the remainder is `0`, the number is **Even**. Otherwise, it is **Odd**.

### `break`

Used to stop the `while` loop when the user selects Exit.

```python
break
```

---

## ▶️ How to Run the Program

### Step 1: Install Python

Install Python 3.x on your computer.

### Step 2: Open the Project Folder

Open the folder containing the Python file.

Example:

```text
D:\pattern
```

### Step 3: Open Terminal / PowerShell

Run:

```bash
python filename.py
```

Example:

```bash
python basic.py
```

### Step 4: Select an Option

Enter:

```text
1
```

for Pattern,

```text
2
```

for Number Analyzer,

or

```text
3
```

to Exit.

---

## 📚 Learning Outcomes

After completing this project, the learner understands:

* How menu-driven programs work.
* How to use loops in Python.
* How to use conditional statements.
* How to generate patterns.
* How to check Even and Odd numbers.
* How to calculate the sum of numbers.
* How to use `break` to stop a loop.
* How to handle invalid menu choices.

---

## 👩‍💻 Project Type

**Beginner Python Project**

This project is created for **learning and practice purposes**.

---

## ⭐ Conclusion

The **Pattern Generator and Number Analyzer** is a beginner-friendly Python project that combines loops, conditions, user input, arithmetic operations, and menu-driven programming into one practical application.

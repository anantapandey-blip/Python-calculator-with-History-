# Python-calculator-with-History-
A Python calculator with History featuring basic arithmetic operations, persistent calculation history, input validation, and file handling. Built as a learning project to strengthen my core Python concepts.
#  A Python Calculator with history

A menu-driven calculator built with Python that performs basic arithmetic operations while maintaining a persistent calculation history using a text file. The project focuses on practicing core Python concepts such as functions, loops, conditionals, file handling, and user input validation.

---

##  Features

- Perform basic arithmetic operations:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
- Stores every calculation in a `history.txt` file.
- View previous calculations using the **history** command.
- Clear saved history using the **clear** command.
- Prevents division by zero.
- Validates user input and displays helpful error messages.
- Interactive command-line interface that runs until the user exits.

---

##  Technologies Used

- Python 3

---

##  Project Structure

```
calculator.py
history.txt
README.md
```

---

##  Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Navigate to the project folder

```bash
cd your-repository-name
```

### Run the program

```bash
python calculator.py
```

---

##  Available Commands

| Command | Description |
|---------|-------------|
| `8 + 6` | Performs a calculation |
| `history` | Displays calculation history |
| `clear` | Clears the history file |
| `exit` | Exits the calculator |

---

##  Example

```
---------- SIMPLE CALCULATOR ----------

Enter calculation or command: 12 * 5
Result: 60

Enter calculation or command: history
12 * 5 = 60

Enter calculation or command: clear
History cleared

Enter calculation or command: exit
Goodbye
```

---

##  Concepts Practiced

This project helped me practice:

- Functions
- While loops
- Conditional statements (`if`, `elif`, `else`)
- File handling (`r`, `w`, `a`)
- Reading and writing text files
- String manipulation (`split()`, `strip()`)
- Type conversion
- Input validation
- Basic program structure

---

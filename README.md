# 🧮 SIMPLE CALCULATOR USING PYTHON (CLI INTERACTION)

## 📘 OBJECTIVE
To create a **command-line calculator** that performs basic arithmetic operations such as addition, subtraction, multiplication, and division using Python.

---

## 🛠️ TOOLS USED
- **Language:** Python  
- **Platform:** IDLE / VS Code / Command Prompt  
- **Interaction Type:** CLI (Command Line Interface)

---

## ⚙️ FEATURES
- Performs Addition, Subtraction, Multiplication, and Division  
- Handles invalid inputs and division by zero  
- Uses **functions**, **loops**, and **conditions**  
- Allows continuous execution until the user exits  

---

## 💻 PROGRAM CODE

```python
# Simple Calculator using functions, conditions, loop, and CLI interaction

def add(a, b):
    return a + b

def sub(a, b):
    return a - b

def mul(a, b):
    return a * b

def div(a, b):
    if b == 0:
        return "Error: Division by zero"
    return a / b

while True:
    print("\n--- Simple Calculator ---")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")
    print("5. Exit")

    choice = input("Enter your choice (1-5): ")

    if choice == "5":
        print("Goodbye!")
        break

    if choice not in ["1", "2", "3", "4"]:
        print("Invalid choice! Please try again.")
        continue

    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))

    if choice == "1":
        print("Result =", add(a, b))
    elif choice == "2":
        print("Result =", sub(a, b))
    elif choice == "3":
        print("Result =", mul(a, b))
    elif choice == "4":
        print("Result =", div(a, b))

`````

## ▶️ HOW TO RUN  

**1.** Save the file as calculator.py  

**2.** Open IDLE or any Python terminal.  

**3.** Run the program using:  
   ```bash
   python calculator.py
   `````
**4.** Choose an option (1–5) and enter two numbers.

**5.** The result will be displayed on the screen.

## 📸 OUTPUT SCREENSHOT

<img width="897" height="987" alt="Screenshot 2025-11-13 201012" src="https://github.com/user-attachments/assets/0c007ea3-5ed8-42e2-8935-2260cf2b0bfb" />

<img width="945" height="817" alt="Screenshot 2025-11-13 201042" src="https://github.com/user-attachments/assets/a3f963fb-7fdb-4371-aa05-691ec5ca00ab" />


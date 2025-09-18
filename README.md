# 🧮 Simple Python Calculator

A beginner-friendly calculator built in Python ⚡.  
It supports **basic arithmetic operations** like addition ➕, subtraction ➖, multiplication ✖️, and division ➗ (with division by zero handling 🚫).

---

## 📂 Code

```python
def calculator(a, b, operator):
    if operator == "+":
        print(a + b)
    elif operator == "-":
        print(a - b)
    elif operator == "*":
        print(a * b)
    elif operator == "/":
        if b != 0:  # Handling division by zero
            print(a / b)
        else:
            print("Cannot divide by zero!")
    else:
        print("Invalid operator")

# Example usage
calculator(98, 65, "-")
🚀 Features

➕ Addition

➖ Subtraction

✖️ Multiplication

➗ Division (with zero check)

❌ Invalid operator handling

🛠️ How to Use
Copy the code into a Python file, e.g. calculator.py
Run it in your terminal:
Call the function with two numbers and an operator:

🎯 Example Output

💡 Future Enhancements
✨ Add support for:
🔢 Power (^)
📏 Modulus (%)
🔽 Floor Division (//)

📝 Author
Made with ❤️ in Python 🐍

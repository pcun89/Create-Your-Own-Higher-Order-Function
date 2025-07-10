# Create-Your-Own-Higher-Order-Function
# 🔁 Higher-Order Functions in Python

This project demonstrates how to work with **Higher-Order Functions (HOFs)** in Python — functions that can accept other functions as arguments or return functions as results. Inspired by Codecademy's *Create Your Own Higher-Order Function* project, it features custom function utilities, use of built-in functional tools, and complete unit testing.

---

## 🚀 Features

- ✅ `custom_map()` — your own version of Python’s `map()`
- ✅ `create_multiplier()` — a function that **returns another function**
- ✅ Built-in HOFs: `map()`, `filter()`, `reduce()` for real-world tasks
- ✅ Test coverage using Python’s `unittest` module
- ✅ Code structured for readability, reusability, and modularity

---

## 🧠 Concepts Practiced

- **Higher-Order Functions (HOFs)**
- **Lambda Functions**
- **Function Factories**
- **Data transformation with list comprehensions and functional tools**
- **Unit Testing with `unittest`**

---

## 📁 Project Structure

higher_order_functions/
│
├── higher_order_functions.py # Core logic and examples
├── test_higher_order_functions.py # Unit tests using unittest
└── README.md # Documentation

yaml
Copy
Edit

---

## 💻 How to Run

### Run the main script:
```bash
python higher_order_functions.py
Run unit tests:
bash
Copy
Edit
python test_higher_order_functions.py
🧪 Sample Output
vbnet
Copy
Edit
Original: [1, 2, 3, 4, 5]
Squared: [1, 4, 9, 16, 25]
Names starting with A: ['Alice', 'Anna']
Total Sum: 15
Doubled (custom_map): [2, 4, 6, 8, 10]
Tripled (create_multiplier): [3, 6, 9, 12, 15]
🧪 Unit Test Coverage
Test Name	Description
test_custom_map_with_square	Tests squaring with custom_map()
test_custom_map_with_string_uppercase	Tests custom_map() with strings
test_create_multiplier	Ensures returned function multiplies
test_builtin_map	Confirms map() increments values
test_builtin_filter	Filters names that start with "A"
test_builtin_reduce	Sums elements using reduce()

To run all tests:

bash
Copy
Edit
python -m unittest test_higher_order_functions.py
# 🧮 Quadratic Equation Calculator

A simple, user-friendly **Quadratic Equation Calculator** built using Python and Tkinter. This application solves quadratic equations of the form \(ax^2 + bx + c = 0\), calculates both roots, and identifies whether the solutions are real or complex.

## 🚀 Features

- **Graphical User Interface (GUI):** Clean and easy-to-use interface built with Tkinter.
- **Root Calculation:** Calculates both roots using the quadratic formula.
- **Discriminant Calculation:** Computes the discriminant \(D = b^2 - 4ac\).
- **Root Classification:** Identifies two distinct real roots, one repeated real root, or two complex roots.
- **Input Validation:** Handles invalid numerical inputs and prevents division by zero when the coefficient `a` is zero.
- **Clear Function:** Resets the input fields and results.
- **Instant Results:** Displays the roots and discriminant immediately.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **GUI Framework:** Tkinter
- **Mathematics Module:** cmath

## 📐 Mathematical Formula

The quadratic equation is:

\[
ax^2 + bx + c = 0
\]

The roots are calculated using the quadratic formula:

\[
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\]

The discriminant is:

\[
D = b^2 - 4ac
\]

Depending on the discriminant:

| Discriminant | Result |
|---|---|
| \(D > 0\) | Two distinct real roots |
| \(D = 0\) | One repeated real root |
| \(D < 0\) | Two complex roots |

## 📋 Requirements

- Python 3.x
- Tkinter (usually included with Python)

No third-party Python packages are required for the provided implementation.

## ⚙️ Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/Quadratic-Calculator-Python.git
```

**2. Navigate to the project directory**

```bash
cd Quadratic-Calculator-Python
```

**3. Run the application**

```bash
python quadratic_calculator.py
```

If your system uses the Python launcher, you can also try:

```bash
python3 quadratic_calculator.py
```

## 💻 Example

Consider the equation:

\[
x^2 - 5x + 6 = 0
\]

Input values:

- `a = 1`
- `b = -5`
- `c = 6`

Expected output:

```text
Discriminant: 1.0000
Root Type: Two distinct real roots

Root 1: 3.0000
Root 2: 2.0000
```

## 📁 Project Structure

```text
Quadratic-Calculator-Python/
│
├── quadratic_calculator.py
└── README.md
```

## 🎯 Learning Outcomes

- Understanding quadratic equations and the quadratic formula.
- Implementing mathematical calculations in Python.
- Working with Tkinter widgets and event handling.
- Applying conditional statements and exception handling.
- Designing a simple desktop application.

## 🔮 Future Improvements

- Add an interactive graph of the quadratic equation.
- Include calculation history.
- Add dark mode and customizable themes.
- Package the application as a standalone executable.
- Improve input validation and interface design.

## 👨‍💻 Author

**Kunal Raj**

B.Tech Computer Science Engineering — Artificial Intelligence

## 📄 License

This project is open-source and available for educational and personal learning purposes. You may add an MIT License if you wish to permit broader reuse and distribution.

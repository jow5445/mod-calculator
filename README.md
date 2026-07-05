<h3 align="center">A simple web-based calculator, built with Vanilla JS<br>
    <a href="https://jow5445.github.io/mod-calculator/src/web-calculator.html">
        👉Check Online👈
    </a>
</h3>
<br>
<p align="center"> 
    <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff">&nbsp
    <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff">&nbsp
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000">
    <br>
    <img width="450" src="https://github.com/user-attachments/assets/72b5389b-2b5a-4f36-a888-05e382b531de"  alt="Preview Picture">
</p>

# 🧮 Web App Calculator

A modern, responsive scientific calculator built using **HTML, CSS, and JavaScript**. The application provides a clean user interface, keyboard navigation, sound effects, and support for several mathematical operations beyond basic arithmetic.

## ✨ Features

- ➕ Basic arithmetic operations
  - Addition (+)
  - Subtraction (-)
  - Multiplication (×)
  - Division (÷)

- 🔢 Advanced mathematical functions
  - Power (`xⁿ`)
  - Square Root (`√`)
  - Factorial (`n!`)
  - Logarithm (`log`)
  - Modulus (`mod`)
  - Parentheses support
  - Pi (`π`)

- ⌨️ Keyboard Support
  - Number keys
  - Operators
  - Enter to calculate
  - Backspace to delete
  - Delete / Escape / C to clear
  - Arrow key navigation between calculator buttons
  - Space/Enter to activate the selected button

- 🔊 Sound Effects
  - Button click
  - Delete
  - Calculate
  - Error

- 📱 Responsive Design
  - Works on desktop and mobile devices.
  - Responsive grid layout.

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

---

## 📂 Project Structure

```
calculator/
│
├── index.html
├── style.css
├── script.js
│
└── public/
    └── sounds/
        └── ui/
            ├── btn-click.wav
            ├── btn-calculate.wav
            ├── btn-remove.wav
            └── error.wav
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/web-app-calculator.git
```

### 2. Open the project

Simply open **index.html** in your favorite web browser.

No installation or build tools are required.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|------|--------|
| 0-9 | Enter numbers |
| + - * / | Operators |
| . | Decimal point |
| ( ) | Parentheses |
| Enter | Calculate |
| Backspace | Delete last character |
| Delete | Clear display |
| Escape | Clear display |
| C | Clear display |
| Arrow Keys | Navigate between buttons |
| Space | Press selected button |

---

## 🧮 Supported Operations

| Operation | Example |
|-----------|---------|
| Addition | 5+2 |
| Subtraction | 10-3 |
| Multiplication | 8*4 |
| Division | 20÷5 |
| Power | 2**8 |
| Square Root | √(81) |
| Factorial | 5! |
| Logarithm | log(100) |
| Modulus | 15 mod 4 |
| Pi | π |

---

## 🎯 Future Improvements

- Scientific mode toggle
- Memory functions (M+, M-, MR, MC)
- Calculation history
- Dark mode
- Trigonometric functions
- Keyboard focus animation
- Copy result button
- Calculation expression preview

---

## 📖 How It Works

The calculator:

- Validates user input before evaluation.
- Automatically closes unclosed parentheses.
- Converts mathematical symbols into JavaScript expressions.
- Evaluates expressions safely.
- Handles invalid calculations gracefully.
- Plays audio feedback for different actions.

---

## ⚠️ Error Handling

The application detects invalid calculations such as:

- Division by zero
- Invalid factorial input
- Malformed expressions

When an error occurs:

- "Error" is displayed.
- An error sound is played.
- The display automatically resets after a short delay.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Jow!**

Software Engineer & STEM Student

GitHub: https://github.com/jow5445

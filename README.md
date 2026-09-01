# Calculator

## 📌 Project Overview
A fully functional, browser‑based calculator capable of performing basic arithmetic operations with a clean, user‑friendly button interface. Built with HTML5, CSS3, and vanilla JavaScript, it includes operator chaining, division‑by‑zero protection, and full keyboard support — all without using `eval()`.

## 🛠️ Tech Stack
- **HTML5** – Semantic structure
- **CSS3** – CSS Grid for button layout, custom properties, dark theme, responsive design
- **JavaScript (Vanilla)** – DOM manipulation, arithmetic logic, event handling, keyboard support
- **Google Fonts** – Inter typeface

## ✅ Features Implemented
- [x] Display screen showing current input and result
- [x] Numeric buttons (0–9) and decimal point button
- [x] Operator buttons: addition (+), subtraction (−), multiplication (×), division (÷)
- [x] Equals (=) button to evaluate expressions
- [x] Clear (C) button to reset the display
- [x] Backspace (⌫) button to remove the last entered character
- [x] Division‑by‑zero error handling – displays "Cannot divide by zero" message
- [x] Operator chaining – allows sequential operations (e.g., 5 + 3 × 2)
- [x] CSS Grid used for button layout alignment
- [x] Event listeners on all buttons (no inline onclick attributes)
- [x] Full keyboard support – numbers, operators, Enter, Backspace, Escape

## 🎨 Design Highlights
- Dark theme with gradient backgrounds
- Colour‑coded buttons (numbers, operators, functions, equals)
- Smooth hover and active animations
- Clean, modern display with expression and result areas
- Responsive design for all screen sizes

## 🔧 How It Works (No eval())
- Stores `previousValue`, `operator`, and `currentValue` separately
- Uses `parseFloat()` and a `switch` statement for arithmetic
- Supports operator chaining – evaluates intermediate results before applying new operators
- Handles edge cases like division by zero, invalid inputs, and large numbers

## ⌨️ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `0`–`9` | Number input |
| `.` | Decimal point |
| `+`, `-`, `*`, `/` | Operators |
| `Enter` or `=` | Evaluate |
| `Backspace` | Delete last digit |
| `C` or `Escape` | Clear all |

## 👩‍💻 Author
**Mudupu Sravya**  
- [GitHub](https://github.com/MudupuSravyaReddy)  
- [LinkedIn](https://www.linkedin.com/in/sravya-mudupu-8860a3389)

## 📅 Date
01 September 2026
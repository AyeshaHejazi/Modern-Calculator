# 🧮 Modern Calculator

A sleek, beginner-friendly, single-page web calculator featuring standard and scientific operations, native physical keyboard support, a persistent local evaluation history panel, and a responsive dark mode theme. 

Built natively from scratch with zero external dependencies—just vanilla **HTML5**, **CSS3 (Custom Variables)**, and **Modern JavaScript (ES6+)**.

---

## ✨ Features

- **📐 Dual Modes:** Toggle seamlessly between a clean Standard layout and advanced Scientific operations (`sin`, `cos`, `tan`, `√`, `xʸ`, `log`, `π`, `e`).
- **🌙 Native Dark Mode:** Smooth, accessible dark palette utilizing CSS variables for instant theme swapping.
- **📜 Live History Panel:** Keeps track of your recent calculations. Click any historical result to instantly load it back into the active input display!
- **⌨️ Keyboard Support:** Fully mapped to physical keyboards for rapid workflows.
- **📱 Responsive Design:** Fluid Flexbox and Grid UI optimized for mobile touchscreens, tablets, and desktop displays.

---

## ⌨️ Keyboard Shortcuts Map

| Key | Action |
| :--- | :--- |
| `0` - `9` / `.` | Appends numbers / decimals |
| `+` `-` `*` `/` | Appends operators (`+`, `-`, `×`, `÷`) |
| `%` | Modulo / Percentage operator |
| `Enter` or `=` | Evaluates the current expression |
| `Backspace` | Deletes the last character (`DEL`) |
| `Escape` | Clears everything (`AC`) |

---

## 🚀 Quick Start / Installation

Because this project is written using pure front-end technologies, there is **no compilation, installation, or server setup required**.

1. **Clone or Download** the `calculator.html` file to your computer.
2. **Double-click** the file to open it instantly in any modern web browser (Chrome, Safari, Firefox, Edge).

---

## 🛠️ Project Structure & Architecture

For beginners learning web development, this codebase is structured to showcase clean separation of concerns within a single accessible file:

- **HTML5:** Semantic architecture laying out the display views, hidden scientific key grids, and history sidebar containers.
- **CSS3 Variables (`:root`):** Powering the real-time theme swapping mechanism. All color metrics automatically update when the `data-theme="dark"` attribute is added to the HTML root element.
- **JavaScript Evaluation:** Safely parses multi-step arithmetic using encapsulated, scoped closures without exposing raw global evaluation risks.

---
Screenshot is added.

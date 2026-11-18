# Smart Expense Tracker

A modern, student-focused web application designed to help students track their daily spending, visualize category expenses with a dynamic chart, and receive tailored money-saving tips.

Built purely with vanilla **HTML5**, **CSS3**, and **JavaScript** — requiring zero dependencies, zero installations, and no backend.

---

## 🌟 Features & Design Highlights

1. **Clean Header & Brand Identity**
   - Sleek header with the application title **"Smart Expense Tracker"**, a student badge, and the clear tagline: *"Smart student spending & instant saving insights"*.
   - Includes quick-action controls: **Dark Mode Toggle**, **Sample Data**, and **Reset**.

2. **Consistent Color Palette & Rounded Cards**
   - Refined design system with rounded corners (`16px`), layered shadows, and high contrast.
   - Distinct category colors across the spectrum:
     - 🍔 **Food**: `#ef4444` (Vibrant Coral Red)
     - 🚌 **Travel**: `#0ea5e9` (Vivid Ocean Sky Blue)
     - 📚 **Study**: `#10b981` (Crisp Emerald Green)
     - 🎮 **Fun**: `#f59e0b` (Bright Amber Gold)
     - 💡 **Other**: `#8b5cf6` (Electric Royal Purple)

3. **Built-in Dark Mode Toggle**
   - Seamless one-click switch between **Light Mode** and **Dark Mode**.
   - Auto-detects system color preferences (`prefers-color-scheme`).
   - Persists your choice in `localStorage`.
   - Adapts all UI cards, text, badges, borders, and HTML5 Canvas chart elements dynamically.

4. **Dynamic Canvas Pie / Donut Chart**
   - High-DPI (Retina) donut chart powered by the native HTML5 Canvas API.
   - Slices styled with distinct category colors, thin border separators, and center total.
   - Automatically adapts slice dividers and text color to match light or dark mode.
   - Displays an elegant placeholder ring when ₹0 is spent.

5. **Student-Tailored Smart Saving Tips**
   - Clicking **"Get Saving Tips"** analyzes your highest-spending categories.
   - Delivers 3 actionable student-friendly tips (e.g. transit concession passes, library textbooks, software discounts, and dorm meal prepping).

6. **Add & Manage Expenses**
   - Form with input validation: prevents empty names, zero, or negative amounts.
   - Category filtering (All, Food, Travel, Study, Fun, Other).
   - Instant delete with confirmation toast feedback.
   - Friendly empty-state illustration when no expenses exist.

7. **Responsive on Phone & Laptop**
   - **Laptop / Desktop**: Balanced 2-column layout with clean card alignment.
   - **Mobile / Tablet**: Single-column layout with touch-friendly buttons, comfortable form inputs, and stacked header controls.

8. **Browser Persistence (`localStorage`)**
   - Keeps your expenses and theme preference saved even after closing or refreshing the tab.

---

## 📁 Project Structure

```text
smart-expense-tracker/
│
├── index.html     # Semantic HTML layout, header, cards, and accessible forms
├── style.css      # Modern responsive styles, light/dark themes, and animations
├── script.js      # App logic, dark mode controller, canvas chart, and tips engine
└── README.md      # Documentation and quickstart instructions
```

Total size: **~60 KB** (far below the 5 MB limit, 0 external network requests, 100% offline).

---

## 🚀 How to Open the App

You can open and run the app in any browser:

### Option 1: Direct File Open (Easiest)
1. Open File Explorer and navigate to:
   ```text
   C:\Users\feayu\.gemini\antigravity\scratch\smart-expense-tracker
   ```
2. Double-click **`index.html`** to open it in your default web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Launch via PowerShell
Run this command in PowerShell:
```powershell
Start-Process "C:\Users\feayu\.gemini\antigravity\scratch\smart-expense-tracker\index.html"
```
# smart-expense-tracker

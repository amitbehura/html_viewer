# HTML Render Tool

A **single‑file HTML playground**: type markup on the left, see it render instantly on the right—no build steps or backend required.

## 🚀 Demo
https://amitbehura.github.io/html_viewer/

## ⚡ Quick Start
1. **Clone / download** this repo.  
2. Open **`index.html`** in any modern browser—done!

## 🔧 How It Works
```
┌ Left pane ┐           ┌ Right pane ┐
| <textarea> | ──▶  | <iframe srcdoc> |
└────────────┘           └──────────────┘
```
* Each keystroke updates the iframe’s `srcdoc` via vanilla JavaScript.  
* Runs completely **offline**—everything lives in one file.

## ✨ Features
- Live preview while you type  
- Resizable split panes  
- **Ctrl + S** downloads your code as a standalone `.html` file  
- Mobile‑friendly (portrait stacks, landscape splits)  
- Zero dependencies, zero build tools

## 📂 File Layout
```
/
└─ index.html   ← 100 % of the tool
```

## 🤝 Contributing
Bug to squash? Want dark mode, syntax highlighting, or drag‑and‑drop? Open an **issue** or **PR**—please keep it lightweight and framework‑free.

---

Made with plain **HTML, CSS, and a pinch of JS**. Happy coding! ❤️

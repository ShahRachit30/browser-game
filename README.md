# 🔮 Mind Reader Game

A simple, browser-based number trick that appears to "read your mind." Pick a number, follow a few quick steps, and the page reveals the exact symbol you're thinking of, every time.

**🎮 Play it live:** [https://shahrachit30.github.io/browser-game/](https://shahrachit30.github.io/browser-game/)

---

## ✨ How to Play

1. Pick any **two-digit number** (e.g., `42`).
2. **Add both digits** together (e.g., `4 + 2 = 6`).
3. **Subtract** that sum from your original number (e.g., `42 − 6 = 36`).
4. Find the **symbol** that matches your result in the symbol table and remember it.
5. Click **🧠 Reveal My Symbol**, and the game shows the symbol you picked!

---

## 🧮 How the Trick Works

The "magic" is pure math. Any two-digit number can be written as `10a + b`, where `a` is the tens digit and `b` is the ones digit.

```
(10a + b) − (a + b) = 9a
```

So the result is **always a multiple of 9** (9, 18, 27, 36, 45, 54, 63, 72, or 81).

The game exploits this by assigning the **same symbol to every multiple of 9** in the table, while all other numbers get random symbols. Whichever number you land on, the symbol you remember is the one the game already knows. 🎩

---

## 🛠️ Built With

- **HTML5**: page structure
- **CSS3**: gradient background and styling
- **Vanilla JavaScript**: random symbol generation and table rendering

No frameworks, no dependencies, no build step.

---

## 🚀 Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ShahRachit30/browser-game.git
   ```
2. Open the project folder:
   ```bash
   cd browser-game
   ```
3. Open `index.html` (or the game's HTML file) in any modern web browser. That's it!

---

## 📁 Project Structure

```
browser-game/
├── index.html    # The complete game (HTML, CSS, and JavaScript in one file)
└── README.md     # Project documentation
```

---

## 💡 Ideas for Improvement

- Add a "Play Again" button that reshuffles the symbols without reloading
- Hide the symbol table until the user clicks to view it
- Add animations or sound effects for the reveal
- Make the layout more mobile-friendly
- Add a section that explains the math behind the trick

---

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to fork the repo, make your changes, and open a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ and a little bit of math.

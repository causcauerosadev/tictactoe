# 🎮 Tic-Tac-Toe

A polished, responsive **Tic-Tac-Toe web game** built as a single self-contained HTML file — no frameworks, no build tools, and no external dependencies.

[![Deploy to GitHub Pages](https://github.com/causcauerosadev/tictactoe/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/causcauerosadev/tictactoe/actions/workflows/deploy-pages.yml)

## 🌐 Play Online

**[▶️ Launch Tic-Tac-Toe on GitHub Pages](https://causcauerosadev.github.io/tictactoe/)**

The site is automatically deployed to GitHub Pages whenever changes are pushed to `main`.

## ✨ Features

- ❌⭕ Classic 3×3 Tic-Tac-Toe
- 👥 **Player vs Player** mode
- 🤖 **Player vs Computer** mode
- 🎯 Easy and **Impossible** AI difficulty
- 🧠 Impossible mode powered by the **minimax algorithm**
- 🏆 Automatic win and draw detection
- 💚 Winning cells are highlighted
- 📊 Persistent in-session score tracking
- 📱 Responsive desktop and mobile layout
- ♿ Keyboard-accessible controls and live status updates
- ⚡ Zero dependencies
- 🌐 Static site — runs entirely in the browser

## 🕹️ How to Play

### Player vs Player

Two players take turns placing **X** and **O** on the board. Get three marks in a row horizontally, vertically, or diagonally to win.

### Player vs Computer

Play as **X** against the computer as **O**.

- **Easy** — mostly random moves, with occasional smarter choices.
- **Impossible** — minimax-powered play that cannot be beaten when played correctly.

Use **New Game** to start another round while keeping the current scoreboard.

## 🚀 Run Locally

No installation or build process is required.

```bash
git clone https://github.com/causcauerosadev/tictactoe.git
cd tictactoe
```

Then open `index.html` in any modern web browser.

## 🌐 GitHub Pages Deployment

This repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml` that deploys the site automatically.

### Enable Pages

If GitHub Pages has not been enabled for the repository yet:

1. Open **Settings → Pages** in the repository.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. Push to `main` or manually run the **Deploy to GitHub Pages** workflow.
4. Your game will be available at:

   `https://causcauerosadev.github.io/tictactoe/`

After that initial setup, pushes to `main` automatically trigger deployment.

## 📁 Project Structure

```text
tictactoe/
├── .github/
│   └── workflows/
│       └── deploy-pages.yml
├── index.html
└── README.md
```

The game itself remains completely self-contained in `index.html`.

## 🛠️ Built With

| Technology | Purpose |
| --- | --- |
| **HTML5** | Structure and accessibility |
| **CSS3** | Responsive layout and visual design |
| **Vanilla JavaScript** | Game logic and AI |
| **GitHub Actions** | Automated deployment |
| **GitHub Pages** | Static web hosting |

## 🔒 Privacy

This game is entirely client-side. It does not require an account, backend, database, or external API.

## 📄 License

This project is open source. Add a license file to the repository if you want to specify reuse and distribution terms.

---

Made with ❤️ and JavaScript by **[Caus Cauero](https://github.com/causcauerosadev)**.

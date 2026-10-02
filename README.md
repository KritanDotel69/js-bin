# 🧪 JS Bin: Online Code Playground

A lightweight, browser-based code playground where you can write HTML, CSS, and JavaScript and see the result instantly, with nothing to install or set up. Inspired by tools like JS Bin and CodePen.

**🔗 Live Demo:** [js-bin-plum.vercel.app](https://js-bin-plum.vercel.app)

Built with **React**, **Vite**, and **Tailwind CSS**, and deployed on **Vercel**.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Available Scripts](#-available-scripts)
- [How It Works](#-how-it-works)
- [Deployment](#-deployment)
- [Screenshots](#-screenshots)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 📖 Overview

Trying out a quick idea, testing a snippet, or practising front-end basics shouldn't require creating files and folders. JS Bin gives you a clean in-browser workspace: type your code on one side and watch the output update on the other.

It's useful for:

- Practising HTML, CSS, and JavaScript
- Prototyping small UI ideas
- Debugging and experimenting with snippets
- Learning front-end development without any local setup

---

## ✨ Features

- 📝 **Code editors** for HTML, CSS, and JavaScript
- ⚡ **Live preview** that updates as you type
- 🎨 **Clean, responsive UI** styled with Tailwind CSS
- 🚀 **Fast development and builds** powered by Vite (with Hot Module Replacement)
- 🌐 **Deployed on Vercel**, so you can use it from any device with a browser

> 📌 *Edit this list to match what your app actually does, for example console output, themes, saving code, or downloading files.*

---

## 🧰 Tech Stack

| Category | Technology |
|----------|-----------|
| Frontend library | [React](https://react.dev/) |
| Build tool | [Vite](https://vitejs.dev/) |
| Styling | [Tailwind CSS](https://tailwindcss.com/) + PostCSS |
| Linting | ESLint |
| Package manager | npm |
| Hosting | [Vercel](https://vercel.com/) |
| Version control | Git & GitHub |

---

## 📂 Project Structure

```
js-bin/
│
├── public/               # Static assets
├── src/                  # Application source code (components, styles, entry point)
│
├── index.html            # HTML entry point
├── package.json          # Project dependencies and scripts
├── package-lock.json     # Locked dependency versions
├── vite.config.js        # Vite configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── postcss.config.js     # PostCSS configuration
├── .eslintrc.cjs         # ESLint rules
├── .gitignore            # Files ignored by Git
└── README.md             # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm (comes with Node.js)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/KritanDotel69/js-bin.git
   ```

2. **Go into the project folder**
   ```bash
   cd js-bin
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open the app** in your browser at the address shown in the terminal (usually `http://localhost:5173`).

---

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Starts the development server with hot reload |
| `npm run build` | Creates an optimized production build in `dist/` |
| `npm run preview` | Previews the production build locally |
| `npm run lint` | Runs ESLint to check code quality |

---

## ⚙️ How It Works

1. You write HTML, CSS, and JavaScript in the editor panels.
2. The app combines your code into a single document.
3. That document is rendered inside a sandboxed `iframe`, which shows the live output without affecting the rest of the page.
4. Each change re-renders the preview, so you get instant feedback.

> 📌 *Adjust these steps to match how your app actually renders the preview.*

---

## 🌍 Deployment

The project is deployed on **Vercel**.

To deploy your own copy:

1. Fork or clone this repository
2. Push it to your own GitHub account
3. Import the repository on [Vercel](https://vercel.com/new)
4. Vercel detects Vite automatically. Use the default settings:
   - **Build command:** `npm run build`
   - **Output directory:** `dist`
5. Click **Deploy**

---

## 📸 Screenshots

Add screenshots of your app here. Create a `screenshots/` folder and reference the images:

```markdown
![Editor and Live Preview](screenshots/editor.png)
```

---

## 🔮 Future Improvements

- [ ] Console panel to display `console.log` output
- [ ] Save and load projects (local storage or a database)
- [ ] Shareable links for code snippets
- [ ] Light and dark theme toggle
- [ ] Syntax highlighting and auto-complete
- [ ] Download code as a ZIP or HTML file
- [ ] User accounts with a MERN backend (Node, Express, MongoDB)
- [ ] Support for external libraries (CDN imports)

---

## 📄 License

This project is open for learning and educational purposes. Add a license (e.g. MIT) if you plan to share it publicly.

---

⭐ If you found this project useful, consider giving it a star!

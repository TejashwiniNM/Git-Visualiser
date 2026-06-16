# 🎯 Git Visualizer — Learn Git Step by Step

An interactive, single-file Git learning tool that simulates a live GitHub repository. Click through 38 Git commands, watch files move through Git's 4 zones in real time, and test your understanding with 16 hands-on challenges — no installation, no real Git required.

**🔗 Live Demo:** [https://git-visualiser.netlify.app/](https://git-visualiser.netlify.app/)

---

## ✨ Why this exists

Most people learn Git by memorizing commands — `git add`, `git commit`, `git push` — without ever seeing *what actually happens* to their files and repository. This tool fixes that by simulating every command's effect visually, step by step, instead of just printing terminal output.

## 🚀 Features

- **38 Git commands** — from `git init` to advanced workflows like `git rebase -i` and `git bisect`
- **Live simulated GitHub repo** — a file tree, commit history, and branch view that update in real time as you run commands
- **Git's 4 Zones, animated** — watch files move through Working Directory → Staging Area → Local Repository → Remote
- **Visual commit & branch graph** — built with inline SVG, updates as you branch, merge, and tag
- **Guided "Next →" walkthrough** — perfect for absolute beginners; auto-runs commands in the right order
- **16 hands-on challenges** — 10 quick single-concept challenges plus 5 multi-step workflow challenges (e.g. *Feature Branch Workflow*, *Release Workflow*) with hints and one-click restart
- **Built-in CLI** — type real Git syntax (47 supported patterns) and watch the same simulation respond
- **Danger warnings** — destructive commands like `reset --hard` and `clean -fd` are clearly flagged
- **Full Git + GitHub guide** — built-in reference covering zones, branching, undoing changes, and best practices
- **Fully responsive** — works on desktop and mobile with a dedicated pane switcher

## 🛠️ Tech Stack

- **Pure HTML5, CSS3, vanilla JavaScript** — zero frameworks, zero build tools, zero dependencies
- **Inline SVG** for the live commit/branch graph
- **CSS custom properties** for theming
- Single self-contained `.html` file — open it directly, no server required

## 📂 How to Use

### Option 1 — Try it instantly (recommended)
Open the live demo: **[git-visualiser.netlify.app](https://git-visualiser.netlify.app/)**

### Option 2 — Run it locally
1. Clone this repo:
   ```bash
   git clone https://github.com/TejashwiniNM/Git-Visualiser.git
   ```
2. Open `git-visualizer.html` directly in any modern browser (Chrome, Firefox, Edge, Safari) — just double-click the file, no server needed.

### Option 3 — Deploy your own copy
Drag and drop `git-visualizer.html` into [Netlify Drop](https://app.netlify.com/drop), or push this repo to GitHub Pages / Vercel — it's a single static file, so any static host works.

## 🎮 Getting Started in the Tool

1. Click **Next →** to start the guided tour — it auto-runs commands in order so you can just watch and learn
2. Switch between the **Code / Commits / Branches / Diff / Zones** tabs to see different views of the same live repo
3. Click **🎯 Challenges** to test what you've learned with hands-on goals
4. Stuck? Click **💡 Hint** inside an active challenge, or **📖 Git Guide** for full reference material

## 📌 Scope Note

This is a **teaching simulator**, not connected to real Git or GitHub — it's built purely to visualize Git concepts clearly before you touch a real terminal. Two things from real Git aren't included as "runnable" steps since they don't change repository state: `git --version` (a one-time setup check) and Git Hooks (scripts you write, not commands you run) — both are explained in the built-in guide.

## 🤝 Feedback

Feedback and improvement ideas are always welcome — feel free to open an issue or reach out.

## 📄 License

This project is open for learning and personal use. Feel free to fork and adapt it for your own portfolio or teaching purposes.

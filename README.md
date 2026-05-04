````markdown
# Mnimi 🧠

**A beautiful, minimal and addictive terminal note-taking app.**

> Inspired by the simplicity of **Apple Notes** and the buttery-smooth UX of **lazygit**.

---

![Status](https://img.shields.io/badge/Status-Early%20Development-FF9800)
![Go](https://img.shields.io/badge/Language-Go-00ADD8)
![Bubble Tea](https://img.shields.io/badge/TUI-Bubble%20Tea-5C2D91)
![Linux](https://img.shields.io/badge/Platform-Linux-FF9900)
![macOS](https://img.shields.io/badge/Platform-macOS-000000)

---

## ✨ Vision

Mnimi is a **Terminal User Interface (TUI)** note-taking application designed for developers and terminal lovers who want something fast, elegant, and genuinely enjoyable to use every day.

It combines:

- The clean simplicity of **Apple Notes**
- The keyboard-driven efficiency of **lazygit**

The result? A zen-like experience that feels fast, calm, and addictive.

---

## 🎯 Goals

- ⚡ **Instant startup** (feels like opening a text file)
- 🧘 **Calm, minimal, "zen" UI** — no visual noise
- 🧠 **Beginner-friendly** yet power-user efficient
- ⌨️ **100% keyboard-driven**
- 💾 **Auto-save everything** — zero manual saving
- 📂 **Clean, file-based storage** (no databases, no cloud required)
- ❤️ **Addictive user experience**

---

## 🖥️ UI / UX Design

### Main Layout

```text
┌───────────────────────┬──────────────────────────────┐
│  📁 Folders           │  📝 Note Editor              │
│                       │                              │
│  • Projects           │  # Meeting notes             │
│    • note1.md         │  • Discuss Q3 roadmap        │
│    • note2.md         │  • Follow up with design     │
│                       │                              │
│  • Ideas              │                              │
│                       │                              │
├───────────────────────┴──────────────────────────────┤
│  n = New note   N = New folder   d = Delete   r = Rename │
│  / = Search     Enter = Open     Space = Select   q = Quit │
└────────────────────────────────────────────────────────┘
```
````

Clean split-pane layout. Left sidebar for folders & notes. Right side is the full editor. Bottom status bar shows available actions.

---

## 🎮 Core Controls (MVP)

| Key       | Action                |
| --------- | --------------------- |
| `n`       | New note              |
| `N`       | New folder            |
| `d`       | Delete selected       |
| `r`       | Rename selected       |
| `Enter`   | Open / Edit note      |
| `Space`   | Select / Multi-select |
| `/`       | Instant search        |
| `j` / `k` | Navigate up / down    |
| `h` / `l` | Navigate folders      |
| `q`       | Quit                  |

---

## 📦 Features (MVP)

- ✅ Create, edit, delete notes
- ✅ Folder organization
- ✅ Move notes between folders
- ✅ Instant fuzzy search
- ✅ Auto-save (changes saved the moment you type)
- ✅ Pure keyboard navigation
- ✅ Cross-platform (Linux + macOS)

---

## ✨ Future Features (Roadmap)

- Tags (`#idea`, `#todo`, `#bug`)
- Live Markdown preview
- Full Markdown rendering & syntax highlighting
- Custom themes (dark/light + custom colors)
- Note preview in sidebar
- Optional Git sync / cloud sync (low priority)

---

## 📁 Storage

Everything is stored as plain `.md` files — no proprietary format, no lock-in.

**Linux:**

```bash
~/.mnimi/
```

**macOS:**

```bash
~/Library/Application Support/mnimi/
```

Example structure:

```bash
mnimi/
├── Projects/
│   ├── meeting-notes.md
│   └── roadmap.md
├── Ideas/
│   └── crazy-idea.md
└── Archive/
```

---

## ⚙️ Tech Stack

- **Language**: Go (for speed and single-binary distribution)
- **TUI Framework**: [Bubble Tea](https://github.com/charmbracelet/bubbletea)
- **Styling**: [Lip Gloss](https://github.com/charmbracelet/lipgloss) + Bubbles
- **Editor**: Full-featured text editor component

Single static binary. No dependencies. Works perfectly on Linux and macOS.

---

## 🧠 Philosophy

> **Do one thing — but do it beautifully.**

Mnimi is **not** another bloated note app.  
It is **not** trying to replace Obsidian or Notion.

It is a focused, beautiful tool that makes you _want_ to open your terminal just to write notes.

---

## 🚀 Getting Started

**Coming very soon** (first release planned in the next few weeks).

```bash
# Once released:
brew install mnimi     # macOS
# or
go install github.com/yourusername/mnimi@latest
```

---

## 💡 Why Mnimi?

Because existing tools are:

- ❌ Too complex
- ❌ Too slow to open
- ❌ Not beautiful in the terminal
- ❌ Not fun to use

Mnimi is:

- ✔ Simple
- ✔ Lightning fast
- ✔ Visually calming
- ✔ Addictive

---

## 🤝 Contributing

Love the vision? Contributions are more than welcome!

See [CONTRIBUTING.md](CONTRIBUTING.md) (coming soon).

---

## ❤️ Support

If Mnimi becomes part of your daily workflow, consider:

- Starring the repo ⭐
- Sharing it with your terminal friends
- Sponsoring development (future)

---

## 📌 Status

🚧 **Early development** — MVP is being built right now.

**First public release expected: May/June 2026**

---

**Made with love by TheShaicho for the terminal community.**

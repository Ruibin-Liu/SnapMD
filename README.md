# SnapMD

**A single-file Markdown editor with instant preview**

![Single File](https://img.shields.io/badge/single--file-yes-success)
![Instant Preview](https://img.shields.io/badge/preview-instant-blue)
![No Build Step](https://img.shields.io/badge/build-none-brightgreen)
![Offline](https://img.shields.io/badge/offline-yes-lightgrey)

---

## What is SnapMD?

SnapMD is a **zero-install Markdown editor** that lives in a **single HTML file**.

Just open it in your browser and start writing — no build step, no backend, no dependencies to install.

It’s designed for:
- **Instant preview** while typing
- **Offline use**
- **Portability** (email it, drop it in a folder, keep it on a USB stick)
- **Simplicity** over feature bloat

---

## Features

- ⚡ **Instant Markdown preview** (updates on every keystroke)
- 📄 **Single HTML file**
- 🌐 **Works offline**
- 🧠 **GitHub‑flavored Markdown**
- 💾 **Auto‑save via localStorage**
- 📤 Export as `.md`, HTML, or PDF
- 📂 Open local `.md` files
- 📦 Export/Import Project as ZIP
- ↔️ Resizable editor / preview panes
- 🎹 Comprehensive keyboard shortcuts
- 🌙 Dark and light theme support
- 📥 Drag & drop `.md` files into folders

---

## Why a single-file app?

Because sometimes you just want a tool that:

- Opens instantly
- Doesn’t need Node, Python, Docker, or a build system
- Works five years from now
- Can be shared as **one file**

SnapMD is intentionally boring in the best way.

---

## Getting Started

### Option 1: Download and open

1. Download `index.html` 
2. Double‑click it
3. Start writing Markdown

That’s it.

### Option 2: Clone the repo

```bash
git clone https://github.com/Ruibin-Liu/SnapMD/SnapMD.git
cd SnapMD
open index.html       # rename it if needed
```

No install. No build. No serve command.

---

## Keyboard Shortcuts

| Shortcut | Action |
|--------|--------|
| `Ctrl / Cmd + S` | Save current file |
| `Ctrl / Cmd + O` | Open .md file |
| `Ctrl / Cmd + N` | New file |
| `Ctrl / Cmd + B` | Toggle sidebar |
| `Ctrl / Cmd + D` | Toggle dark/light theme |
| `Ctrl / Cmd + F` | Focus search |
| `Ctrl / Cmd + H` | Toggle help modal |
| `Ctrl / Cmd + I` | Make text italic |
| `Ctrl / Cmd + K` | Create code block |
| `Ctrl / Cmd + Shift + B` | Make text bold |
| `Ctrl / Cmd + Shift + L` | Create anchor at selected text |
| `Ctrl / Cmd + V` | Paste URL → Create inline link |
| `Esc` | Close help modal |

---

## Tech Stack

- Vanilla **HTML / CSS / JavaScript**
- [`marked`](https://github.com/markedjs/marked) for Markdown parsing
- Browser APIs only

No frameworks. No bundlers.

---

## Use Cases

- Quick Markdown notes
- README drafting
- Documentation writing
- Offline writing
- Teaching Markdown
- Lightweight alternative to heavy editors

---

## Philosophy

SnapMD follows a few simple rules:

- ✅ One file is better than many
- ✅ Instant feedback beats delayed polish
- ✅ Shipping beats configuring
- ❌ No telemetry
- ❌ No accounts
- ❌ No cloud lock‑in

---

## Screenshots
  
![SnapMD Screenshot](https://github.com/Ruibin-Liu/SnapMD/blob/main/assets/snapshot.png)
 
---

## Roadmap (Maybe)

Only if it stays simple:

No promises — simplicity comes first.

---

## Contributing

Ideas, bug reports, and small PRs are welcome.

If you’re proposing a feature, please explain:
- Why it belongs in a **single-file** app
- How it avoids adding complexity

---

## License

MIT — do whatever you want, just don’t blame me.



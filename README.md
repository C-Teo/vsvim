# 🖥️ Personal Shortcut Cheat Sheet

This document is a collection of my most frequently used **keyboard shortcuts** across three powerful tools I use daily: **Vim**, **Visual Studio Code (VSCode)**, and **TMUX**. These shortcuts help me navigate, edit, and manage my development environment more efficiently.

## 🧑‍💻 Tools Covered

- **Vim**: A highly efficient text editor for code and writing.
- **VSCode**: A versatile code editor with a rich ecosystem of extensions that streamline my workflow.
- **TMUX**: A terminal multiplexer that allows me to manage multiple terminal sessions.

---

This cheat sheet provides an easy-to-reference list of shortcuts and keybindings for each tool. It's designed to speed up development and help you make the most out of your terminal and editor.

Feel free to use this as a reference or customize it according to your own workflow!

<br>

# Vim by vscodevim — Vim Emulation for Visual Studio Code

A quick reference guide for using Vim keybindings in Visual Studio Code via the [vscodevim extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim).

## 🔄 Basic Navigation

- `h` — Move left
- `j` — Move down
- `k` — Move up
- `l` — Move right  
  _Tip: Use `hjkl` to keep your hands on the home row._

## ✍️ Insert Mode

- `i` — Enter insert mode before the cursor
- `I` — Insert at the beginning of the line
- `a` — Insert after the cursor
- `A` — Insert at the end of the line
- `o` — Open a new line below
- `O` — Open a new line above

## 🖼️ Visual Mode

- `v` — Visual mode (character-wise)
- `V` — Visual line mode
- `Ctrl + v` — Visual block mode

## 📋 Yank (Copy)

- `y` — Yank (copy) selected text
- `yy` — Yank the entire line
- `" + y` — Yank to system clipboard (useful for copying outside VS Code)

## ❌ Delete

- `d` — Delete selected text or text object
- `dd` — Delete the current line
- `x` — Delete the character under the cursor
- `X` — Delete the character before the cursor
- `D` — Delete to the end of the line

## 📂 Folding

- `zM` — Close all folds
- `zO` — Open all folds
- `zR` — Open folds recursively

## 📜 Scrolling

- `Ctrl + u` — Scroll up half a screen
- `Ctrl + d` — Scroll down half a screen
- `Ctrl + b` — Scroll up a full screen
- `Ctrl + f` — Scroll down a full screen
- `zz` — Center the current line in the viewport

## 💡 Tips

- Stay in Normal mode when navigating or manipulating text.
- Use Vim registers (e.g., `"` or `@`) to access clipboard or macros.
- Customize your `.vimrc`-like settings in VS Code under `vim.*`.

## 🔗 Resources

- [vscodevim Extension on Marketplace](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
- [Official GitHub Repository](https://github.com/VSCodeVim/Vim)

<br>

# 🖥️ TMUX on WSL Ubuntu

A quick reference for using **tmux**, the terminal multiplexer, inside **WSL Ubuntu**.

## 🔧 Starting tmux

Run `tmux` in your terminal to start a new session.

All tmux shortcuts use a **prefix**, by default: Ctrl + B

After pressing the prefix, follow it with another key.

## 💻 Common Keybindings

- `Ctrl + B D` — Detach from the current session
- `Ctrl + B %` — Split the window **vertically** (side by side)
- `Ctrl + B "` — Split the window **horizontally** (top/bottom)
- `Ctrl + B` + Arrow Keys — Move between panes (`Left`, `Right`, `Up`, `Down`)
- `Ctrl + B X` — Close the current pane
- `Ctrl + B C` — Create a new window
- `Ctrl + B ?` — View all keybindings (press `q` to exit help)

## 🔍 Scrolling in tmux

1. Press `Ctrl + B [`
2. Use the **Arrow Keys**, `Page Up`, or `Page Down` to scroll
3. Press `q` to exit scroll mode

## 🔗 Resources

- [tmux Official GitHub](https://github.com/tmux/tmux)
- [tmux Cheat Sheet](https://tmuxcheatsheet.com)

<br>

# 🖥️ VSCode Shortcuts

A quick reference guide for some useful keyboard shortcuts in **Visual Studio Code**.

## 📂 Explorer

- `Ctrl + Alt + 0` — Custom command to **close all folders** in the explorer

---

## 🔍 Command Palette

- `Ctrl + Shift + P` — Open the **Command Palette**

---

## 🔢 Switching Between Editors

- `Ctrl + 1-9` — Switch to the editor window by number (e.g., `Ctrl + 1` for the first editor)

---

## 📁 File Explorer & Search

- `Ctrl + Shift + E` — Open the **Explorer** panel
- `Ctrl + Shift + F` — Open the **Search** panel

---

## 🖱️ Integrated Terminal

- Ctrl + ` — Open/close the **Integrated Terminal**

---

Feel free to modify or add more custom keybindings from the **VSCode settings**.

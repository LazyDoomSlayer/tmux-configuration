# Tmux Configuration 🖥️

This is my personal **tmux configuration**, designed to enhance terminal workflows with intuitive key bindings and a clean interface.

---

## 🎯 Features

- **Custom Key Bindings:** Optimized for faster navigation and workflow.
- **Enhanced Prefix:** `Ctrl + Space` for an ergonomic prefix key.
- **Split and Resize Panes:** Effortless terminal pane management.
- **Session Management:** Easily create, switch, and manage tmux sessions.
- **Custom Status Bar:** A clean and informative status line.

---

## ⚡ Installation

1. Clone the repository to your home directory:
   ```bash
   git clone https://github.com/LazyDoomSlayer/tmux-configuration ~/.tmux
   ```

2. Symlink the `.tmux.conf` file:
   ```bash
   ln -s ~/.tmux/.tmux.conf ~/.tmux.conf
   ```

3. Reload tmux to apply the configuration:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

---

## 🔧 Customization

You can tweak the configuration by editing the `.tmux.conf` file directly. Key bindings, appearance, and plugins can all be customized to fit your workflow.

---

## 🛠️ Requirements

- **tmux 3.0 or higher**
- **A patched terminal font** (e.g., Nerd Fonts) for proper status bar display.

---

## ❤️ Acknowledgments

Special thanks to the tmux community for inspiring this configuration and providing useful resources.
```

Absolutely! Here’s the entire `README.md` in one copy-pastable block:

---

```markdown
# My macOS Configuration

This repository contains my personal macOS configuration files for a productive and efficient development environment.  
It uses `~/.config` to manage settings for the following tools:

- **Amethyst** (tiling window manager)
- **Window Borders**
- **Karabiner-Elements** (keyboard remapping)
- **iTerm2** (terminal emulator)

---

## 📁 Directory Structure

```

\~/.config/
├── amethyst/
├── borders/
├── karabiner/
├── iterm2/

````

---

## ✅ Requirements

- macOS (tested on [Your Version])
- Homebrew (recommended)

---

## 📌 Installation

### 1️⃣ Clone this repo

```bash
git clone https://github.com/yourusername/mac-config.git ~/.config
````

---

### 2️⃣ Install dependencies

```bash
# Install Homebrew if not installed
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install Amethyst
brew install --cask amethyst

# Install Karabiner-Elements
brew install --cask karabiner-elements

# Install iTerm2
brew install --cask iterm2

# Install Borders (if using yabai or custom)
# Example:
# brew install koekeishiya/formulae/yabai
```

---

### 3️⃣ Link config files

Some apps read configs directly from `~/.config`.
If not, link manually. For example, for Karabiner:

```bash
ln -s ~/.config/karabiner/karabiner.json ~/Library/Application\ Support/Karabiner/karabiner.json
```

Adjust as needed.

---

## ⚙️ What’s Included

### 🪟 **Amethyst**

* Auto-tiling window manager for macOS.
* Config: `~/.config/amethyst/amethyst.yml`

---

### 🗂️ **Borders**

* Window borders for visible tiling layouts.
* Config: `~/.config/borders/`
* Example: If using `yabai`, add borders config to your `yabairc`.

---

### ⌨️ **Karabiner-Elements**

* Advanced keyboard remapping.
* Config: `~/.config/karabiner/karabiner.json`

---

### 🖥️ **iTerm2**

* Terminal emulator.
* Config: `~/.config/iterm2/`
  *Note: iTerm2 may require manual import/export of settings.*

---

## 🔄 Syncing Changes

1. Edit your local configs.
2. Commit & push:

   ```bash
   git add .
   git commit -m "Update configs"
   git push
   ```

---

## 📚 Resources

* [Amethyst Docs](https://ianyh.com/amethyst/)
* [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
* [iTerm2 Documentation](https://iterm2.com/documentation-preferences.html)
* [Homebrew](https://brew.sh/)

---

## 🛠️ License

\[Your License] (e.g., MIT)

---

## ✨ Notes

* Some apps may require a restart after changing configs.
* Always back up your configs before making major changes.
* Feel free to fork and adjust for your own workflows!

---

Happy hacking! 🚀

```

---

Copy the whole block above into a `README.md` in your repo and you’re good to go!  
If you’d like, I can also help you make **example config files**, a `.gitignore`, or even a shell script to automate symlinking — just say **“yes”**!
```

# 🎨 neofetch — Stylish System Info in Your Terminal

**neofetch** is a CLI tool that displays system information alongside your distro’s logo in the terminal. It’s lightweight, highly customizable, and perfect for screenshots or just checking your system at a glance.

---

## ✅ Features

- Shows essential system information
- Displays OS logo in ASCII art
- Supports many operating systems and desktop environments
- Fully configurable via a config file
- Great for screenshots or status updates

---

## 🔧 Installation

### Debian/Ubuntu
```bash
sudo apt install neofetch
```

### Arch Linux
```bash
sudo pacman -S neofetch
```

### Fedora
```bash
sudo dnf install neofetch
```

### macOS (with Homebrew)
```bash
brew install neofetch
```

---

## 🚀 Basic Usage

### Show system info
```bash
neofetch
```

That’s it! Run and enjoy the view.

---

## ⚙️ Output Includes:

- OS & Kernel
- Uptime
- Shell
- Resolution
- DE/WM
- Theme/Icon
- CPU & GPU
- RAM
- Disk usage
- Terminal

---

## 🛠️ Customize Output

### Only show RAM and CPU
```bash
neofetch --disable everything --enable ram cpu
```

### Set ASCII logo to a specific distro
```bash
neofetch --ascii_distro arch
```

---

## 📂 Config File

The config file allows deep customization:
```bash
~/.config/neofetch/config.conf
```

Change colors, layout, what info is shown, and more.

---

## 🎨 Useful Options

| Option                    | Description                            |
|---------------------------|----------------------------------------|
| `--off`                   | Don't display the ASCII logo           |
| `--ascii_distro <distro>` | Force specific distro logo             |
| `--disable <feature>`     | Disable specific components            |
| `--source <file>`         | Use a custom ASCII image/logo          |
| `--config <file>`         | Use a different config file            |

---

## 🔁 Examples

### Only show info without logo
```bash
neofetch --off
```

### Show logo from another distro
```bash
neofetch --ascii_distro ubuntu
```

---

## 🧩 Tips

- Works great in `.bashrc` or `.zshrc` for showing info on every new terminal.
- Add `neofetch` as part of your system info scripts.
- For a more minimal version, check out [pfetch](https://github.com/dylanaraps/pfetch).

---

## 📚 More Info

- GitHub: [https://github.com/dylanaraps/neofetch](https://github.com/dylanaraps/neofetch)
- Run `man neofetch` or `neofetch --help` for more details.

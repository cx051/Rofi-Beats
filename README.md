# ❄️ Rofi-Beats – Winter Frostline

![Rofi-Beats Banner](https://via.placeholder.com/800x200?text=Rofi-Beats+Winter+Frostline)

**Rofi-Beats** is a winter-themed, minimalist lo-fi launcher for [Rofi](https://github.com/davatorium/rofi), bringing cozy beats to your keyboard-driven workflow 🌨️🎧.

---

## 🌟 Features

- 🎵 **Launch & control lo-fi beats** directly from Rofi  
- 🧊 **Winter-inspired minimalist workflow** for focus  
- ⌨️ **Fully keyboard-driven** – no mouse needed  
- 🔒 **Compiled binary** for easy distribution  
- 🎧 Uses **mpv** with **mpv-mpris** support  
- 🌙 Perfect for late-night coding or study sessions  

---

## 📦 Requirements

Before running Rofi-Beats, make sure the following are installed:

### 1️⃣ System packages (APT)
```bash
sudo apt update
sudo apt install rofi mpv mpv-mpris
````

### 2️⃣ yt-dlp (Official GitHub release)

> ⚠️ Do **not** use the APT version – it may break functionality.

```bash
sudo wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -O /usr/local/bin/yt-dlp
sudo chmod +x /usr/local/bin/yt-dlp
yt-dlp --version
```

---

## 🛠️ Installation

```bash
# Clone repository
cd ~
git clone https://github.com/cx051/Rofi-Beats.git

# Navigate to project folder
cd ~/Rofi-Beats

# Make binary executable
chmod +x rofi-beats.x
```

---

## ▶️ Usage

### Run from Terminal

```bash
./rofi-beats.x
```

### Bind to Keyboard Shortcut (Recommended ❄️)

1. Open **System Settings → Keyboard → Custom Shortcuts**
2. Add a new shortcut with:

   * **Command:** `~/Rofi-Beats/rofi-beats.x`
   * **Shortcut key:** e.g., `F2`
3. Enjoy lo-fi beats at a single keypress 🌨️🎶

---

## ⚡ Support & Future Plans

* Multiple new **themes** in development
* Workflow **enhancements** and **automation scripts**
* Star ⭐ or buy me a coffee ☕ to support future updates

Your support helps Winter Frostline grow 🌨️

---

## 📄 License

Licensed under **[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)**

* ✔ Credit required
* ❌ No commercial use
* ❌ No modification or redistribution

See the LICENSE file for full details.

---

## ❄️ Credits

**Created by:** cx051

**Tip:** Use a dark Rofi theme, low screen brightness, and headphones for the best experience 🌙❄️

```


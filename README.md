# Control.py – Telegram Controlled RAT

This project is a **safe, educational demonstration** of how a Python script can communicate with a Telegram bot.  
It is intended **only for learning purposes in a controlled environment**.  
⚠️ Do not use this code for malicious activity.

---

## ✨ Features
- Simple client controlled via a Telegram bot.
- Can receive commands from bot owner.
- Executes safe tasks and returns results back to Telegram.

---

## 📂 Project
```
control.py        # Main script
```

---

## ⚙️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/magicianKaif/control.git
cd control
```

### 2. Install requirements
```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

## Replace Your Telegram Bot Token & Account Chat id in Control.py

### Start the script
```bash
python control.py
```

- The script will connect to your Telegram bot.  
- You (as the bot owner) can send commands directly in Telegram.  
- Results are sent back into the same chat.  

---

## 💻 Convert to EXE (Windows)

You can package the script into a single `.exe` file using **PyInstaller**.

### Install PyInstaller
```bash
pip install pyinstaller
```

### Build EXE (no console, one file, with icon)
```bash
pyinstaller --onefile --noconsole --icon=controlico.ico control.py
```

The executable will be created in the `dist/` folder.  
You can now run `control.exe` directly without needing Python installed.

---
## CONTACT 
[Instagram](https://Instagram.com/magicianslime/) 
[Telegram](https://t.me/magician_slime) 

## ⚠️ Disclaimer
This project is **for educational purposes only**.  
Do **not** use it on machines you don’t own or without explicit permission.  
The author takes no responsibility for misuse.

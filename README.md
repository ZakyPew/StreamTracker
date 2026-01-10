# 🏆 StreamTracker (OBS Achievement Overlay)

A dynamic, automated Steam Achievement Tracker for OBS Studio.
It runs locally on your PC, scans your active game, and auto-themes the overlay to match the game's artwork.
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/c19bbacf-fdd4-4f0c-927c-014d25a706cf" />

## ✨ Features

* **🦎 Chameleon Theme:** Automatically detects your game and changes overlay colors.
* **📱 Vertical Mode:** Ready for TikTok/Shorts (9:16).
* **🎯 Hunter Mode:** Pin specific achievements to grind for.
* **🎛️ Native OBS Dock:** Control everything from within OBS.
* **⚡ Lightweight:** Written in Python, uses minimal resources.

## 📥 Download

You can download the latest pre-compiled `.exe` from the [Releases Page](../../releases).

## ☕ Support the Project

This project is free and open source. If it helps your stream, consider buying me a coffee!
* **Patreon:** https://www.patreon.com/cw/Zakypew
* **Ko-fi:** https://wwww.Ko-fi.com/ZakyPew


## 🛠️ How to Run from Source

If you prefer running the Python script directly instead of the `.exe`:

1.  **Install Python 3.x**
2.  **Install Dependencies:**
    ```bash
    pip install flask flask-cors requests psutil pillow pyinstaller
    ```
3.  **Run the App:**
    ```bash
    python app.py
    ```

## 📦 Building the EXE
To build your own executable:
```bash
python -m PyInstaller --noconsole --onefile --na

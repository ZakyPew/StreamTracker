# 🏆 StreamTracker (OBS Achievement Overlay)

<p align="center"> <img width="300" height="300" alt="StreamTracker Logo" src="https://github.com/user-attachments/assets/c19bbacf-fdd4-4f0c-927c-014d25a706cf"> </p>

A dynamic, automated Steam Achievement Tracker for OBS Studio. It runs locally on your PC, scans your active game, and auto-themes the overlay to match the game's artwork.


**🎥 Installation Video**
<div align="center">
<a href="https://youtu.be/giiv7gTtkRo"><img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/372ab7e5-7ff7-4605-9c2e-7226ef65723e" /></a></div>

## 🚀 Features

-   **🦎 Chameleon Theme:** Automatically detects your game via Steam and changes overlay colors to match the official artwork.
    
-   **🎯 Hunter Mode:** Pin a specific locked achievement to the screen to show chat what you are grinding for.
    
-   **📱 Vertical Mode:** Dedicated 9:16 layout for TikTok Live and YouTube Shorts.
    
-   **🎛️ Native OBS Dock:** Control the tracker, reset sessions, and adjust volume directly inside OBS.
    
-   **⏱️ Session Tracking:** Live timer + "Session Counter" (shows `+X` unlocks) to track your progress during the current stream.
    
-   **💤 Smart Standby:** Switches to a sleek "Profile Card" showing your avatar and stats when no game is running.
    
-   **⚡ Lightweight:** Written in Python, runs locally, uses minimal resources.
    

## 📸 Screenshots

**Standard Overlay** 
<br></br>
<img width="759" height="161" alt="image" src="https://github.com/user-attachments/assets/27734f7c-cbd4-4e33-952a-51a80e808bb0" />

<img width="728" height="170" alt="image" src="https://github.com/user-attachments/assets/7eb48a0c-866d-4543-9250-67a52443faac" />


**Vertical Mode**
<br></br>
<img width="369" height="279" alt="image" src="https://github.com/user-attachments/assets/e44b8069-8aec-4793-8156-56aeb1c2839e" />


**Control Dock**
<br></br>
<img width="456" height="852" alt="image" src="https://github.com/user-attachments/assets/ef6eebe3-5f4a-4b99-be55-bf879b352c90" />


## 📥 Download

You can download the latest pre-compiled `.exe` from the [Releases Page](https://www.google.com/search?q=../../releases "null").

## ☕ Support the Project

This project is free and open source. If it helps your stream, consider buying me a coffee!

-   **Patreon:** [https://www.patreon.com/cw/Zakypew](https://www.patreon.com/cw/Zakypew "null")
    
-   **Ko-fi:** [https://ko-fi.com/ZakyPew](https://www.google.com/search?q=https://ko-fi.com/ZakyPew "null")
    

## 📦 Installation

1.  Download **`StreamTracker_v1.5.zip`**. Check out the installation video https://youtu.be/giiv7gTtkRo
    
2.  **Unzip** the folder to a permanent location (e.g., Documents/StreamTools).
    
3.  Run `SteamTracker.exe`.
    
4.  Enter your Steam API Key and ID in the Setup Wizard.
    
5.  **Add to OBS:**
    
    -   Add a **Browser Source**.
        
    -   URL: `http://localhost:5000`
        
    -   Width: `600` | Height: `250`
        

### 📱 Vertical Mode (TikTok)

-   **URL:** `http://localhost:5000/?mode=vertical`
    
-   **Dimensions:** Width `350` | Height `600`
    

### 🎛️ Adding the Control Dock

1.  In OBS, go to **Docks** -> **Custom Browser Docks**.
    
2.  Name: `Tracker Control`
    
3.  URL: `http://localhost:5000/dock`
    
4.  Click Apply and snap the window into your layout.
    

## 🛠️ Running from Source

If you prefer running the Python script directly instead of the `.exe`:

1.  **Install Python 3.x**
    
2.  **Install Dependencies:**
    
    ```
    pip install flask flask-cors requests psutil pillow pyinstaller
    
    ```
    
3.  **Run the App:**
    
    ```
    python app.py
    
    ```
    

## 🤝 Contributing

Feel free to submit Pull Requests or open Issues if you find bugs!

**Powered by ZakyPew**

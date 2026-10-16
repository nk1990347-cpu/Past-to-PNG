# 📸 Past-to-PNG (AE-Apps)

> A lightweight, lightning-fast Windows desktop utility packaged as a standalone executable that instantly captures images from your clipboard, saves them into structured local date folders, and manages everything **100% offline**[cite: 1].

<div align="center">

[![Platform: Windows](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)](https://github.com/nk1990347-cpu/Past-to-PNG)
[![Privacy: 100% Offline](https://img.shields.io/badge/Privacy-100%25%20Offline-success?style=for-the-badge&logo=shield)](https://github.com/nk1990347-cpu/Past-to-PNG)
[![Release: Standalone EXE](https://img.shields.io/badge/Release-v1.0.0-orange?style=for-the-badge&logo=github)](https://github.com/nk1990347-cpu/Past-to-PNG/releases/tag/V1.0.0)

</div>

---

## 📥 Quick Download

* **[⬇️ Download `default.exe` (v1.0.0)](https://github.com/nk1990347-cpu/Past-to-PNG/releases/download/V1.0.0/default.exe)**
* **[📦 View All Releases](https://github.com/nk1990347-cpu/Past-to-PNG/releases/tag/V1.0.0)**[cite: 1]

> **Note:** Zero setup or Python installation is required. Simply download the `.exe` file and run it right away[cite: 1]!

---

## ✨ Key Specializations & Features

* **🔒 100% Offline & Private:** Operates entirely on your local Windows machine without sending data, logs, or images to any external cloud service or third-party server[cite: 1].
* **⚡ Standalone EXE:** Fully compiled into a ready-to-run Windows executable—no Python installation or extra dependencies required to run[cite: 1].
* **🖱️ Instant Capture:** Press `Ctrl + V` anywhere on the app window or click the interface to instantly grab and save clipboard graphics (`ImageGrab.grabclipboard()`)[cite: 1].
* **📁 Smart Automated Organization:** Automatically sorts saved `.png` files into structured directories (`Pictures/Pasted Images/DD-MM-YYYY/`) with built-in duplicate prevention counters[cite: 1].
* **🎨 Sleek Dark-Mode GUI:** Custom borderless window design featuring smooth drag-and-drop navigation, custom Alt-Tab window integration, and rich animated toast notifications[cite: 1].
* **🧹 Clipboard Cleanup:** Automatically clears the system clipboard after a successful write operation to keep your workflow clean[cite: 1].

---

## 🛠️ Tech Stack & Build Environment

* **Language/Core:** Python, Tkinter, Pillow (PIL)[cite: 1]
* **Packaging:** PyInstaller (compiled into a standalone `.exe`)[cite: 1]
* **System Integration:** Windows Win32 API (`ctypes`) for window handling and clipboard management[cite: 1]

---

## 🚀 How to Use

1. Download the latest standalone **`default.exe`** from the [Releases Page](https://github.com/nk1990347-cpu/Past-to-PNG/releases/tag/V1.0.0)[cite: 1].
2. Double-click the `.exe` to launch the application[cite: 1].
3. Copy any image or screenshot to your Windows clipboard (`Print Screen`, right-click copy, etc.)[cite: 1].
4. Press **`Ctrl + V`** or click the center download arrow inside the app window[cite: 1].
5. Your image will be saved instantly with an on-screen confirmation toast! Click the path prompt at the bottom of the app to open your destination folder.

Your image is instantly saved locally, and a toast notification confirms the file path. 

Click the bottom path label to instantly open the destination folder in Windows Explorer.   

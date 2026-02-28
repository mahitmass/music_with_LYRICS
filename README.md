# Pro Media Player 🎵

A lightweight, high-performance hybrid music player built with Electron. It seamlessly combines local `.mp3` playback with global online streaming, featuring perfectly synced lyrics and an immersive UI. 

## ✨ Key Features

* **Global Cloud Streaming:** Integrated with the JioSaavn API to instantly search and stream high-quality audio from a library of 80+ million tracks worldwide—no downloads required.
* **Local Drag & Drop:** Easily manage your offline library. Drag and drop individual `.mp3` files or entire folders right into the queue.
* **Smart Synced Lyrics:** Automatically fetches time-synced lyrics via LRCLIB. Includes a smart-fallback that automatically detects native scripts (like Russian, Punjabi, or Greek) and fetches the Romanized English version.
* **In-Place Lyrics Editor:** Missing or incorrect lyrics? Click the "Edit" button to manually type and sync lyrics directly inside the app's UI. Local edits are saved to your hard drive, and online edits are saved to the app's internal memory.
* **Immersive UI:** The app dynamically extracts album art (from local file metadata or online APIs) and generates a beautiful, fluid background blur.
* **Advanced Controls:** * Full support for hardware Media Keys.
  * Arrow key controls (Up/Down for Volume, Left/Right to seek 10 seconds).
  * Trackpad swipe gestures (Swipe left/right to change tracks).

## 🛠️ Tech Stack
* **Framework:** Electron, Node.js
* **Frontend:** Vanilla HTML, CSS, JavaScript
* **APIs Used:** JioSaavn API (for streaming & metadata), LRCLIB (for synced lyrics), jsmediatags (for local album art extraction)

## 📥 Installation (Windows & Mac)

1. Go to the [Releases](../../releases) tab on the right side of this GitHub page.
2. **For Windows:** Download the `music-player Setup 1.0.0.exe` file and run it.
3. **For Mac:** Download the `.dmg` file to install.
4. Enjoy your ad-free, seamlessly synced music!

## ⌨️ Keyboard Shortcuts
| Action | Key / Gesture |
| :--- | :--- |
| **Play / Pause** | `Media Play/Pause` |
| **Next / Prev Track** | `Media Next/Prev` or Trackpad Swipe |
| **Volume Up / Down** | `Arrow Up` / `Arrow Down` |
| **Seek +/- 10s** | `Arrow Right` / `Arrow Left` |

---
*Developed for a seamless, private, and bloat-free listening experience.*

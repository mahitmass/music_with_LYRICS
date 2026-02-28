# 🎵 Pro Media Player

A premium, lightweight desktop music player designed for high-quality local listening with **Synced Lyrics** and **Immersive Visuals**.

---

### 🌟 Overview
Most modern players are either too heavy or hide synced lyrics behind a subscription. This player focuses on:
* **Privacy & Speed**: It plays your local `.mp3` files without tracking your data.
* **Synced Lyrics**: Automatically fetches and perfectly highlights lyrics from the LRCLIB database, including Hindi, Punjabi, and International tracks.
* **Immersive Vibe**: A dedicated full-screen mode that blurs your album art for a cinematic background while you listen.

---

### 🚀 How to Run

#### **Option 1: Standalone Installer (Recommended)**
If you just want to listen to music:
1.  Navigate to the **`dist/`** folder in this repository.
2.  Download **`music-player Setup 1.0.0.exe`**.
3.  Run the installer to add the player to your Start Menu and Desktop.

#### **Option 2: Run from Source (For Developers)**
To modify the code or run via terminal:
1.  **Clone the repository**:
    ```powershell
    git clone [https://github.com/mahitmass/music_with_LYRICS.git](https://github.com/mahitmass/music_with_LYRICS.git)
    cd music_with_LYRICS
    ```
2.  **Install Dependencies**: Recreates the `node_modules` folder.
    ```powershell
    npm install
    ```
3.  **Launch the App**:
    ```powershell
    npm start
    ```

---

### 🛠️ Key Features
* **Smart Drag & Drop**: Drag files from Windows Explorer directly into the queue to insert them at specific positions.
* **Immersive Mode**: Click the song info in the player bar to toggle the full-screen blurred art view.
* **Persistent Queue**: Remembers your songs and last played track even after closing the app.
* **Manual Lyric Sync**: Use `[` and `]` keys to manually adjust lyric timing if a file is slightly out of sync.
* **Interactive Lyrics**: Click any line in the lyrics view to jump the song instantly to that timestamp.

---

### 📦 Technical Stack
* **Electron**: Native Windows shell and desktop integration.
* **JS Media Tags**: For extracting embedded album art directly from your MP3 files.
* **LRCLIB API**: High-quality, open-source synced lyrics database.

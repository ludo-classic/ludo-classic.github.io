# 🎲 Ludo Classic – Multiplayer
A modern, real-time multiplayer implementation of India's favorite board game, Ludo! Built with vanilla JavaScript, HTML, CSS, and powered by Firebase Realtime Database. This project is structured using Jekyll for clean, modular code maintenance.
## ✨ Features
 * **Real-time Multiplayer:** Play smoothly with friends using Firebase Realtime Database.
 * **Multiple Game Modes:** Supports 1v1, 2v2, and Free-For-All (up to 4 players).
 * **Private Rooms:** Create a room and invite friends via a unique Room Code or a directly shareable link.
 * **Interactive UI/UX:**
   * 3D-style rolling dice animation.
   * Smooth token (goti) movement animations.
   * Floating emoji reactions during gameplay.
 * **Audio Feedback:** Includes background music, dice roll sounds, token move sounds, and winning fanfares.
 * **Smart Gameplay Mechanics:**
   * Auto-turn skip if a player disconnects or takes too long (20-second timer).
   * Safe zones (stars) and capturing mechanics exactly like the classic rules.
 * **Responsive Design:** Fully optimized for both desktop and mobile screens.
## 🛠️ Tech Stack
 * **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6 Modules)
 * **Backend/Database:** Firebase Realtime Database (BaaS)
 * **Architecture:** Jekyll (using _includes for modular component management)
## 📂 File Structure
This project uses Jekyll to keep the lobby, win screens, and main board logic separate.
```text
├── _includes/
│   ├── lobby.html
│   └── win.html
├── assets/
│   ├── start-bgm.mp3
│   ├── dice-roll.mp3
│   └── win.mp3
└── index.html

```
## 📧 Contact Developer
For any queries, feedback, or collaboration, feel free to reach out:
 * **Email:** kumarsharma2580@gmail.com

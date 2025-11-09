
# 🎨 Collaborative Canvas — Multi-User Drawing App

## 🧾 Description

Collaborative Canvas is a real-time multi-user drawing app built with **Node.js**, **Express**, **Socket.io**, and **HTML5 Canvas**.
It lets multiple users draw together on a shared canvas with instant synchronization, live cursor tracking, undo/redo, and touch support — perfect for creative teamwork and learning real-time web technologies.


🚀 Quick Start

1. Clone the repository

   ```bash
   git clone https://github.com/utkarshaman13/collaborative-canvas.git
   cd collaborative-canvas
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Start the server

   ```bash
   npm start
   ```

4. Open your browser

   ```
   http://localhost:3000
   ```


 ✨ Features

 🖊️ Real-time multi-user drawing
 👥 See who’s online
 🖱️ Live cursor tracking
 ↩️ Global undo/redo
 📱 Touch support (mobile-friendly)
 ⚡ Fast and lightweight performance

🧪 Test Multi-User Drawing

1. Start the server using `npm start`
2. Open `http://localhost:3000` in multiple browser tabs
3. Enter different usernames
4. Draw on one tab — see it update instantly in all others!

 📁 Project Structure

collaborative-canvas/
├── client/          
│   ├── index.html       # Includes socket.io client
│   ├── style.css
│   ├── canvas.js
│   ├── websocket.js
│   └── main.js
├── server/          
│   └── server.js
├── package.json
└── README.md

📝 License

MIT License — free to use, modify, and distribute.

Would you like me to make this README **GitHub-styled with emojis and color formatting (Markdown badges, headers, etc.)** or keep it **simple and report-style** (for documentation or college submission)?

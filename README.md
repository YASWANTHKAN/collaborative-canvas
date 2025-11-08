# 🎨 Real-Time Collaborative Canvas

A **multi-user, real-time drawing application** built with **Node.js** and **vanilla JavaScript**. It allows multiple users to draw on the same canvas simultaneously, view each other’s cursors, and share a **global undo/redo history** — all synchronized in real time.

This project showcases mastery of the **HTML5 Canvas API**, **vanilla JavaScript (ES6)**, and **real-time state synchronization** using **WebSockets**.

---

## 🚀 Live Demo

🔗 **Try it here:** [https://collaborative-canvas-vw5y.onrender.com/](https://collaborative-canvas-vw5y.onrender.com/)

---

## ✨ Core Features

* **🖊️ Real-Time Sync** — Drawings appear instantly on all connected clients.
* **🎨 Drawing Tools** — Brush and eraser tools supported.
* **⚙️ Tool Properties** — Custom colors and adjustable stroke width.
* **🖱️ Live User Cursors** — See other users’ cursor positions with unique colors.
* **👥 User List** — Displays all currently connected users in real time.
* **♻️ Global Undo/Redo** — Server-authoritative undo/redo shared by all users.
* **📱 Mobile/Touch Support** — Works seamlessly on touch devices.

---

## 🧰 Tech Stack

| Component       | Technology                                          |
| --------------- | --------------------------------------------------- |
| **Backend**     | Node.js, Express, Socket.io                         |
| **Frontend**    | Vanilla JavaScript (ES6 Classes), HTML5 Canvas, CSS |
| **Development** | Nodemon for live server reload                      |

---

## ⚙️ Setup & Running

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Run in Development Mode

(Uses `nodemon` for live reload)

```bash
npm run dev
```

### 3️⃣ Run in Production Mode

```bash
npm start
```

### 4️⃣ Access the App

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🧪 Testing Multi-User Features

1. Start the server using one of the above commands.
2. Open [http://localhost:3000](http://localhost:3000) in **two or more** browser windows or tabs.
3. Observe:

   * The **“Online” list** in both windows should display *You* and *User XXXX*.
   * Drawing in one window appears **instantly** in the others.
   * Each user’s **cursor** is visible in the other windows.
   * Clicking **Undo** in one window undoes the last action **for all users**.
   * Clicking **Redo** reapplies the action **for all users**.

---

## ⚠️ Known Limitations

* **Single Room:** Currently hard-coded to one default room. Backend supports multiple rooms, but the client UI doesn’t expose room creation/joining.
* **No Persistence:** Drawing history is stored **in-memory**. Restarting the server clears all drawings.
* **Clear is Final:** The *Clear* button wipes all drawings and history permanently — not undoable.

---

## ⏱️ Time Spent on Project

**Approximately:** 12 hours

Would you like me to also reformat your **ARCHITECTURE.md** file in the same professional style next?

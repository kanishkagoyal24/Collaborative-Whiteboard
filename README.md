Click on the link to run the Deployed WebApp:https://collaborative-whiteboard-orpin.vercel.app/

Video Demonstration Link: https://drive.google.com/file/d/1Dt6VICqZTyueVH1M9GjmsBtRQO0RkgeW/view?usp=drive_link
# 🧑‍🎨 Collaborative Whiteboard

**Collaborative Whiteboard** is a real-time, browser-based canvas app enabling multiple users to sketch, draw shapes, add text, and co-create visually — simultaneously. It leverages **React**, **Fabric.js**, and **Socket.IO** to deliver smooth, multi-user collaboration.

---

## 📝 Overview

This digital whiteboard platform is built for teams, educators, designers, or anyone who wants to visually collaborate in real-time.

**Core Capabilities:**

* Join or host custom rooms
* Draw freely or use shapes and text tools
* Instantly see others’ contributions
* Control user permissions (editor/viewer mode)

---

## ✨ Features

### 👥 User & Room Management

* Set custom usernames
* Create and join rooms (public/private)
* Password-protected access
* Role-based permissions (view-only or editor)
* Live user presence and roles

### 🎨 Drawing Tools

* Pen tool with customizable color and stroke
* Eraser functionality
* Rectangle and circle drawing
* Text input and editing
* Object selection and manipulation

### 🔁 Real-time Collaboration

* Synchronized drawings across all users
* Live path rendering and object updates
* Instant canvas clearing
* Real-time notifications for joining/leaving users

### 📦 Export Options

* Download canvas as **PNG**, **JPEG**, or **PDF**
* Save/load drawings as **JSON** for future editing

---

## 🧰 Tech Stack

### Frontend

* ⚛️ React (with Hooks)
* 🖼️ Fabric.js for canvas management
* 🔌 Socket.IO (client-side)
* 🎨 CSS3 (Minimal pastel theme)
* ⚡ Vite for rapid development

### Backend

* 🟢 Node.js with Express
* 🌐 Socket.IO server
* 🔐 CORS enabled for cross-origin support

---

## 🚀 Getting Started

### 📋 Requirements

* Node.js v14 or higher
* npm or yarn
* Modern browser (WebSocket-enabled)

---

### ⚙️ Backend Setup

```bash
cd whiteboard-backend
npm install
node index.js
```

> Runs on: `http://localhost:10000`

---

### 🧑‍💻 Frontend Setup

```bash
cd whiteboard-frontend
npm install
npm run dev
```

> Default app URL: `http://localhost:5173`

> ⚠️ Make sure the Socket.IO URL in `WhiteboardApp.jsx` matches your backend:

```js
const socket = io('http://localhost:10000', {
  transports: ['websocket'],
  withCredentials: true
});
```

---

## 📂 Running the Full Stack

In two terminals:

**Terminal 1 (Backend):**

```bash
cd whiteboard-backend
node index.js
```

**Terminal 2 (Frontend):**

```bash
cd whiteboard-frontend
npm run dev
```

Then, open your browser at:
👉 [http://localhost:5173](http://localhost:5173)

---

Let me know if you'd like this in `README.md` format or need a version with screenshots or badges!

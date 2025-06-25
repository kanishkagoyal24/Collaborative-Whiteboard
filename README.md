🎨 Collaborative Whiteboard
A real-time collaborative whiteboard app built with React, Node.js, Socket.io, and Fabric.js. Collaborate with others in a shared drawing environment using powerful tools and live synchronization.

🚀 Features
🖍️ Live Drawing — Multiple users can draw simultaneously on a shared canvas.

🏠 Room System — Create or join rooms with optional password protection.

✏️ Drawing Tools — Pen, eraser, text, rectangles, circles, and more.

🔐 User Permissions — Set users as editors or view-only.

💾 Export Options — Save your canvas as PNG, JPEG, PDF, or JSON.

↩️ Undo/Redo — Basic undo/redo support for drawing actions.

📦 Requirements
Node.js v14 or higher

npm

🔧 Getting Started
🛠 Backend Setup
Navigate to the backend folder:

bash
Copy
Edit
cd backend
Install dependencies:

bash
Copy
Edit
npm install express socket.io cors
Start the backend server:

bash
Copy
Edit
node index
The backend will run at http://localhost:4000

🎨 Frontend Setup
Navigate to the frontend folder:

bash
Copy
Edit
cd frontend
Install dependencies:

bash
Copy
Edit
npm install react react-dom socket.io-client fabric
npm install -D vite @vitejs/plugin-react
Start the frontend dev server:

bash
Copy
Edit
npm run dev
The frontend will be available at http://localhost:5173

📚 Tech Stack
Backend
express — Web server

socket.io — WebSocket communication

cors — Enable cross-origin requests

Frontend
react / react-dom — UI rendering

socket.io-client — Real-time communication

fabric — Canvas rendering and manipulation

vite — Fast dev server & bundler

@vitejs/plugin-react — React plugin for Vite

🧪 How to Use
Open your browser at: http://localhost:5173

Enter your name to register

Create a room or join an existing one

Start drawing and collaborate in real-time!

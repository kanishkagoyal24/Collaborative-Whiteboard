Collaborative Whiteboard – Real-Time Drawing Application
The Collaborative Whiteboard is a web-based application that enables multiple users to draw and interact on a shared canvas in real-time. Built using React, Node.js, Socket.io, and Fabric.js, this tool is designed for seamless collaboration and efficient team brainstorming or creative work.

Key Highlights
Live Multi-User Collaboration: Multiple users can draw on the canvas simultaneously, with real-time updates.

Room-Based Management: Users can create or join rooms, each optionally secured with a password.

Comprehensive Drawing Tools: Includes pen, eraser, text, and shape tools such as rectangles and circles.

User Access Control: Differentiates between editing and view-only permissions for better room management.

Export Options: Supports exporting the whiteboard in PNG, JPEG, PDF, and JSON formats.

Undo/Redo Functionality: Basic undo and redo operations to correct mistakes quickly.

System Requirements
Node.js (version 14 or above)

npm (Node Package Manager)

Project Setup
Backend Setup
Navigate to the backend directory.

Install required dependencies:

lua
Copy
Edit
npm install express socket.io cors
Start the backend server:

perl
Copy
Edit
node index
Server runs at: http://localhost:4000

Frontend Setup
Navigate to the frontend directory.

Install dependencies:

nginx
Copy
Edit
npm install react react-dom socket.io-client fabric
npm install -D vite @vitejs/plugin-react
Start the frontend development server:

arduino
Copy
Edit
npm run dev
Application runs at: http://localhost:5173

Technology Stack
Frontend: React, Vite, Fabric.js, Socket.io-client

Backend: Express.js, Socket.io, CORS

How to Use
Launch the frontend at http://localhost:5173.

Enter a username to register.

Create a new room or join an existing one.

Begin drawing and collaborating with other users in real-time.

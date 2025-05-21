# Collaborative-code-editor
Code Together

Project Description
Code Sync is a real-time collaborative code editor. It enables multiple users to write, edit, and view code simultaneously from different devices. This project uses Node.js, Express.js, and Socket.io to create seamless WebSocket-based communication between clients.

✨ Features
🔄 Real-Time Sync: Instant code updates across all connected clients.

🔗 Room-based Sessions: Users can join the same room using a shared Room ID.

🧠 Socket.io Powered: Handles real-time bi-directional communication.

🖥 User-Friendly Interface: Clean and responsive interface for ease of use.

🧰 Tech Stack
Frontend: HTML5, CSS3, JavaScript

Backend: Node.js, Express.js

Real-Time Communication: Socket.io

📁 Folder Structure
csharp
Copy
Edit
Code-Sync/
│
├── client/               # Frontend files
│   ├── index.html
│   └── style.css
│
├── server/               # Backend logic
│   └── index.js
│
├── public/               # Public assets
│
├── package.json          # Node dependencies
└── README.md             # Project documentation
🚀 How to Run Locally
Prerequisites
Node.js installed on your system.

Steps
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/code-sync.git
cd code-sync
Install Dependencies

bash
Copy
Edit
npm install
Start the Application

bash
Copy
Edit
npm start
Access the App

Open your browser and go to:
http://localhost:3000

You can open the link in multiple tabs or different devices to test real-time collaboration.

🧪 How It Works
Each user enters a username and a room ID.

If the room ID already exists, they join the ongoing session.

All users in a room will see live code updates instantly as others type.

Communication is handled through Socket.io WebSockets.

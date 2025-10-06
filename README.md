✅ MERN Stack Todo App 📋

A simple yet powerful full-stack Todo application built using the MERN Stack — helping users efficiently manage daily tasks with a clean, modern, and responsive interface.

🌐 Live Demo

🚀 View Live Project
 (https://mern-todofy.netlify.app/)

💡 About the Project

This Todo App is a full-stack CRUD application (Create, Read, Update, Delete) that lets users:

Add new tasks 📝

Edit existing tasks ✏️

Mark tasks as completed ✅

Delete tasks 🗑️

Built with the MERN stack (MongoDB, Express.js, React.js, Node.js), it provides a seamless user experience and fast performance.

🛠️ Tech Stack
Frontend (Client):

⚛️ React.js – For building the dynamic user interface

🎨 HTML, CSS – For structure and styling

🌈 TailwindCSS – For rapid, modern UI design

Backend (Server):

🟢 Node.js – JavaScript runtime environment

🚀 Express.js – Web framework for RESTful APIs

🧩 Mongoose – ODM library for MongoDB

Database:

🍃 MongoDB – NoSQL database to store todos

📂 Project Structure
Todo-app/
├── client/                      # Frontend React application
│   ├── public/
│   ├── src/                     # Source code
│   │   └── App.jsx
│   ├── .env                     # Frontend environment variables
│   ├── index.css                # Global styles
│   ├── index.html               # HTML entry point
│   └── main.jsx                 # React entry point
│
└── server/                      # Backend Node.js + Express.js
    ├── controllers/             # Request handlers
    ├── models/                  # Mongoose schemas
    ├── routes/                  # API route definitions
    ├── .env                     # Backend environment variables
    └── index.js                 # Server entry point

⚙️ Prerequisites

Before running this project, make sure you have:

🧠 Basic knowledge of MongoDB, Express.js, React.js, Node.js

⚙️ Installed Node.js and npm

🍃 A running instance of MongoDB (local or Atlas)

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/basu57/Todo-app.git

2️⃣ Go to the Project Directory
cd Todo-app

3️⃣ Install Dependencies
Install frontend dependencies
cd client
npm install

Install backend dependencies
cd ../server
npm install

4️⃣ Set Up Environment Variables

Create a .env file inside the server folder with the following keys:

MONGO_URI=your_mongodb_connection_string
PORT=5000


(Optional) Create a .env file inside client if needed for environment configuration.

5️⃣ Run the Application
Start the Backend (from /server):
npm run start

Start the Frontend (from /client):
npm run dev


Now open your browser and visit:

🌍 Frontend: http://localhost:3000

⚙️ Backend: http://localhost:5000

🧑‍💻 Contributing

Contributions are always welcome! 🎉
If you’d like to help improve the project:

Fork this repository

Create a new branch (feature-new)

Make your changes

Submit a pull request

Your contributions will make this project even better ❤️

📝 Task Manager App – Backend

A simple Task Manager backend built with Node.js, Express, and MongoDB Atlas.
Includes user authentication using JWT and full CRUD operations for tasks.

🌐 Live API
Backend Live URL: https://task-manager-backend-1-57jc.onrender.com

🔧 Tech Stack

Node.js

Express

MongoDB Atlas

JWT (Authentication)

Mongoose

dotenv

CORS

✅ Features

User Sign Up & Login

JWT-based Authentication

Add, Edit, Delete Tasks

Mark Tasks as Completed or Pending

REST API structure with clear routes

📁 Project Structure

task-manager-backend/
├── controllers/
├── models/
├── routes/
├── .env
├── server.js
└── package.json

🔐 .env Configuration

Create a .env file in the root folder and add:

PORT=5000  
MONGO_URI=mongodb+srv://n190974_db_user:M2n3hR479jI4u9kO@cluster0.nxqi7yb.mongodb.net/taskdb?retryWrites=true&w=majority  
JWT_SECRET=9vK2@hF3!u4PxZt6LmRq  


🚀 How to Run Locally

Clone the repository:
git clone https://github.com/hariramuu/task-manager-backend.git

Navigate into the project:
cd task-manager-backend

Install dependencies:
npm install

Add the .env file (as shown above)

Start the server:
npm start

Server will run on http://localhost:5000

🔗 API Endpoints

Auth Routes

POST /api/auth/register – Register a new user

POST /api/auth/login – Login and get token

Task Routes (Protected)

GET /api/tasks – Get all tasks

POST /api/tasks – Add a new task

PUT /api/tasks/:id – Update a task

DELETE /api/tasks/:id – Delete a task

Use this in headers for protected routes:
Authorization: Bearer <your_token>

📽️ Demo Video
https://www.loom.com/share/b16e2ef8ad1c426caa676e21926f658c

🙋‍♂️ Author

Dampetla Hari
GitHub: https://github.com/hariramuu

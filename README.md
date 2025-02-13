# MERN Stack ToDo App

A full-stack **ToDo App** built using the **MERN (MongoDB, Express, React, Node.js) stack**. This application allows users to create, update, delete, and mark tasks as completed.

## Features
- Add new tasks
- Edit existing tasks
- Mark tasks as complete/incomplete
- Delete tasks
- User authentication (JWT-based login/signup)
- Responsive UI

## Tech Stack
- **Frontend**: React.js, React Router, Axios, Bootstrap/Tailwind
- **Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT Authentication
- **Database**: MongoDB (Atlas/local)

## Installation & Setup

### Prerequisites
Make sure you have the following installed:
- **Node.js** (>=14.x)
- **MongoDB** (local or Atlas)
- **Git**

### Clone the Repository
```sh
git clone https://github.com/Ritvik-22/Todo_App
cd todo-app-mern
```

### Backend Setup
```sh
cd backend
npm install
```

#### Configure Environment Variables
Create a `.env` file in the **backend** folder and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

#### Start Backend Server
```sh
npm start
```
The server will run at `http://localhost:5000`

### Frontend Setup
```sh
cd ../frontend
npm install
```

#### Start Frontend Server
```sh
npm start
```
The React app will be running at `http://localhost:3000`

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | `/api/users/register` | Register a new user |
| POST   | `/api/users/login` | Login user & get token |
| GET    | `/api/todos` | Fetch all todos |
| POST   | `/api/todos` | Create a new todo |
| PUT    | `/api/todos/:id` | Update a todo |
| DELETE | `/api/todos/:id` | Delete a todo |

## Screenshots
(Add relevant screenshots here)

## Contributing
Pull requests are welcome! Please follow best practices and submit changes for review.

## License
This project is licensed under the **MIT License**.

---
Feel free to modify this README to fit your specific app details.


# Good Notes

Good Notes is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The app allows users to register, login, and manage their personal notes. After successful login or registration, users can create, update, delete, and search for notes. Additionally, users can log out securely from the app.

## Features

- User registration and login functionality with JWT authentication
- CRUD (Create, Read, Update, Delete) operations for managing notes
- Search functionality to find particular notes by keywords
- Secure logout functionality
- User-friendly interface with React.js
- Backend powered by Express.js and MongoDB for database storage

## Tech Stack

- **Frontend:** React.js, React Router, Redux, Axios
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JSON Web Token (JWT), bcryptjs for password hashing
- **Database:** MongoDB (Mongoose ORM)
- **Styling:** CSS, TailwindCSS

## Installation

### Prerequisites

Make sure you have the following installed:

- Node.js
- MongoDB (local or cloud MongoDB Atlas instance)
- npm or yarn

### Clone the repository

```bash
clone this repo
```

### Backend Setup
 ####Navigate to the backend directory:
```bash
cd backend
```

### Install dependencies:
```bash
npm install
```

### Create a .env file in the backend folder and add the following environment variables:
```bash
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

### Start the backend server:
```bash
npm run start
```

### The backend server will start on http://localhost:5000.

### Frontend Setup
### Navigate to the frontend directory:
```bash
cd frontend
```

### Install frontend dependencies:
```bash
npm install
```
### Start the frontend development server:
```bash
npm start
```

###The frontend will be running on http://localhost:3000.

## Usage
## Registration and Login
  ### Open the app in your browser at http://localhost:3000.
  ### Register a new account by providing your username, email, and password.
  ### Once registered, you can log in using your credentials.
  ### Notes CRUD Functionality
  ### After logging in, you will be redirected to the notes dashboard.
  ### You can perform the following operations on notes:
  ### Create: Add new notes by clicking the "Add Note" button.
  ### Read: View your existing notes.
  ###   ### Update: Edit existing notes by clicking the "Edit" button.
  ### Delete: Remove notes by clicking the "Delete" button.
  ### Search Functionality
  ### Use the search bar at the top of the notes dashboard to find a note by typing in a keyword.
  
## Logout
### Click on the "Logout" button in the top navigation bar to securely log out of your account.


# Netflix Clone - MERN Stack

Welcome to the Netflix Clone project built using the MERN (MongoDB, Express, React, Node.js) stack. This project replicates the core functionality of Netflix, including video streaming, user authentication, and more. It's a great full-stack project that demonstrates how to build a video streaming platform from scratch.

## 📖 Project Overview

This project is a clone of Netflix that allows users to:

- Browse movie and TV show categories
- Watch trailers and video content
- Sign up and log in securely using JWT authentication
- View personalized recommendations based on preferences (future feature)

The frontend is built using React, styled with CSS, and leverages Redux for state management. The backend is powered by Node.js and Express, and the database is MongoDB.

## 🛠️ Technologies Used

### Frontend:
- **React.js** - For building dynamic user interfaces
- **Redux** - For state management across the app
- **Axios** - For API requests
- **React Router** - For navigation and routing between pages
- **CSS** - For styling the application

### Backend:
- **Node.js** - For server-side logic
- **Express.js** - For handling API requests and server routes
- **MongoDB** - For storing user data and video information
- **JWT (JSON Web Token)** - For secure user authentication

### Other Tools:
- **MongoDB Atlas** - Cloud database for MongoDB

## 🚀 Features

- **User Authentication:** Sign up, log in, and log out functionality using JWT.
- **Movie & TV Show Browsing:** Explore and browse movies and shows by category.
- **Video Streaming:** Play trailers and video content within the app.
- **Responsive Design:** Works seamlessly across all devices.

## 📂 Folder Structure

The repository is organized as follows:

```
/netflix-clone
    ├── /frontend (React code)
    └── /backend (Node.js and Express code)
```

### Frontend Structure:

```
/frontend
    ├── /src
    │   ├── /components (Reusable components)
    │   ├── /pages (All pages such as Home, Login, etc.)
    │   ├── /hooks (hooks for fatching data from backend)
    │   ├── /store (Auth store )
    │   └── /utils (Helper functions and API calls)
    └── package.json (Frontend dependencies)
```

### Backend Structure:

```
/backend
    ├── /config (Database connection settings)
    ├── /controllers (Logic for routes)
    ├── /models (MongoDB models for users, videos, etc.)
    ├── /routes (API routes)
    ├── /middlewares (JWT authentication middleware)
    ├── /services (Easy to fatch data from API )
    ├── /utils (Generate Token And Set Cookie )
    └── package.json (Backend dependencies)
```

## 📦 Installation Instructions

### Prerequisites:

Ensure you have the following installed on your local machine:

- **Node.js**
- **MongoDB Atlas** (or use MongoDB)
- **Git**
- **VSCode** (or any code editor)

### Steps to Install and Run Locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-clone.git
   cd netflix-clone
   ```

2. **Install Dependencies:**
   - Installing
     ```shell
      npm run build
      ```

   - Install frontend dependencies:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set Up Environment Variables:**
   - In the `main` folder, create a `.env` file and add your environment variables:
     ```
     MONGO_URI=your-mongodb-atlas-uri
     JWT_SECRET=your-secret-key
     ```

4. **Run the Development Servers:**
   - Run the backend server:
     ```bash
     cd backend
     npm run dev
     ```
   - Run the frontend server:
     ```bash
     cd frontend
     npm start
     ```

5. **Access the App:**
   Open your browser and go to `http://localhost:5173`.

## 📝 API Endpoints

### Auth Routes:
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login a user and receive a JWT token

### User Routes:
- `GET /api/users/me` - Get logged-in user information

## 🛠️ Key Dependencies

### Frontend:
- React.js
- Redux
- Axios
- React Router DOM

### Backend:
- Express.js
- MongoDB/Mongoose
- JWT
- bcrypt.js

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request with any improvements.

## 📧 Contact

If you have any questions, feel free to reach out:

- **Email:** vanshbdobariya1312@gmail.com
- **GitHub:** [Vansh Dobariya](https://github.com/VanshBD)

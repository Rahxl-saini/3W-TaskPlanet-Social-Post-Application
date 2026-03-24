# 3W-TaskPlanet-Social-Post-Application

# 🚀 Mini Social Post Application

A full-stack social media application where users can create accounts, post content, and interact with others through likes and comments — inspired by the TaskPlanet Social Feed.

---

## 📌 Features

### 👤 Authentication
- User Signup & Login (Email & Password)
- Secure password storage using bcrypt
- JWT-based authentication

### 📝 Create Post
- Users can create posts with:
  - Text 📝
  - Image 🖼️
  - Or both
- At least one field is required

### 🌍 Public Feed
- View posts from all users
- Displays:
  - Username
  - Post content (text/image)
  - Likes count ❤️
  - Comments count 💬

### ❤️ Like & 💬 Comment
- Like/unlike posts
- Add comments on posts
- Stores usernames of users who liked/commented
- Real-time UI updates

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Material UI (MUI)
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### Deployment
- Frontend: Vercel / Netlify
- Backend: Render
- Database: MongoDB Atlas

---

## 📂 Project Structure

project-root/
│
├── backend/ # Node.js + Express API
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ └── server.js
│
├── frontend/ # React App
│ ├── src/
│ └── public/
│
└── README.md


---

# 🔗 API Endpoints (Sample)
Auth
POST /api/auth/signup
POST /api/auth/login
Posts
POST /api/posts
GET /api/posts
PUT /api/posts/:id/like
POST /api/posts/:id/comment

# 🌐 Deployment Links
https://threew-taskplanet-social-post-wfvy.onrender.com

# 🎯 Assignment Objective

This project was built as part of a Full Stack Internship Assignment to demonstrate:

Full-stack development skills
REST API design
Authentication & authorization
Database design (MongoDB)
UI/UX inspired by real-world application

# 👨‍💻 Author

Rahul Saini

GitHub: https://github.com/Rahxl-saini

LinkedIn: https://www.linkedin.com/in/rahul-saini2522/
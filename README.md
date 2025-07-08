# MERN Blog Application

[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19866356&assignment_repo_type=AssignmentRepo)

This is a full-stack blog application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It features user authentication, blog post creation with image uploads, commenting functionality, and protected routes.

---

## Features

- User registration and login with JWT authentication  
- Create, read, update, and delete (CRUD) blog posts  
- Upload images to blog posts  
- Comment on blog posts: add, edit, delete comments  
- Protected routes: only logged-in users can create/edit/delete posts and comments  
- Responsive design for desktop and mobile  
- Clean and modern UI using Tailwind CSS  

---

## Project Structure

mern-blog/  
├── client/                 # React front-end  
│   ├── public/             # Static files  
│   ├── src/                # React source code  
│   │   ├── components/     # Reusable components  
│   │   ├── pages/          # Page components  
│   │   ├── hooks/          # Custom hooks  
│   │   ├── services/       # API service functions  
│   │   ├── context/        # React context providers  
│   │   └── App.jsx         # Main app component  
│   └── package.json        # Client dependencies  
├── server/                 # Express.js back-end  
│   ├── config/             # Configuration files  
│   ├── controllers/        # Route controllers  
│   ├── models/             # Mongoose models  
│   ├── routes/             # API routes  
│   ├── middleware/         # Custom middleware  
│   ├── utils/              # Utility functions  
│   ├── server.js           # Main server file  
│   └── package.json        # Server dependencies  
└── README.md               # Project documentation  

---

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)  
- MongoDB instance (local or cloud e.g. MongoDB Atlas)  

### Installation

1. Clone the repository

```bash
git clone <your-repo-url>
cd mern-blog

2.Install dependencies for both client and server

pnpm install
pnpm --filter client install
pnpm --filter server install

3.Create .env files in both /server and /client (if needed) with environment variables

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

4.Run the development servers concurrently

pnpm run dev

Frontend will run on http://localhost:5173/ (Vite default)
Backend will run on http://localhost:5000/

## Usage
Register a new user or login with existing credentials

Create new blog posts with optional image upload

View list of blog posts on the Home page

Click a blog post title to view details and comments

Add, edit, and delete comments on posts

Edit or delete your own blog posts

Technologies Used
React.js with React Router and Tailwind CSS

Node.js with Express.js

MongoDB with Mongoose ODM

JWT for authentication

Axios for HTTP requests

Nodemon and concurrently for developmen

Future Improvements
Add pagination or infinite scroll to blog list

Enable rich text editing for blog content

Enhance image upload with progress bar

Add user profiles and avatar uploads

Deploy to cloud hosting platforms

📸 Screenshots
Homepage


Blog Detail Page


Blog with Comment


Login Page


Homepage View 2


Author
Derrick Swaka

Thank you for checking out my MERN blog app! Feel free to reach out for any questions.
Email: derrickswaka910@gmail.com

Resources
MongoDB Documentation

Express.js Documentation

React Documentation

Node.js Documentation

Mongoose Documentation
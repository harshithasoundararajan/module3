# BlogSpace - Blog Management Web Application

BlogSpace is a simple full-stack blog application built using HTML, CSS, JavaScript, Node.js, Express.js, Mongoose, and MongoDB.

## Features

- User Registration
- User Login
- Password hashing using bcrypt
- Create blog posts
- View all blogs
- View individual blog details
- Store users and blogs in MongoDB
- Responsive frontend

## Technologies Used

### Frontend

- HTML
- CSS
- JavaScript
- Live Server

### Backend

- Node.js
- Express.js
- REST API
- Mongoose
- bcryptjs
- CORS
- dotenv

### Database

- MongoDB

## Project Structure

```text
codomax/
│
├── backend/
│   ├── models/
│   │   ├── user.js
│   │   └── blog.js
│   ├── .env
│   ├── package.json
│   └── server.js
│
└── frontend/
    ├── index.html
    ├── login.html
    ├── register.html
    ├── dashboard.html
    ├── create.html
    ├── blog-details.html
    ├── app.js
    └── style.css

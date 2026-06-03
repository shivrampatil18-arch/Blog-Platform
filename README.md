# BlogSphere - Blog Platform with Comments

## Project Overview

BlogSphere is a full-stack blogging platform that allows users to register, log in, create blog posts, and interact through comments. The platform is built using HTML, CSS, JavaScript, Node.js, Express.js, and MySQL.

---

## Features

### User Authentication
- User Registration
- User Login
- JWT Authentication
- Secure Password Hashing using bcrypt

### Blog Management
- Create Blog Posts
- View All Posts
- View Single Post
- Edit Posts
- Delete Posts

### Comment System
- Add Comments
- View Comments
- Manage User Discussions

### Responsive Design
- Clean UI
- Mobile-Friendly Layout
- Easy Navigation

---

## Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MySQL

### Authentication
- JSON Web Token (JWT)
- bcryptjs

---

## Project Structure

blog-platform/

├── config/

│ └── db.js

├── routes/

│ ├── auth.js

│ ├── posts.js

│ └── comments.js

├── index.html

├── login.html

├── register.html

├── post.html

├── style.css

├── app.js

├── server.js

├── database.sql

├── package.json

└── README.md

---

## Database Setup

### Create Database

```sql
CREATE DATABASE blog_platform;

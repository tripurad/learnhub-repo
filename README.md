# learnhub-repo
📚 LearnHub – Online Learning Platform Using MERN
📌 Table of Contents

- Introduction
- Features
- Tech Stack
- Project Structure
- Installation & Setup
- User Roles
- Milestones
- Project Demo

🧩 Introduction
LearnHub is a full-stack web application designed to deliver interactive online education. It supports learners and educators with features like course management, progress tracking, certification, and role-based access. Built using the MERN stack, LearnHub ensures a seamless and flexible learning experience.
🔑 Features
🎯 General
- Browse and filter courses by name, category, or difficulty
- Enroll in free or paid courses
- Track learning progress and continue from where you left
- Download course completion certificates
👩‍🏫 Instructor Features
- Add, update, and delete courses
- Create sections and manage course content
🛡️ Admin Panel
- Manage users (students, teachers)
- Monitor course listings and platform activity
🧱 Tech Stack
Frontend:
- React.js
- Axios
- Bootstrap, Material UI, Ant Design, MDB UI Kit
Backend:
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Multer (file uploads)
- dotenv, cors, bcryptjs, nodemon
📂 Project Structure

learnhub/
├── frontend/        # React UI
└── backend/         # Express + MongoDB + API logic

🛠️ Installation & Setup
**Prerequisites**
- Node.js & npm: https://nodejs.org/
- MongoDB: https://www.mongodb.com/
- Git: https://git-scm.com/
- Code editor (e.g., VS Code)
**Clone the Project**
```    
git clone <repository-url>
cd learnhub
```
https://github.com/tripurad/learnhub-repo.git


**Install Frontend Dependencies**
```
cd frontend
npm install
```
**Install Backend Dependencies**
```
cd ../backend
npm install
```
**Run the Application**
```
# In frontend
npm run dev

# In backend
npm start
```
**Visit the App**
http://localhost:5172
🔐 User Roles
👨‍🎓 Student:
- Register/login
- Enroll in courses (free/paid)
- Track progress and access course materials
- Download certificate upon course completion
👩‍🏫 Teacher:
- Upload new courses
- Add sections and manage course content
- Remove inactive courses
🛠 Admin:
- Manage user roles and activity
- Edit/remove any course
- View all enrolled students and courses
⏱️ Milestones
Milestone 1: Setup & Configuration
- Created frontend and backend folders
- Installed tools (vite, express, cors, dotenv, mongoose, multer, jwt, nodemon)
Milestone 2: Backend Development
- Setup Express server and environment variables
- Added authentication middleware (`authMiddleware.js`)
Milestone 3: Database Integration
- Configured MongoDB connection with mongoose
- Defined schema models in `/models`
Milestone 4: Frontend Development
- Built UI using React, Axios, Bootstrap, MUI
- Connected to backend APIs
Milestone 5: Project Implementation
- Final testing and UI enhancements
- Functional dashboards for Admin, Teacher, Student
🚀 Project Demo
🎬 Demo Video: https://drive.google.com/file/d/1ijav4VUrWqTayZ8RG3QuwzDagu0uIIMp/view?usp=drive_link
📦 Code Drive: https://github.com/tripurad/learnhub-repo/tree/main/Project%20Files
📝 License
This project is open-source and free to use for educational purposes.

Screenshots:
![Image](https://github.com/user-attachments/assets/ae89aa80-2ea7-4dbc-9b8b-5bb56d679fd9)


![image](https://github.com/user-attachments/assets/9e3e0531-2a40-4ce7-830c-7bebf6238ae2)


Ok![image](https://github.com/user-attachments/assets/3b9e5499-28b2-4d81-91ea-6ffedae638ec)


![image](https://github.com/user-attachments/assets/ce75c583-a888-4c43-b25e-6af3d3c6ca56)


![image](https://github.com/user-attachments/assets/9eb2b9c0-00a9-47ea-9686-0c9b5128ee50)


![image](https://github.com/user-attachments/assets/d45563ce-c0d0-4065-bffc-82aec1deb1b3)


![image](https://github.com/user-attachments/assets/c3d0126b-9762-4c72-a891-9f30fb0c8390)


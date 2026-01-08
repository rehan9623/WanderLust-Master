# 🌍 WanderLust

WanderLust is a full-stack travel web application that allows users to explore, add, edit, and manage travel destinations.  
The project follows the **MVC architecture** and is built using modern web technologies.

---

## ✨ Features

- 🏡 Browse travel destinations  
- ➕ Add new travel listings  
- ✏️ Edit & delete listings  
- 👤 User authentication & authorization  
- 🖼 Image upload with cloud storage  
- 📍 Location-based destination handling  
- ⚙️ Clean MVC project structure  

---

## 🛠 Tech Stack

- **Backend:** Node.js, Express.js  
- **Frontend:** EJS, HTML, CSS, JavaScript  
- **Database:** MongoDB, Mongoose  
- **Authentication:** Passport.js  
- **Cloud Storage:** Cloudinary  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure

WanderLust-Master
│
├── controllers/ # Application logic
├── models/ # Database schemas
├── routes/ # Express routes
├── views/ # EJS templates
├── public/ # Static files (CSS, JS, images)
├── utils/ # Helper utilities
├── init/ # Database initialization
│
├── app.js # Main server file
├── schema.js # Validation schemas
├── middlewares.js # Custom middlewares
├── cloudConfig.js # Cloudinary configuration
├── package.json
├── package-lock.json
├── .gitignore
└── README.md

---

## 🚀 Getting Started

### 🔹 Prerequisites

Make sure you have installed:
- Node.js
- MongoDB
- Git

---

### 🔹 Installation Steps

1. Clone the repository
   ```bash
   git clone https://github.com/rehan9623/WanderLust-Master.git
2. Navigate to the project directory

cd WanderLust-Master

3. Install dependencies

npm install

---

🔐 Environment Variables

- Create a .env file in the root directory and add:

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MONGO_URL=your_mongodb_connection_string
SESSION_SECRET=your_secret_key

--- 

▶️ Run the Application

Using Node:

node app.js


Using Nodemon:

nodemon app.js


🌐 Server will start at:

http://localhost:3000

--- 


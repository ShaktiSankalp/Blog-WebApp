


# 📝 MERN Stack Blog App

A full-featured **Blog Platform** built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). Includes modern features like **JWT authentication**, **rich text editing**, **image uploads**, **commenting**, **admin panel**, **search**, and more.

---

## 🚀 Features

- 🔐 JWT Authentication (Login/Register with protected routes)
- ✍️ Rich Text Editor for blog post creation
- 🖼️ Image Upload (local or Cloudinary)
- 💬 Comments & Replies on posts
- 🧑‍💼 Admin Dashboard (manage posts, users)
- 🔍 Search and Filter posts by tags, author, or keywords
- 📆 Post Scheduling and Draft Saving
- 🌐 RESTful API built with Express
- 📱 Mobile-Responsive UI with React
- 📦 Fully modular codebase for scalability

---

## 🛠️ Tech Stack

**Frontend:**
- React.js (Hooks, Context API / Redux)
- React Router
- Axios
- Tailwind CSS / Material UI

**Backend:**
- Node.js + Express.js
- MongoDB + Mongoose
- JWT + Bcrypt for authentication
- Multer + Cloudinary for image handling

**Other Tools:**
- ESLint + Prettier
- dotenv for config
- GitHub Actions (CI/CD optional)

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/mern-blog-app.git
cd Blog WebApp
````

### 2. Setup the Backend

```bash
cd backend
npm install
```

Create a `.env` file and add:

```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the backend server:

```bash
node index.js
```

### 3. Setup the Frontend

```bash
cd ../frontend
npm install
npm run dev
```

The frontend will run on `http://localhost:3000` and backend on `http://localhost:5000`.

---


## ✅ Roadmap / To-Do

* [ ] Unit & integration tests
* [ ] Docker support

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Please fork the repo and submit a pull request.




---

## 🌐 Live Demo

> Coming soon 

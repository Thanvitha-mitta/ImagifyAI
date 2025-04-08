# 🖼️ ImagifyAI - Text to Image Generator SaaS App

ImagifyAI is a full-stack **SaaS web application** that generates high-quality images from text prompts using the **ClipDrop API**. Built with the **MERN stack**, it features user authentication, credit-based usage, and a sleek UI — making it ideal for both demo and real-world use.

Live Demo 👉 [ImagifyAI on Render](https://imagifyai-frontend.onrender.com)

---

## ✨ Features

- 🔐 **User Authentication** (JWT-based login & registration)
- 🧠 **AI-Powered Image Generation** using **ClipDrop API**
- 🎯 **Credit System** (1 credit = 1 image generation)
- 📊 **Credit Tracker** in real-time
- 🚀 **Fully deployed** (Frontend + Backend on Render)

---

## 🛠️ Tech Stack

### Frontend:
- React.js
- Axios
- Tailwind CSS

### Backend:
- Node.js
- Express.js
- JWT for Auth
- MongoDB 
- ClipDrop API

### Deployment:
- Render (for both client and server)
- .env for API keys and configs

---

## 📦 Folder Structure

```
imagifyai/
├── client/                 # React frontend
│   └── src/
│       ├── components/
│       ├── pages/
│       └── services/
├── server/                 # Node + Express backend
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── middleware/
└── README.md
```

---

## 🚀 Getting Started (Locally)

### 1. Clone the repo

```bash
git clone https://github.com/Thanvitha-mitta/ImagifyAI.git
cd ImagifyAI
```

### 2. Setup backend

```bash
cd server
npm install
```

Create a `.env` file with:

```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLIPDROP_API_KEY=your_clipdrop_api_key
```

Then run:
```bash
npm run dev
```

### 3. Setup frontend

```bash
cd ../client
npm install
npm start
```

---

## 🧪 API Endpoints (RESTful)

| Method | Endpoint              | Description                 |
|--------|------------------------|-----------------------------|
| POST   | `/api/auth/register`   | Register a new user         |
| POST   | `/api/auth/login`      | Login existing user         |
| POST   | `/api/generate-image`  | Generate image from prompt  |
| GET    | `/api/user/images`     | Fetch user's generated images |
| PATCH  | `/api/user/credits`    | Update user's credits       |

---

## 🧠 Future Improvements

- 🔌 Integrate payment gateway for credit purchases
- 📈 Add dashboard analytics for user activity
- 🛡️ Admin panel for monitoring image generations
- 🌍 Internationalize for multi-language support

---


## 🙌 Acknowledgements

- [ClipDrop API](https://clipdrop.co/apis)
- [Render](https://render.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

---

## 👤 Author

**Thanvitha Mitta**  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)  
📧 thanvithamitta@gmail.com

---

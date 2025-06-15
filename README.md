# 💬 Chatty

Welcome to **Chatty** — the real-time chat app where typing fast and hitting send recklessly is strongly encouraged. 🚀  
A fullstack modern webapp built with love, caffeine, and probably a few rage restarts. ❤️‍🔥

---

## 🔧 Tech Stack

Because why use one framework when you can use five?

- ⚛️ **React** + **Vite** – frontend built for speed and sanity
- 🎨 **TailwindCSS** + **DaisyUI** – styling that doesn’t look like 1998
- 🧠 **Node.js** + **Express.js** – backend that Just Works™
- 📡 **Socket.io** – for that spicy real-time messaging
- 🍃 **MongoDB** – yes, we have a database! Unlike your crush, your messages won’t disappear.
- ☁️ **Render** – the cloud magic that makes it all live

---

## 🗂 Project Structure

Chatty/

  ├── backend/ # Express backend with socket.io + MongoDB

  ├── frontend/ # React frontend (Vite + Tailwind + DaisyUI)

  ├── package.json # Root scripts for build/start

## 🧪 Getting Started

If you're reading this, you're either:
1. Here to run the app 🔧
2. Stalking my code 👀
3. Just really bored 🤷

### 🚀 Quick Start

1. **Clone the repo:**
 ```
 git clone https://github.com/yourusername/chatty.git
 cd chatty
```
2. Install dependencies:

```

npm install --prefix backend
npm install --prefix frontend
```

🔐 Step 3: Set up environment variables

    
```bash

cd backend
```
create .env file, which must look like this

```
# MongoDB connection string – replace with your own MongoDB Atlas URI
MONGODB_URI=mongodb+srv://<username>:<password>@<cluster-url>/<database>?retryWrites=true&w=majority&appName=<yourAppName>

# Port your backend will run on (default is 5000 or 5001)
PORT=5001

# JWT secret for authentication – make it long and hard to guess
JWT_SECRET=your_super_secret_key_here

# Cloudinary config for image uploads (optional if you don’t use it)
CLOUDINARY_CLOUD_NAME=your_cloud_name_here
CLOUDINARY_API_KEY=your_api_key_here
CLOUDINARY_API_SECRET=your_api_secret_here

# Environment mode (usually development or production)
NODE_ENV=development
```
🚀 Step 4: Run the backend

in one terminal:
```
cd backend
npm run dev
```

🌐 Step 5: Run the frontend
```
cd frontend
npm run dev
```
💻 Step 6: Open the app

Once both servers are running, head over to:

👉 http://localhost:5173

If you don’t see it,  restart both terminals, or/and restart code editor, or/and restart computer, if still don't see it, get ☕


### 👀 Features

🧑‍🤝‍🧑 Real-time messaging

🍃 MongoDB-powered conversations (because someone has to remember your chaos)

🖼 Clean and responsive UI (thank you DaisyUI gods)

🌈 Choose from literally 32 themes with daisyUI
Want your chat to feel like a hacker cave? Or a unicorn tea party?
Boom. One config line. One click. Pure aesthetic madness.

### ⚠️ Disclaimer
This project is a work in progress. It might break, yell at you in the console, or gaslight you into thinking it works when it doesn't.
Use responsibly. Or not.

### 🙌 Contributing
Fork it, break it, fix it, repeat. PRs welcome!

#### 📬 Contact

Have questions, suggestions, or memes?
Reach out via LinkedIn: https://www.linkedin.com/in/mako-dolidze/ or throw a paper plane my way 🛩️

### ⭐ If you like it, star it. If you hate it... star it anyway. 



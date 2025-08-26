# Chat App  

Chat App is a simple real-time chat application where users can sign up, log in, and chat instantly.  
The project has two parts:  

- **Frontend (React with Vite)** → deployed on **Netlify**  
- **Backend (Node.js + Express)** → deployed on **Vercel**  

---

## Project Description  

This project is built to provide an easy-to-use chat app with authentication and live messaging.  
It has a modern interface, is lightweight, and can be run locally or used directly from the deployed links.  

---

## Installation Instructions  

**1. Clone the repository from GitHub:**  
`git clone https://github.com/shubhambhumi07/Chat-App.git`  

**2. Install dependencies separately for frontend and backend:**  

- For backend:  
  - `cd server`  
  - `npm install`  

- For frontend:  
  - `cd client`  
  - `npm install`  

**3. Set environment variables:**  

- Backend (`server/.env`):  
  - `PORT=5001`  
  - `MONGO_URI=your_mongodb_connection`  
  - `JWT_SECRET=your_secret_key`  

- Frontend (`client/.env.local`):  
  - `VITE_BACKEND_URL=http://localhost:5001` (for local)  
  - `VITE_BACKEND_URL=https://chat-app-backend-phi-murex.vercel.app` (for production)  

**4. Run the project locally:**  
- Backend → `npm run dev` inside `server` folder  
- Frontend → `npm run dev` inside `client` folder  

---

## Usage  

- In local development, open the frontend at: **http://localhost:5173**  
- Create an account or log in  
- Start chatting  

**Deployed Links:**  
- Frontend (Netlify): [https://keen-torrone-0eec51.netlify.app](https://keen-torrone-0eec51.netlify.app)  
- Backend (Vercel): [https://chat-app-backend-phi-murex.vercel.app](https://chat-app-backend-phi-murex.vercel.app)  

---

## Features  

- 🔐 User signup and login with authentication  
- 💬 Real-time chat system  
- 🖼️ Photo upload and sharing inside chat  
- 🟢 Online users list (see who is currently active)  
- 🎨 Clean and modern UI with React and TailwindCSS  
- ⚡ Fast build and development with Vite  
- ☁️ Fully deployed using Netlify (frontend) and Vercel (backend)  
- 🔄 Routing support with Netlify redirects  

---

## Screenshots  

**Login Page:**  
![Login Page](https://github.com/shubhambhumi07/Chat-App/blob/main/assets/login.png)  

**Home Page:**  
![Home Page](https://github.com/shubhambhumi07/Chat-App/blob/main/assets/home.png)  

*(Make sure to upload your screenshots into an `assets/` folder in your repo and rename them `login.png` and `home.png`.)*  

---

## Acknowledgments  

- **React** for building the frontend  
- **Vite** for fast development  
- **Express** for backend server  
- **MongoDB** for database  
- **Netlify** and **Vercel** for easy deployment  

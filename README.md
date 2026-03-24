# 🚀 Hire-Sense - MERN Job Portal

A full-stack job portal built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that connects job seekers and recruiters with real-time application tracking, authentication, and dashboard analytics.

---

## 🔗 Quick Access

👉 Frontend Code: https://github.com/Sip-p/jobportal-client  
👉 Backend Code: https://github.com/Sip-p/jobportal-server  
👉 Live Demo: (https://jobportal-client-liard.vercel.app/)

---

## 💻 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Context API
- React-Quill (Rich text editor)
- Framer Motion & GSAP (Animations)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- RESTful APIs

### Authentication & Security
- Clerk (SSO for candidates)
- JWT Authentication (recruiters)
- bcrypt (password hashing)

### Media & Integrations
- Multer (file uploads)
- Cloudinary (image & resume storage)
- Svix (Clerk webhooks)

---

## ✨ Features

- 👤 Dual-role system (Candidate & Recruiter)
- 📝 Job posting and application tracking
- 📊 Recruiter dashboard with analytics
- 📄 Resume upload (PDF support)
- 🔐 Secure authentication & authorization
- ⚡ Real-time data handling and smooth UI experience
- 🎨 Responsive UI with modern animations

---

## 🧠 System Design Highlights

- Designed a **dual-authentication system** combining Clerk SSO and custom JWT flows
- Built **scalable REST APIs** with Express.js
- Modeled **complex relationships** between users, jobs, and applications using MongoDB
- Implemented **cloud-based media storage** to reduce server load

---

## ⚙️ Installation & Setup

### 1. Clone Repositories
```bash
git clone https://github.com/Sip-p/jobportal-client
git clone https://github.com/Sip-p/jobportal-server

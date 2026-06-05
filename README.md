# Notion Club - Event Registration Portal 🚀

A full-stack web application designed for students to seamlessly register for upcoming club events, workshops, and hackathons. This project provides a smooth user experience for event registration with dynamic backend integration, validation, and real-time database storage.

🌐 **Live Project URL:** https://notion-bhumi.vercel.app

---

## ✨ Features

### 💻 Frontend (Client Side)
- **Hero Section:** Clean UI featuring the event banner, catchy taglines, and a direct 'Register Now' action button.
- **About Section:** Clear display of event details, venue/platform information, date & time, and guest speaker insights.
- **Registration Form:** Intuitive validation-backed fields capturing crucial student data.
- **Instant Response Alerts:** User-friendly success and failure messages based on real-time API responses.

### ⚙️ Backend (Server Side)
- **Robust REST API:** Handles form submissions securely and triggers responses instantly.
- **Database Storage:** Connected seamlessly with MongoDB Atlas to store and manage participant details.
- **Data Validation:** Form controls to ensure input data integrity before processing.
- **Fetch Registrations Endpoint:** Built-in route to gather and view all registered participants.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+), Hosted on Vercel
- **Backend:** Node.js, Express.js, Hosted on Render
- **Database:** MongoDB Atlas, Object Modeling via Mongoose

---

## 📂 Project Structure

```text
├── Notion-task/          # UI components, assets, and pages (Vercel)
└── Notion-backend/        # Express server, routes, database schemas (Render)
```
---

## 🚀 Quick Setup & Run

Follow these quick commands to get the project running locally:

### 1. Clone & Install
```bash
git clone [https://github.com/bhatibhumi7/Notion-Web.git](https://github.com/bhatibhumi7/Notion-Web.git)
cd Notion-Web
```
---
### 2. Go to backend & install dependencies
```
cd Backend
npm install
```
---
### Create .env file
```env
MONGO_URI=mongodb+srv://<YOUR_MONGODB_USERNAME>:<YOUR_MONGODB_PASSWORD>@cluster0.mongodb.net/your_db_name
PORT=5000
```
---
### Start backend server
```
node server.js
```
---
### Start frontend 
```
npm run dev
```
# 🧑‍💻Author
-**Bhumi bhati**- https://github.com/bhatibhumi747-byte


# 🎉 College Event Networking Platform

A **full-stack MERN platform** for discovering, managing, and networking during college events. This platform enables students to explore events, register easily, chat in real-time with other attendees, and allows organizers and admins to manage events efficiently.

---

## 🚀 Tech Stack
- **Frontend:** React.js, Material UI, React Router  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Atlas)  
- **Real-Time Communication:** Socket.IO  
- **Authentication & Security:** JWT, bcrypt  
- **Deployment:** Netlify (Frontend), Render (Backend)

---

## ✨ Features

### Core Features
- 🔑 **Role-Based Authentication:** Student, Organizer, and Admin accounts with proper privileges  
- 📅 **Event Creation & Registration:** Easy management and registration for college events  
- 🔍 **Event Filtering & Search:** Filter events by date, category, location, and popularity  
- 💬 **Real-Time Chat:** Communicate instantly with other attendees  
- 📊 **Admin Dashboard:** Monitor events, users, and platform analytics  

### Additional Features
- 🔔 Notifications for upcoming events  
- 📱 Fully responsive and mobile-friendly design  
- 👤 User profiles with event history  
- 🔒 Secure password hashing and JWT-based sessions  

---

## 📂 Project Structure
College_Event/
├── backend/ # Express.js backend API
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
├── frontend/ # React.js frontend client
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.js
│ └── package.json
├── .gitignore
└── README.md

## ⚙️ Setup Instructions

### Backend
```bash
cd backend
npm install
npm run dev

### Frontend
cd frontend
npm install
npm start

🌐 Live Demo
Project Live Link : http://clgevent.netlify.app/
Frontend Depolyed : Netlify
Backend Depolyed : Render

📸 Screenshots
Homepage
<img width="1920" height="918" alt="Screenshot 2025-02-01 013042" src="https://github.com/user-attachments/assets/46a8cad9-d31c-40e5-8c8a-c628c1a08843" />
Event Listing & Filter
<img width="1920" height="881" alt="Screenshot 2025-01-28 014614" src="https://github.com/user-attachments/assets/c28e03f0-aff1-4d0b-8935-616d991e1661" />
💡 How It Works

-Users sign up and log in according to their roles.

-Organizers can create and manage events.

-Students browse, filter, and register for events.

-Real-time chat connects attendees during events.

-Admins monitor platform activity and manage users/events.

🔒 Security

-Passwords hashed using bcrypt

-JWT authentication for secure routes

-Role-based access control to prevent unauthorized access

📈 Future Enhancements

-Event calendar view with drag-and-drop registration

-AI-based event recommendations

-Virtual event video streaming

-Advanced analytics and reporting for admins

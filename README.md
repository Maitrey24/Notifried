# 🔔 Notifried - Real-Time Chat App

**Notifried** is a fully functional **MERN stack real-time chat application** featuring instant messaging, group chats, user authentication, and dynamic theme switching with **32 DaisyUI themes**. This app is based on the amazing tutorial by [**Codesistency**](https://youtube.com/@codesistency).

🎥 **Watch the full build tutorial here**: [YouTube - Codesistency](https://youtu.be/ntKkVrQqBYY?si=Vgn3z22IrBKGBXg0)

---

## ✨ Key Features

- 💬 Real-Time Messaging with **Socket.IO**
- 🔐 Secure **JWT Authentication**
- 👥 One-on-one and group chat support
- 🎨 **32 DaisyUI Themes** for personalization
- 🌓 Light/Dark mode support
- 🔔 Smart unread message notifications
- 📱 Responsive design (mobile-friendly)
- 🧭 User & Chat search functionality
- 📂 Persistent chat history via MongoDB
- 🧑 Profile editing and settings panel

---

## 🌐 Tech Stack

**Frontend**:

- React.js
- Tailwind CSS + DaisyUI
- Socket.IO Client
- Axios

**Backend**:

- Node.js
- Express.js
- MongoDB (with Mongoose)
- Socket.IO Server
- JWT + bcrypt.js

---

## 🧪 Getting Started

### 🔧 Prerequisites

- Node.js and npm
- MongoDB (local or cloud)
- Git

### 📥 Clone the Repository

```bash
git clone https://github.com/your-username/notifried.git
cd notifried
```

### 🚀 Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret_key
CLIENT_URL=http://localhost:3000
```

Run backend server:

```bash
npm run dev
```

### 💻 Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

---

## 🎨 DaisyUI Themes

Notifried supports 32 built-in themes from DaisyUI, including:

- `light`, `dark`, `cupcake`, `bumblebee`, `emerald`, `corporate`, `synthwave`, `retro`, `cyberpunk`, `valentine`, `halloween`, `garden`, `forest`, `aqua`, `pastel`, `fantasy`, `wireframe`, `luxury`, `dracula`, `cmyk`, `autumn`, `business`, `acid`, `lemonade`, `night`, `coffee`, `winter`, and more!

Users can select themes via the UI settings panel.

---

## 🙏 Credits

Big thanks and all credit to [**Codesistency**](https://youtube.com/@codesistency) for the original tutorial and codebase that inspired this project.

📺 Watch the original tutorial here:  
[**Build a MERN Real-Time Chat App with Socket.IO**](https://youtu.be/ntKkVrQqBYY?si=Vgn3z22IrBKGBXg0)

---

## 🤝 Contributing

Feel free to fork this repo, customize the UI or add new features like:

- Message delete/edit
- Voice/video chat (via WebRTC)
- Emojis, attachments, etc.

Pull requests welcome!

---

## 📬 Contact

For questions or feedback:

- Email: maitrey.bharambe24@gmail.com

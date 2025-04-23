
# Chess AI Platform

A full-stack web-based chess application that enables players to compete against an AI opponent or another user online in real time. Built with React, Node.js, WebSocket, and MySQL.

---

## 🌐 Live Demo

- **Frontend**: [https://chess-ai-platform.vercel.app](https://chess-ai-platform.vercel.app)
- **Backend API**: [https://chess-backend.onrender.com/api](https://chess-backend.onrender.com/api)
- **WebSocket**: [https://chess-backend.onrender.com](https://chess-backend.onrender.com)

---

## 👤 Demo Accounts

| Username   | Password |
|------------|----------|
| demoUser1  | pass123  |
| demoUser2  | pass456  |

---

## ⚙️ Tech Stack

| Layer     | Technology             |
|-----------|------------------------|
| Frontend  | React, TailwindCSS     |
| Backend   | Node.js, Express       |
| Realtime  | WebSocket (Socket.IO)  |
| AI Engine | Minimax Algorithm      |
| Database  | MySQL (via Railway)    |

---

## 🚀 Local Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/kiraka0228/chess-ai-platform.git
cd chess-ai-platform
```

### Install Dependencies

```bash
cd chess-client
npm install

cd ../chess-server
npm install
```

### Configure Environment Variables

#### Frontend (.env)
```env
REACT_APP_SOCKET_URL=http://localhost:5000
REACT_APP_API_URL=http://localhost:5000/api
```

#### Backend (.env)
```env
DB_HOST=your_mysql_host
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=chess_ai
PORT=5000
```

### Run the App

In one terminal:
```bash
cd chess-server
node server.js
```

In another terminal:
```bash
cd chess-client
npm start
```

---

## 📁 Project Structure

```
chess-ai-platform/
├── chess-client/        # React frontend
└── chess-server/        # Node.js backend with AI + Socket.IO
```

---

## 📄 License

For academic demonstration use only.

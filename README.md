# 🚀 UniHelp Backend

<p align="center">
  <h3 align="center">Backend API for UniHelp Campus Super App</h3>

  <p align="center">
    A scalable Node.js + Express backend powering authentication, campus feed, marketplace, messaging, events, notes, and real-time student collaboration using Firebase services.
  </p>
</p>

---

# 📌 Overview

UniHelp Backend provides RESTful APIs and business logic for the UniHelp ecosystem. It manages authentication, Firestore operations, Firebase Storage integration, marketplace workflows, messaging, events, notifications, and campus social interactions.

---

# 🌐 Live API

**Backend Deployment**

https://unihelp-backend-a5f3.onrender.com
---

# ✨ Features

## 🔐 Authentication

- Firebase Authentication
- JWT Verification
- Protected Routes
- User Registration
- Login
- Session Validation

---

## 👤 User Management

- Create Profile
- Update Profile
- User Search
- Academic Information
- Profile Images

---

## 🏠 Social Feed

- Create Posts
- Edit Posts
- Delete Posts
- Like Posts
- Save Posts
- Comments
- Trending Feed

---

## 📝 Notes

- Upload Notes
- Download Notes
- Browse Notes
- File Metadata
- Subject Categories

---

## 🛒 Marketplace

- Create Listings
- Browse Listings
- Reserve Items
- Contact Seller
- Mark Sold
- Delete Listings

---

## 📅 Events

- Create Events
- Browse Events
- Event Posters
- Calendar Support

---

## 📊 Polls

- Create Polls
- Vote
- Poll Results

---

## 💬 Messaging

- Conversation APIs
- Message APIs
- User Conversations

---

## 🔎 Lost & Found

- Report Lost Items
- Found Items
- Browse Listings

---

## 📦 File Storage

- Firebase Storage
- Image Uploads
- Notes Uploads
- Event Posters
- Profile Images

---

# 🛠 Tech Stack

## Runtime

- Node.js

## Framework

- Express.js

## Database

- Firebase Firestore

## Authentication

- Firebase Authentication
- JWT

## Storage

- Firebase Storage

## Deployment

- Render

## Utilities

- Multer
- dotenv
- CORS

---

# 🏗 System Architecture

```text
                React Native App
                        │
                        ▼
                Express REST API
                        │
        ┌───────────────┼───────────────┐
        ▼               ▼               ▼
 Firebase Auth     Firestore      Firebase Storage
        │               │               │
        └───────────────┼───────────────┘
                        ▼
               Business Logic Layer
```

---

# 📂 Project Structure

```text
backend/

├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── services/
├── utils/
├── uploads/

server.js
package.json
```

---

# 📡 API Modules

### Authentication

- Login
- Register
- Verify User

### Users

- Get Profile
- Update Profile
- Search Users

### Posts

- Create
- Read
- Update
- Delete

### Comments

- Add Comment
- Delete Comment

### Marketplace

- Listings
- Reserve
- Contact Seller

### Notes

- Upload
- Download

### Events

- Create
- Browse

### Polls

- Create
- Vote

### Messages

- Conversations
- Messages

---

# ⚙️ Installation

Clone repository

```bash
git clone https://github.com/utkarsh0885/UniHelp-backend.git
```

Move into project

```bash
cd UniHelp-backend
```

Install dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Development

```bash
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file.

```env
PORT=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=

JWT_SECRET=

FRONTEND_URL=
```

---

# 📈 Backend Highlights

- RESTful API Design
- Modular Architecture
- Firebase Integration
- JWT Authentication
- Secure Middleware
- Error Handling
- Image Upload Support
- Production Deployment

---

# 🔮 Future Improvements

- WebSockets
- Push Notifications
- Rate Limiting
- Redis Caching
- AI Moderation
- Analytics Dashboard
- Admin Panel
- Audit Logs
- API Versioning
- Docker Support

---

# 🤝 Contributing

1. Fork repository

2. Create branch

```bash
git checkout -b feature/new-feature
```

3. Commit

```bash
git commit -m "Add feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Open Pull Request

---

# 📄 License

MIT License

---

# 👨‍💻 Developer

**Utkarsh Thakur**

GitHub:
https://github.com/utkarsh0885

Email:
utkarshthakur0701@gmail.com

---

## ⭐ If you like this project, consider giving it a Star.

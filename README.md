# ResolvePoint 🚀

A Complaint Tracking and Disposal System built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).

---

## 🔥 Features

- 🛡️ User Authentication (JWT based)
- 📨 SMS-based OTP Verification (Fast2SMS)
- 🖊️ Complaint Registration
- 📋 View & Track Complaint Status
- 🏛️ Officer Dashboard for Complaint Management
- 📈 Filter Complaints by Status
- 🔑 Forgot Password via OTP
- 📱 Mobile Responsive UI
- ⏳ JWT Auto Expiry Check & Logout

---

## 🛠️ Tech Stack

- **Frontend**: React.js, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Authentication**: JWT Tokens
- **OTP Service**: Fast2SMS API

---

## 📂 Project Structure

```plaintext
/resolvepoint
├── backend/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
├── frontend/
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── LICENSE
└── README.md
```

## ⚙️ Setup Instructions

1. **Clone the repository**
```
git clone https://github.com/Hiren-Sarvaiya/ResolvePoint.git
cd resolvepoint
```

2. **Setup Backend**
```
cd backend
npm install
npm run dev
```

3. **Setup Frontend**
```
cd frontend
npm install
npm run dev
```

4. **Environment Variables**
- Create two .env files in /backend and /frontend :
- Backend ```.env```
```
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
FAST2SMS_API_KEY=your_fast2sms_api_key
SESSION_SECRET=your_session_secret
EMAIL=your_email
EMAIL_PASSKEY=your_email_passkey
```

- Frontend ```.env```
```
VITE_BACKEND_API_BASE=your_backend_api's_base
```

## ✨ Author

- Hiren Sarvaiya
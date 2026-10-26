# 🚀 Quick Start - JWT Authentication

## TL;DR - Get Started in 3 Steps

### 1. Start Backend
```bash
cd back-end
npm start
```
✅ Should see: "🚀 Starting server in development mode", "Connected to MongoDB Atlas" and "Server running on http://localhost:7001"

### 2. Start Frontend
```bash
cd front-end  
npm start
```
✅ Should see: "Local: http://localhost:5173/" (or similar)

### 3. Login
- Navigate to the app in your browser
- Click "Get Started"
- Click **"🚀 Quick Demo Login (dev)"** button

**Demo Credentials** (if needed):
- Email: `demo@readnest.app`
- Password: `password123`

---

## ✅ What's Working Now

- ✅ JWT authentication on all API endpoints
- ✅ Frontend sends tokens automatically
- ✅ Login/Register forms functional
- ✅ Auth state managed globally
- ✅ Test user created in MongoDB
- ✅ "Access token required" errors fixed

---

## 📝 Test User Info

**Email**: `demo@readnest.app`  
**Password**: `password123`  
**User ID**: `692cd73b55793bcaa23e9683`

To recreate:
```bash
cd back-end
node scripts/createTestUser.js
```

---

## 🔧 Environment Setup

**Backend** needs `.env` file (already created):
```bash
cd back-end
# .env file exists with MongoDB URI and JWT_SECRET
```

**Frontend** - No .env needed for basic usage

---

## 🐛 Troubleshooting

### "Access token required" error?
→ **Login first!** Click the demo login button

### Backend won't start?
→ Check `.env` file exists in `back-end/` directory

### Can't login?
→ Run: `node back-end/scripts/createTestUser.js`

### Frontend errors?
→ Clear browser: `localStorage.clear()` then refresh

---

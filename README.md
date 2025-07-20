# 📍 ClusterHex

A full-stack **location review app** powered by **MongoDB, Express.js, and jQuery** with secure authentication and dynamic, map-based interaction.

🗺️ Submit and browse places, view geocoded markers, and get real-time updates via AJAX. User sessions are persisted and scoped for access control.

<img  height="700" alt="image" src="https://github.com/user-attachments/assets/f86f2951-4583-401e-aa99-7cfcdad89b0b" />

---

## 🎯 Features

- ✅ Secure login & session handling with Passport.js
- ✅ User-level access control (authenticated vs unauthenticated)
- ✅ Dynamic map rendering with geocoded markers
- ✅ Real-time marker updates via AJAX (jQuery)
- ✅ Form validation and flash messaging
- ✅ RESTful CRUD for reviews and places
- ✅ Fully deployed on Heroku with persistent MongoDB

---

## 📦 Tech Stack

**Frontend:**
- HTML + EJS
- Bootstrap
- jQuery
- AJAX

**Backend:**
- Node.js + Express.js
- MongoDB + Mongoose
- Passport.js (Local Strategy)
- Cloudinary (for image uploads)

**Deployment:**
- Heroku (App)
- AWS EC2 (MongoDB)
- dotenv + session-store



---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Yash-Aanand/ClusterHex.git
cd ClusterHex
```


### 2. Install dependencies
```bash
npm install
(make sure MongoDB is installed if running locally)
```

### 3. Set up .env file

Create a .env file in the root with the following:
```bash
MAPTILER_API_KEY=your_api_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
```

### 4. Run the app locally
```bash
node app.js
```

The app will start at:
🔗 http://localhost:3000

## 🛠 Dependencies
```bash
express
mongoose
ejs
ejs-mate
passport
passport-local
connect-flash
method-override
dotenv
cloudinary
multer
maptiler-sdk
```

---

## 🔐 License

MIT — free to use, modify, and distribute.

---

## 👨‍💻 Author

**Yash Aanand**  
Computer Science @ University of Waterloo  

- 🌐 [yashaanand.com](https://yashaanand.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/yash-aanand-35192b273/)
- 🛠️ [GitHub](https://github.com/Yash-Aanand)




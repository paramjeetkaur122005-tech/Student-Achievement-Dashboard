# 🎓 Student Achievement Dashboard

A high-performance **MERN Stack** application designed to help students track academic progress, visualize GPA trends, manage certifications, and showcase achievements through an elegant modern dashboard.

---

## 📸 Preview

<img width="1918" height="911" alt="Dashboard Preview 1" src="https://github.com/user-attachments/assets/fb7e5e3f-d8f9-4d9e-b8fb-a55a1666cfdc" />

<br>

<img width="1918" height="913" alt="Dashboard Preview 2" src="https://github.com/user-attachments/assets/6e55baca-5a7e-41e7-b0c4-8b45e0dc3246" />

---

## 🚀 Key Features

### 📊 Data Visualization
Interactive **Line Charts** and **Bar Charts** powered by **Chart.js** to monitor SGPA and CGPA growth across semesters.

### 🧮 Automated GPA Engine
Smart GPA calculation system based on credit hours and subject grades.

### ☁️ Certificate Vault
Secure certificate and achievement storage using **Cloudinary** integration.

### 🏆 Achievement Badges
Automatic milestone recognition such as:
- Semester Topper
- Top Ranker
- Consistent Performer

### 🌙 Modern UI/UX
Responsive and animated interface built using:
- Tailwind CSS
- Framer Motion
- Dark Mode Support

---

# 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React.js, Tailwind CSS, Framer Motion |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT, Bcrypt.js |
| **Cloud Storage** | Cloudinary |
| **Charts & Analytics** | Chart.js |

---

# 📁 Project Structure

```text
student-dashboard/
│
├── client/                     # React Frontend
│   ├── src/
│   │   ├── components/         # Reusable UI Components
│   │   ├── pages/              # Dashboard Pages
│   │   ├── hooks/              # Custom Hooks
│   │   ├── context/            # Auth Context
│   │   └── utils/              # Helper Functions
│
├── server/                     # Node.js Backend
│   ├── models/                 # Mongoose Schemas
│   ├── controllers/            # Business Logic
│   ├── middleware/             # JWT/Auth Middleware
│   ├── routes/                 # API Routes
│   └── config/                 # Database Config
│
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/student-dashboard.git
cd student-dashboard
```

---

# 🖥️ Backend Setup

Navigate to the backend folder:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `server` directory:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
```

Start the backend server:

```bash
npm start
```

Backend runs on:

```bash
http://localhost:5000
```

---

# 🌐 Frontend Setup

Open a new terminal and navigate to the client folder:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start the frontend:

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# 📈 Future Roadmap

- [ ] PDF Export for Report Cards
- [ ] LinkedIn Achievement Sharing
- [ ] AI-Based Performance Prediction
- [ ] Attendance Analytics
- [ ] Real-Time Notifications
- [ ] Role-Based Admin Panel

---

# 🤝 Contributing

Contributions are welcome.

### Steps to contribute:

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Added AmazingFeature"
```

4. Push to GitHub

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ❤️ Developed by Sehaj

*"Turning academic data into visual stories, one dashboard at a time."*

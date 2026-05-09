# 🎓 Student Achievement Dashboard

A high-performance **MERN Stack** application designed for students to track academic milestones, visualize GPA trends, and manage certifications.

---

## 🚀 Key Features

*   **Data Visualization:** Interactive line and bar charts using **Chart.js** to track SGPA/CGPA growth.
*   **Automated GPA Engine:** Logic-based system to calculate semester results based on credit hours.
*   **Certificate Vault:** Secure storage for academic achievements via **Cloudinary** integration.
*   **Achievement Badges:** Automated milestone recognition (e.g., "Top Ranker", "Semester Topper").
*   **Dark Mode & Responsive UI:** Built with **Tailwind CSS** for a seamless experience across devices.

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | React.js, Tailwind CSS, Framer Motion |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose) |
| **Auth** | JWT, Bcrypt.js |
| **Storage** | Cloudinary |

---

## 📁 Project Structure

```text
├── client/                # React Frontend
│   ├── src/
│   │   ├── components/    # Reusable UI (Charts, Modals)
│   │   ├── hooks/         # Custom API hooks
│   │   └── context/       # Auth State
├── server/                # Node.js Backend
│   ├── models/            # Mongoose Schemas
│   ├── controllers/       # Business Logic
│   └── routes/            # API Endpoints



## ⚙️ Installation

### 1️⃣ Clone the Project

```bash
git clone https://github.com/yourusername/student-dashboard.git
cd student-dashboard
```

---

## 🖥️ Backend Setup

1. Navigate to the `server` folder:

```bash
cd server
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the `server` directory and add the following variables:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
```

4. Start the backend server:

```bash
npm start
```

Backend will run on:

```bash
http://localhost:5000
```

---

## 🌐 Frontend Setup

1. Open a new terminal and navigate to the `client` folder:

```bash
cd client
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend application:

```bash
npm start
```

Frontend will run on:

```bash
http://localhost:3000
```

---

## 📈 Roadmap

- [ ] PDF Export for Report Cards
- [ ] LinkedIn API integration for one-click achievement sharing
- [ ] AI-based performance prediction
- [ ] Dark Mode support
- [ ] Real-time notifications system

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### Cloud & Storage
- Cloudinary

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add some AmazingFeature"
```

4. Push to the branch

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

# ❤️ Developed by Paramjeet

*"Code, coffee, and a little chaos stitched together into one dashboard."*

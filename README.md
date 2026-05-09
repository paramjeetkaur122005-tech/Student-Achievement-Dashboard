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



⚙️ Installation
Clone the Project:

Bash
git clone [https://github.com/yourusername/student-dashboard.git](https://github.com/yourusername/student-dashboard.git)


2. **Backend Setup:**
   - Go to `server` folder.
   - Run `npm install`.
   - Create `.env` and add `MONGO_URI`, `JWT_SECRET`, and `CLOUDINARY_URL`.
   - Start with `npm start`.

3. **Frontend Setup:**
   - Go to `client` folder.
   - Run `npm install`.
   - Start with `npm start`.

---

## 📈 Roadmap

- [ ] PDF Export for Report Cards.
- [ ] LinkedIn API integration for one-click achievement sharing.
- [ ] AI-based performance prediction.

---

**Developed with ❤️ by paramjeet kaur**

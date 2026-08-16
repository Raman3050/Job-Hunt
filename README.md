<div align="center">
  <h1>🚀 Job-Hunt Portal</h1>
  <p>A Full-Stack MERN Job Portal Application tailored for Students and Recruiters.</p>
</div>

## 📖 Overview

Job-Hunt is a comprehensive platform connecting job seekers with recruiters. Built using the **MERN** stack (MongoDB, Express, React, Node.js), this application provides a modern and fast user experience thanks to Vite, Tailwind CSS, and robust state management.

## ✨ Key Features

### For Students
- **Browse & Search:** Effortlessly search for jobs by keywords, filter by category, or view latest openings.
- **Apply Instantly:** Apply to jobs with a single click and track application statuses (Pending, Accepted, Rejected).
- **Profile Management:** Update your resume (handled securely via Cloudinary), skills, and personal bio at any time.

### For Recruiters
- **Company Management:** Create multiple company profiles, upload logos, and seamlessly edit or delete them.
- **Post Jobs:** Publish new job openings specifying requirements, experience level, salary, and job type.
- **Manage Applicants:** Review applications in real-time, view candidate profiles & resumes, and update application statuses.

## 🛠️ Tech Stack

**Frontend:**
- [React.js](https://reactjs.org/) (built with Vite for lightning-fast HMR)
- [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/) for beautiful, responsive UI components
- [Redux Toolkit](https://redux-toolkit.js.org/) for centralized state management
- [React Router DOM](https://reactrouter.com/) for seamless navigation
- [Lucide React](https://lucide.dev/) for crisp vector icons

**Backend:**
- [Node.js](https://nodejs.org/) & [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/) & [Mongoose](https://mongoosejs.com/) for data modeling
- [JSON Web Tokens (JWT)](https://jwt.io/) & HttpOnly Cookies for secure authentication
- [Cloudinary](https://cloudinary.com/) & [Multer](https://www.npmjs.com/package/multer) for handling and hosting image/resume uploads
- [Bcryptjs](https://www.npmjs.com/package/bcryptjs) for password hashing

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites
- Node.js (v16+ recommended)
- A MongoDB cluster/URI
- A Cloudinary account

### 1. Clone the Repository
```bash
git clone https://github.com/Raman3050/Job-Hunt.git
cd Job-Hunt
```

### 2. Setup Backend
```bash
cd backend
npm install
```
Create a `.env` file in the `backend` directory with the following credentials:
```env
MONGO_URI=your_mongodb_connection_string
PORT=8000
SECRET_KEY=your_jwt_secret_key
CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
```
Run the backend server:
```bash
npm run dev
```

### 3. Setup Frontend
Open a new terminal window:
```bash
cd frontend
npm install
npm run dev
```
The application should now be running on `http://localhost:5173`.

---

<div align="center">
  <i>Built with ❤️ to connect talent with opportunities.</i>
</div>

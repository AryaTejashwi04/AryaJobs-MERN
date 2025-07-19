AryaJobs – MERN Stack Job Portal
AryaJobs is a full-stack job portal built using the MERN stack. It allows users to register as job seekers or recruiters, apply to jobs, manage profiles, and post job listings. The project aims to mimic core features of modern job platforms with a clean UI and scalable architecture.

🔗 Live Links
Frontend: https://aryajobs.vercel.app

Backend: https://aryajobs-api.onrender.com

folder Structure
bash
Copy
Edit
AryaJobs-MERN/
├── frontend/   # React + Vite + Tailwind
├── backend/    # Node.js + Express + MongoDB
└── README.md
Features
Job Seekers:
Register and log in

Browse and search for jobs

Apply with resume upload

Manage profile information

Recruiters:
Post and manage job listings

View applicants per job

Dashboard with basic stats

Common:
JWT-based authentication

Cloudinary resume uploads

Protected routes

Mobile responsive UI

Tech Stack
Frontend:
React (Vite)

Redux Toolkit

Tailwind CSS

Axios

Backend:
Node.js

Express

MongoDB (Mongoose)

Multer & Cloudinary

JWT Auth

Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/AryaTejashwi04/AryaJobs-MERN.git
cd AryaJobs-MERN
2. Setup Backend
bash
Copy
Edit
cd backend
npm install




PORT=3001
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
Deployment
Frontend: Vercel

Backend: Render

Database: MongoDB Atlas

Author
Tejashwi Arya

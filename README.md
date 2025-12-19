# 📘 StudyNotion — Smart EdTech Learning Platform

StudyNotion is a full-stack educational platform built with the MERN stack (MongoDB, Express, React, Node.js) that enables users to create, access, and interact with online courses, driving a collaborative and immersive learning experience for students and instructors worldwide. 
GitHub

# 🌟 Project Overview

StudyNotion empowers learners and educators with a feature-rich online ecosystem that includes:

| **Students**                | **Instructors**              | **Admins**                 |
| --------------------------- | ---------------------------- | -------------------------- |
| Explore & enroll in courses | Create & publish courses     | Moderate users & content   |
| Track progress              | Manage analytics             | View platform metrics      |
| Wishlist & checkout         | Edit & update course content | Moderate payments & access |

The platform integrates authentication, payment systems, rich media support, and secure APIs — bringing real-world learning to users everywhere.

# 🚀 Key Features
| Feature                                        | Description                                                                      |
| ---------------------------------------------- | -------------------------------------------------------------------------------- |
| 🎓 **Course Creation & Consumption**           | Instructors upload structured courses; students browse and enroll.  |
| 🔐 **Authentication & OTP Verification**       | Secure user signup/login using JWT & OTP flows.                    |
| 💸 **Secure Payments with Razorpay**           | Checkout & purchase courses securely (Razorpay).                    |
| 🖼️ **Cloudinary Media Storage**               | Store course thumbnails & video content.                           |
| 📊 **Instructor Dashboard & Analytics**        | Visualize engagement & progress metrics.                            |
| ⭐ **Ratings & Reviews**                        | Students can rate and review courses.                            |
| 🧠 **Interactive UI with TailwindCSS & React** | Dynamic, responsive frontend experience.                       |

[1]: https://medium.com/%40ayushsaha.work/building-studynotion-an-edtech-platform-powered-by-the-mern-stack-3e6589ac1c42?utm_source=chatgpt.com "Building StudyNotion: An EdTech Platform Powered by the MERN ..."
[2]: https://github.com/AnishAwadh/StudyNotion?utm_source=chatgpt.com "StudyNotion is a fully functional ed-tech platform that ... - GitHub"

# 🧩 Tech Stack
📍 Frontend

* React.js

* Tailwind CSS

* Redux (optional state management)

* Axios for API integration

⚙️ Backend

* Node.js

* Express.js

* RESTful API design

* JWT Authentication

* OTP email verification

* Razorpay payment integration

🗄️ Database

* MongoDB (Atlas / cloud or local)

☁️ Other Integrations

* Cloudinary (media upload & delivery)

* Nodemailer (OTP & transactional emails)

# 🛠️ Setup & Installation
💡 Make sure Node.js, npm, and MongoDB are installed before starting.

STEP1️⃣ Fork the repository

STEP2️⃣ Clone the repository

git clone https://github.com/your-repo-name/StudyNotion.git
* cd StudyNotion

STEP 3️⃣ 

Frontend:
* cd client
* npm install

Backend:
* cd server
* npm install

STEP 4️⃣ Environment Variables

* Create .env in both root and server folders:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
EMAIL_HOST=smtp.yourmail.com
EMAIL_PORT=your_email_port
EMAIL_USER=your_email
EMAIL_PASS=your_email_password

STEP 5️⃣ Run the app

Backend
* cd server
* npm run dev

Frontend
* cd client
* npm run dev

# 🧠 Usage
🧑‍🎓 For Students

✔ Browse and search courses.
✔ Enroll & checkout using secure payments.
✔ View your enrolled courses and progress.

👨‍🏫 For Instructors

✔ Create and manage courses (sections, content, media).
✔ View analytics on course engagement.
✔ Respond to feedback and student ratings.

🛠 For Admins (Optional)

✔ Moderate inappropriate content and users.
✔ Oversee registration & platform growth.
✔ Manage financial & engagement metrics.

# 🚢 Deployment

StudyNotion can be deployed to platforms like:

Vercel (Frontend)

Render / Railway (Backend)

MongoDB Atlas (Cloud Database)

Cloudinary (Media)

# 📌 Contributions

1. Fork the repo

2. Create a feature branch

3. Commit & push changes

4. Open a Pull Request

5. Add clear descriptions & test cases

We welcome all enhancements — UI upgrades, new features, performance improvements, and bug fixes!

# 📄 License

Licensed under the MIT License — feel free to use, modify, and distribute with attribution.

# 📫 Contact

Got feedback or suggestions?
Reach out via GitHub issues or email in your .env setup.


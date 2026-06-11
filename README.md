<h1 align="center">
  <img src="https://img.shields.io/badge/Prescripto-Healthcare%20Appointment%20App-blue?style=for-the-badge&logo=react" alt="Prescripto" />
</h1>

<p align="center">
  A full-stack doctor appointment web app built with the MERN stack — making healthcare more accessible through seamless booking and secure payments.
</p>

<p align="center">
  <a href="https://prescripto-sepia-delta.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-prescripto--sepia--delta.vercel.app-brightgreen?style=for-the-badge" alt="Live Demo" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-626CD9?style=flat-square&logo=stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/Razorpay-02042B?style=flat-square&logo=razorpay&logoColor=white" />
</p>

---

## 🌐 Live Demo

👉 **[https://prescripto-sepia-delta.vercel.app/](https://prescripto-sepia-delta.vercel.app/)**

| Role | Credentials |
|------|-------------|
| Patient | Register via the Sign Up page |
| Doctor | Log in via Doctor Login |
| Admin | Log in via Admin Panel |

---

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Pages & Modules](#-pages--modules)
- [Payment Integration](#-payment-integration)
- [Deployment](#-deployment)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)

---

## ✨ Features

### 🔑 Three-Level Authentication

**Patient**
- Sign up, log in, and book appointments with doctors
- Manage appointments — view, cancel, or reschedule
- Multiple payment options: Cash, Stripe, Razorpay
- Editable user profile (name, email, address, gender, birthday, profile picture)

**Doctor**
- Dashboard with earnings, patient count, appointment stats, and latest bookings
- View appointment details: patient info, payment mode, and status
- Update profile: description, fees, address, and availability

**Admin**
- Create and manage doctor profiles
- Full dashboard analytics: total doctors, appointments, patients, recent bookings
- Add new doctors with all details (image, specialty, degree, experience, fees, etc.)
- Manage all appointments — cancel or mark as completed

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Auth | JSON Web Token (JWT) |
| Payments | Stripe, Razorpay |
| Deployment (Frontend) | Vercel |
| Deployment (Backend) | Render |

---

## 📄 Pages & Modules

### 🏠 Home Page
- Search doctors by specialty
- View top doctors and their profiles
- Sections: About Us, Delivery Information, Privacy Policy, Get in Touch

### 🩺 All Doctors Page
- Lists all available doctors with specialty filters
- Click any doctor to navigate to their appointment page

### 📄 About Page
- Prescripto's vision and mission
- **Why Choose Us**: Efficiency · Convenience · Personalization

### 📞 Contact Page
- Office address and contact details
- Job opportunities section

### 📅 Doctor Appointment Page
- Doctor profile: picture, qualification, experience, description
- Appointment booking form: date, time, payment method
- Related doctors section

### 👤 User Profile
- Upload profile picture
- Update name, email, address, gender, birthday
- View upcoming and past appointments

### 🗄️ Admin Panel
- **Dashboard**: Doctor count, appointment stats, patient count, latest bookings
- **Add Doctor**: Full form with image, specialty, credentials, fees
- **Doctor List**: View, edit, or delete doctor profiles
- **Appointments**: Full list with patient info — cancel or mark complete

### 🩺 Doctor Dashboard
- Total earnings overview
- Appointment list with patient details (name, age, date, time, payment mode, status)
- Actions: Mark complete or Cancel
- Profile management: fees, address, availability, description

---

## 💳 Payment Integration

Prescripto supports three payment methods:

- 💵 **Cash** — Pay at the clinic
- 💳 **Stripe** — International card payments
- 🏦 **Razorpay** — India-focused payment gateway

All transactions are processed securely through their respective SDKs.

---

## 🚀 Deployment

This project is deployed across two platforms:

### Frontend — [Vercel](https://vercel.com/)
The React frontend is hosted on **Vercel** for fast, global CDN delivery with zero-config deployment from GitHub.

> Live URL: **[https://prescripto-sepia-delta.vercel.app/](https://prescripto-sepia-delta.vercel.app/)**

### Backend — [Render](https://render.com/)
The Node.js/Express API server is hosted on **Render**, providing a reliable always-on backend with easy environment variable management and automatic deploys from GitHub.

---

## 🏃 Getting Started

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)
- Stripe & Razorpay accounts

### Clone the Repository

```bash
git clone https://github.com/your-username/prescripto.git
cd prescripto
```

### Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### Environment Variables

Create a `.env` file in the `/backend` directory:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Run Locally

```bash
# Start backend
cd backend
npm run server

# Start frontend
cd ../frontend
npm run dev
```

---

## 📁 Project Structure

```
prescripto/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.jsx
│   └── index.html
└── README.md
```

---

## 📬 Contact

Have feedback or questions? Reach out through the **Contact** page on the live site.

---

<p align="center">Made with ❤️ using the MERN Stack</p>
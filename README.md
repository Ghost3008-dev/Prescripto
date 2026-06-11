# Prescripto - Doctor Appointment Web App

Prescripto is a full-stack web application designed to make healthcare more accessible by simplifying the process of booking doctor appointments. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

**Live Demo:** https://prescripto-sepia-delta.vercel.app/

---

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Token (JWT)
- **Payments:** Stripe, Razorpay

---

## Deployment

- **Frontend** is deployed on [Vercel](https://vercel.com/)
- **Backend** is deployed on [Render](https://render.com/)

---

## Key Features

### Three-Level Authentication

**Patient**
- Sign up, log in, and book appointments
- Manage appointments (view, cancel, reschedule)
- Pay via Cash, Stripe, or Razorpay
- Editable profile (name, email, address, gender, birthday, photo)

**Doctor**
- Dashboard with earnings, patient count, and appointment stats
- View patient details, payment mode, and appointment status
- Update profile: description, fees, address, availability

**Admin**
- Add and manage doctor profiles
- Dashboard with total doctors, appointments, patients, and recent bookings
- Manage all appointments — cancel or mark as completed

---

## Pages

- **Home** — Search doctors by specialty, view top doctors
- **All Doctors** — Filter doctors by specialty
- **About** — Vision, mission, and why choose Prescripto
- **Contact** — Office address, contact details, job opportunities
- **Doctor Appointment** — Book by date, time, and payment method
- **User Profile** — View and edit personal details and appointments
- **Admin Panel** — Full control over doctors and appointments
- **Doctor Dashboard** — Manage appointments and profile

---

## Payment Methods

- Stripe — card payments
- Razorpay — UPI and Indian payment options

---

## Getting Started

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)
- Stripe and Razorpay accounts

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

Create a `.env` file in the `/backend` folder:

```
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

## Project Structure

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
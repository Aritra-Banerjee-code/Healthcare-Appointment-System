# 🏥 Doctors Appointment Platform

A **Full Stack Doctors Appointment Platform** built with **Next.js, Tailwind CSS, Prisma, and Shadcn UI**, integrated with **Vonage APIs** for real-time communication. This platform helps patients **book, manage, and attend appointments online**, while doctors can manage their schedules efficiently.

---

## ✨ Features

* 👨‍⚕️ **Patient & Doctor Management** – Patients can register, log in, and book appointments, while doctors can manage their availability.
* 📅 **Appointment Scheduling** – Real-time booking and rescheduling with database-backed availability.
* 📞 **Vonage Integration** – Voice/Video call support for teleconsultations.
* 🎨 **Modern UI** – Built with **Tailwind CSS** and **Shadcn UI** for a sleek, responsive design.
* 🗄 **Database with Prisma** – Secure and scalable database models for doctors, patients, and appointments.
* 🔒 **Authentication & Authorization** – Role-based access (Doctors, Patients, Admins).
* 📊 **Dashboard** – Patients can track their appointments; doctors can view/manage schedules.

---

## 🛠 Tech Stack

* **Frontend:** Next.js, React, Tailwind CSS, Shadcn UI
* **Backend:** Next.js API routes, Prisma ORM
* **Database:** PostgreSQL (via Prisma)
* **Communication:** Vonage API (Video/Voice calls)
* **Authentication:** NextAuth.js
* **Deployment:** Vercel / Docker

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/doctors-appointment-platform.git
cd doctors-appointment-platform
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file in the root directory and add:

```env
DATABASE_URL=your_postgres_database_url
NEXTAUTH_SECRET=your_auth_secret
VONAGE_API_KEY=your_vonage_api_key
VONAGE_API_SECRET=your_vonage_api_secret
```

### 4️⃣ Run database migrations

```bash
npx prisma migrate dev --name init
```

### 5️⃣ Start the development server

```bash
npm run dev
```

---

## 📈 Future Improvements

* Add payment gateway integration (Stripe/PayPal).
* Email & SMS notifications for appointments.
* AI-powered chatbot for symptom checking.
* Multi-language support for global use.

---


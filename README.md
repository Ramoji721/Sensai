# AI Career Coach

AI Career Coach is an AI-powered platform designed to assist job seekers with interview preparation, career insights, and resume optimization. The platform leverages AI to provide personalized recommendations and salary insights.

## 🚀 Features
- **AI-Powered Interview Preparation**: Get tailored questions and feedback.
- **Industry Insights & Salary Data**: Stay updated on salary trends and job market insights.
- **Resume Optimization**: Improve your resume's ATS score and increase interview chances.
- **User Authentication**: Secure login/signup powered by **Clerk**.
- **Database Management**: **Prisma** + **PostgreSQL**.
- **Frontend Framework**: Built with **Next.js 15**.

## 📦 Tech Stack
- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL (via Prisma ORM)
- **Authentication**: Clerk
- **Hosting**: Vercel, Neon.tech for database

## 📂 Project Structure
```
.
├── public/               # Static assets (images, icons, etc.)
├── prisma/               # Prisma schema and migrations
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Next.js pages
│   ├── lib/              # Utility functions (Prisma, API calls, etc.)
├── .env                  # Environment variables
├── next.config.js        # Next.js configuration
├── prisma/schema.prisma  # Database schema
├── README.md             # Project documentation
```
## my links : -
``` sh
inngest :  https://app.inngest.com/env/production/functions/sensai
Neon DataBase : https://console.neon.tech/app/projects/damp-lab-44621918/branches/br-plain-bird-a8pyescd/tables?database=SENSAI

```
## 🔧 Setup & Installation
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/KunchapuGowriSai/SENSAI.git
cd SENSAI
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Set Up Environment Variables**
Create a `.env` file and add the necessary configurations:
```env

DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```

### **4️⃣ Run Database Migrations**
```sh
npx prisma migrate dev --name init
```

### **5️⃣ Start the Development Server**
```sh
npm run dev
```
- App runs locally at: **http://localhost:3000**

## 🚀 Deployment
- **Frontend**: Deploy on **Vercel**
- **Database**: Hosted on **Neon.tech**

## 🛠 Troubleshooting
### **Database Connection Issue**
- Ensure **Neon.tech PostgreSQL** is running.
- Check `.env` and verify `DATABASE_URL`.

### **Clock Skew Detected (Clerk Issue)**
- Sync your system clock: `w32tm /resync` (Windows) or `sudo timedatectl set-ntp on` (Linux/macOS).

### **Image Not Loading (Next.js)**
- Ensure images are in `public/` and use a leading `/` in paths (e.g., `/MEE.jpg`).

## 📜 License
This project is licensed under the **MIT License**.

## 📞 Contact
For support, reach out to [kunchapugowrisai143@gmail.com] or create an issue on GitHub!


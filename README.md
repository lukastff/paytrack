# 💸 PayTrack
Online reimbursement request platform with payment receipt.
***
## 📌 About the Project
Paytrack is a platform developed to make the reimbursement process between customers and businesses. Instead of dealing with manual or in-person processes, everything happens 100% online from user registration to submitting and reviewing receipts. <br>
***
## ✅ Features
✓ Data validation with Zod <br>
✓ Upload payment receipt directly on the platform <br>
✓ Reimbursement requests for products or services <br>
✓ Fully online process, no in-person contact required <br>
✓ User registration and authentication with JWT and BCRYPT <br>

***
## 🔄 How It Works
1. The user creates an account on the platform
2. Starts a reimbursement request by providing the product name, category, and amount
3. Uploads a photo of the payment receipt
4. The business receives and reviews the request through the platform
***
## ⚙️ Tech Stack
- **Frontend:** Vite + React + Typescript + Zod + Axios + Tailwind CSS --> [PayTrack Front-end Repository](https://github.com/lukastff/paytrack)
- **Backend:** NodeJS + Express + Typescript + JWT + BCRYPT --> [PayTrack Back-end Repository](https://github.com/lukastff/paytrack-backend)
- **Database:** SQLite via Prisma ORM
***
## 🛡️ Prerequisites
- **NodeJS** [-> Download](https://nodejs.org/en)
***
## 🛠️ Environment Variables
Add a **.env** file to your project and include the following variable:

```env
DATABASE_URL="file:./dev.db"
```
***
## 🌐 Front-end Setup

```cmd
npm install
npm run dev
```
***
## 📡 Back-end Setup

```cmd
npm install
npx prisma migrate deploy
npx prisma generate
npx prisma studio (optional — opens a GUI to view the database)
npm run dev
```
***
## 💡 Motivation
This was my first end-to-end project. Building a complete solution from front to back, including authentication, file uploads, and the business logic, helped me grow a lot as a developer. I ran into quite a few challenges along the way, and it was precisely by working through them that I truly learned.
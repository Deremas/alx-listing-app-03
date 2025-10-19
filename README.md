# 🏡 Milestone 4: Booking Detail Page

![React](https://img.shields.io/badge/React-18-61dafb?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-13+-000000?style=for-the-badge&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-4+-3178C6?style=for-the-badge&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3+-38B2AC?style=for-the-badge&logo=tailwind-css)

A **fully functional Booking Detail Page** built with **Next.js, React, TypeScript, and Tailwind CSS**, allowing users to enter contact and payment details, review booking information, and confirm their booking. The page is fully responsive and mirrors real-world platforms like Airbnb and Booking.com.

---

## 📌 Overview

This milestone helps learners practice:

- Component-based architecture in a **Next.js project**
- Building responsive **forms** with Tailwind CSS
- Dynamic **Order Summary** components
- Presenting booking and pricing information clearly
- Organizing project files for scalability and maintainability
- Implementing UX elements like **cancellation policy** and **ground rules**

---

## 🎯 Features

- ✅ **Booking Form** – Collects contact, payment, and billing details  
- ✅ **Order Summary** – Displays booking fees, subtotal, and total  
- ✅ **Cancellation Policy** – Clear information on refund rules  
- ✅ **Ground Rules** – House rules for guests  
- ✅ **Responsive Design** – Mobile, tablet, and desktop layouts using Tailwind CSS  
- ✅ **Reusable Components** – `BookingForm`, `OrderSummary`, `CancellationPolicy`  
- ✅ **TypeScript Typing** – Interfaces for booking data  
- ✅ **Clean UI/UX** – Structured layouts with Tailwind utility classes  

---

## 🛠️ Tech Stack

- **Next.js 13+** – Framework for SSR/SSG and routing  
- **React 18** – Component-based UI  
- **TypeScript** – Type safety and improved development experience  
- **Tailwind CSS 3+** – Utility-first styling for responsive design  
- **ESLint + Prettier** – Code quality and formatting  

---

## 📂 Project Structure

```bash
alx-listing-app-03/
├── components/
│   ├── booking/
│   │   ├── BookingForm.tsx         # Contact, payment, and billing form
│   │   ├── OrderSummary.tsx        # Booking fee and total summary
│   │   └── CancellationPolicy.tsx  # Cancellation rules and ground rules
│   ├── layout/                     # Header, Footer, Layout components
│   └── common/                     # Reusable UI components (Card, Button)
├── constants/                       # Sample booking and property data
├── interfaces/                      # TypeScript interfaces
├── pages/
│   ├── booking/
│   │   └── index.tsx                # Booking detail page
│   └── _app.tsx                     # Application root with Layout wrapper
├── public/                           # Images and static assets
├── styles/                           # Tailwind CSS global styles
└── next.config.js                    # Next.js configuration
```

## 🧑‍💻 Installation & Setup
1️⃣ Clone the repository
```bash
git clone https://github.com/Deremas/alx-listing-app-03.git
```
2️⃣ Navigate to the project folder
```bash
cd alx-listing-app-03
```
3️⃣ Install dependencies:
```bash
npm install
```
4️⃣ Run the development server:
```bash
npm run dev
```

Open `http://localhost:3000/booking` to view the Booking Detail Page.
---
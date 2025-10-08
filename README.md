# ₹ TrackIt AI

An AI-powered expense tracking web application built with **Next.js 15**, featuring intelligent categorization, real-time analytics, and personalized financial insights.

![Next](https://img.shields.io/badge/Next.js-15.3.5-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-19.0.0-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.17-38B2AC?style=for-the-badge&logo=tailwind-css)

## ✨ Features

### 🤖 AI-Powered Intelligence

- **Smart Categorization**: AI automatically suggests expense categories based on descriptions  
- **Financial Insights**: Personalized recommendations and spending pattern analysis  
- **Interactive AI Chat**: Get detailed explanations and advice for any insight

### 💼 Core Functionality

- **Expense Tracking**: Add, edit, and delete expenses easily  
- **Real-time Charts**: Beautiful visualizations using Chart.js  
- **Statistics Dashboard**: Comprehensive spending analytics  
- **Expense History**: Transaction history with search and filter options

### 🎨 Modern UI/UX

- **Light & Dark Mode**: Smooth theme switching  
- **Fully Responsive**: Works on all devices  
- **Beautiful Animations**: Smooth hover and click interactions  
- **Gradient Cards**: Modern blur-glass design for dashboards

### 🔐 Authentication & Security

- **Clerk Authentication**: Secure and easy user login  
- **Google/Email Login** options  
- **User Profiles**: Personalized dashboards per user

## 🛠️ Tech Stack

### Frontend

- **Next.js 15** – App Router + Server Actions  
- **React 19** – Latest concurrent React  
- **TypeScript** – Type-safe development  
- **Tailwind CSS** – Modern, utility-first styling  
- **Chart.js** – Interactive charts

### Backend & Database

- **Neon DB** – Serverless PostgreSQL  
- **Prisma** – Type-safe ORM  
- **Server Actions** – Fast API endpoints

### AI & Authentication

- **OpenRouter API** – Free OpenAI-compatible API  
- **Clerk** – User authentication and session management  

### Deployment

- **Vercel** – Serverless hosting for modern web apps

## 🚀 Getting Started

### Prerequisites

- Node.js 18+  
- npm / yarn / pnpm

### Installation

```bash
git clone https://github.com/mnvarts/expense-tracker-ai.git
cd expense-tracker-ai
npm install
```

### Environment Setup

Create a `.env` file in the root directory:

```env
DATABASE_URL="your-neon-db-url"

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
CLERK_SECRET_KEY="your-clerk-secret-key"

OPENROUTER_API_KEY="your-openrouter-api-key"

NEXT_PUBLIC_APP_URL="http://localhost:3000"
```

### Database Setup

```bash
npx prisma generate
npx prisma db push
```

### Run Development Server

```bash
npm run dev
```

Then visit 👉 [http://localhost:3000](http://localhost:3000)

## 📊 Database Schema

- **User** → Clerk user info  
- **Record** → Expense transactions (amount, category, date)

## 🌐 Deployment (Vercel Recommended)

1. Push project to GitHub  
2. Import to [Vercel](https://vercel.com)  
3. Add `.env` variables in dashboard  
4. Deploy 🚀

## 📎 Useful Links

- [Neon Database](https://neon.tech)  
- [Clerk Authentication](https://clerk.com)  
- [Next.js Docs](https://nextjs.org)  
- [Tailwind CSS](https://tailwindcss.com)  
- [Vercel Deployment](https://vercel.com)

**Built with ❤️ by [MNV ROHITH](https://github.com/mnvrohith)**  


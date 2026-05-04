# 🚀 AI Interview Agent

> Voice-based AI interview platform for realistic, interactive, and feedback-driven interview preparation.

## 📌 Overview

AI Interview Agent is a full-stack, AI-powered interview platform that simulates real-world technical and behavioral interviews using **voice-based conversations**.

It enables users to practice interviews, receive **instant AI feedback**, and track their performance over time — replicating a real interviewer experience.

## ✨ Key Features

- 🎙️ **Voice-Based Interviews (Vapi AI)**
  - Real-time conversational interviews with AI interviewer
  - Natural speech interaction instead of text-based Q&A

- 🧠 **AI-Driven Questioning & Feedback**
  - Dynamic question generation based on role, experience, and tech stack
  - Instant evaluation and structured feedback

- 🔐 **Authentication & User Management**
  - Secure login/signup using Firebase (Email + Google OAuth)

- 📊 **Interview History Tracking**
  - Store and review past interviews for continuous improvement

- 🎯 **Custom Interview Configuration**
  - Role-based interviews (Frontend, Backend, Full-stack)
  - Experience level selection (Junior → Senior)
  - Tech stack-specific questioning

- 📱 **Responsive UI/UX**
  - Modern interface using Tailwind CSS and shadcn/ui


## 🏗️ Architecture

User (Voice Input)
        ↓
Frontend (Next.js App Router)
        ↓
Vapi AI (Voice Agent)
        ↓
Google AI (Question + Evaluation)
        ↓
Firebase (Auth + Database)
        ↓
Dashboard (History + Feedback)


## ⚙️ Tech Stack

### Frontend
- Next.js 15 (App Router)
- React 19
- TypeScript
- Tailwind CSS
- shadcn/ui + Radix UI

### Backend / Services
- Firebase (Auth + Firestore + Hosting)
- Vapi AI (Voice-based AI interviewer)
- Google AI SDK (LLM-based evaluation & feedback)

### Tools
- ESLint
- PostCSS
- Turbopack


## 🔁 Interview Flow

1. User logs in via Firebase  
2. Selects role, experience level, and tech stack  
3. AI interviewer starts voice conversation  
4. User responds verbally  
5. AI evaluates response using LLM  
6. Feedback is generated instantly  
7. Interview session is stored in database  


## 🧠 Core System Design

- Interviewer Agent (Vapi) → conducts voice interview  
- LLM Engine (Google AI) → generates questions + evaluates answers  
- Persistence Layer (Firebase) → stores sessions and user data  
- Frontend Layer (Next.js) → renders UI and manages interaction  


## 📁 Project Structure

AI-Agent-For-Interviews/
├── app/
├── components/
├── lib/
├── firebase/
├── types/
├── public/
└── interviewgenerator.json


## 🚀 Getting Started

### 1. Clone Repository
git clone https://github.com/ayushman3704/AI-Interview-Agent.git
cd AI-Interview-Agent

### 2. Install Dependencies
npm install

### 3. Environment Setup

Create `.env.local`:

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=

NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_AI_API_KEY=

FIREBASE_ADMIN_PROJECT_ID=
FIREBASE_ADMIN_PRIVATE_KEY=
FIREBASE_ADMIN_CLIENT_EMAIL=

NEXT_PUBLIC_BASE_URL=


## ▶️ Run Locally

npm run dev

Visit: http://localhost:3000


## 🎯 Use Cases

- SDE interview preparation  
- Behavioral + technical practice  
- Communication improvement  
- AI-based performance evaluation  

## 🚀 Deployment

- Vercel (recommended)
- Firebase Hosting
- Netlify / AWS Amplify

## 📜 License

MIT License

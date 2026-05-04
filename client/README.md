# 🚀 HireMind AI

> Voice-based AI interview platform for realistic, interactive, and feedback-driven interview preparation.

## 📌 Overview

AI Interview Agent is a full-stack, AI-powered interview platform that simulates real-world technical and behavioral interviews using **voice-based conversations**.

It enables users to practice interviews, receive **instant AI feedback**, and track their performance over time — replicating a real interviewer experience.

## ✨ Key Features

- 🎙️ **Voice-Based Interviews (OpenRouter)**
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

## ⚙️ Tech Stack

### Frontend
- React 19
- Tailwind CSS
- shadcn/ui + Radix UI

### Backend / Services
- Firebase (Auth + Firestore + Hosting)
- Open Router 4 (Evaluation and Feedback)

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

- LLM Engine (OpenRouter) → generates questions + evaluates answers  
- Persistence Layer (Firebase) → stores sessions and user data  
- Frontend Layer (ReactJS - for interactive UI)

## 🎯 Use Cases

- SDE interview preparation  
- Behavioral + technical practice  
- Communication improvement  
- AI-based performance evaluation  

## 🚀 Deployment
- Vercel (Frontend)
- Render (Backend)

## 📜 License

MIT License

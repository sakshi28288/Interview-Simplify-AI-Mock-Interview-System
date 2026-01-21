# 🎯 Simplify – AI-Based Mock Interview Platform

Simplify is an AI-powered mock interview platform built with Next.js that helps users practice technical and behavioral interviews in a realistic, on-demand environment.
The platform dynamically generates interview questions, analyzes user responses, and provides structured feedback to improve interview readiness and confidence.

---

## 🚀 Features

### 🤖 AI-Generated Interview Questions
- Generates role-specific technical and HR interview questions using AI-powered prompts.

### 📊 Real-Time Feedback & Scoring
- Evaluates responses based on:
  - Correctness
  - Clarity
  - Confidence
  - Communication skills

### 🎯 Role-Based Interview Modes
- Software Engineer
- Frontend Developer
- Backend Developer
- Data Analyst
- HR / Behavioral Interviews

### 💻 Modern Interactive UI
- Built using Next.js App Router
- Smooth, responsive UI with reusable components

### ⏱️ Session Management
- Start, stop, reset, and track mock interview sessions easily

---

## 🛠️ Tech Stack

- Frontend: Next.js 14 (App Router), TypeScript
- Styling: Tailwind CSS
- UI Components: shadcn/ui
- State Management: React Hooks
- AI Integration: Custom API Routes (OpenAI / Gemini compatible)
- Deployment: Vercel

---

## 📦 Project Structure

Interview-Simplify/
│── app/
│   ├── page.tsx
│   ├── interview/
│   └── api/
│
│── components/
│── public/
│── styles/
│── package.json
│── tsconfig.json
│── next.config.ts
│── README.md

---

## ▶️ Getting Started

### 1️⃣ Clone the Repository
git clone https://github.com/JanaviSingh/Interview-Simplify-AI-based-Mock-Interview-Platform.git
cd Interview-Simplify-AI-based-Mock-Interview-Platform

### 2️⃣ Install Dependencies
npm install
# or
yarn install

### 3️⃣ Run the Development Server
npm run dev

Open http://localhost:3000 in your browser.

---

## 🔧 Environment Variables

Create a .env.local file and add:

OPENAI_API_KEY=your_api_key_here
NEXT_PUBLIC_APP_URL=http://localhost:3000

Replace your_api_key_here with your actual API key.

---

## 📘 How It Works

1. User selects an interview type (Technical / HR / Domain-specific)
2. The app generates dynamic AI-based interview questions
3. User submits responses (text or voice – if enabled)
4. AI evaluates the response using scoring metrics
5. Dashboard displays performance summary, strengths, and improvement suggestions

---

## 📊 Future Enhancements

- Voice-to-text and speech sentiment analysis
- Resume-based personalized interview generation
- User authentication and performance history
- Multi-round interview simulations

---

## 👩‍💻 Author

Sakshi Sinha  
Frontend Developer | Aspiring Full-Stack Engineer

GitHub: https://github.com/your-github-username  
LinkedIn: https://linkedin.com/in/your-linkedin-username

---

## 💡 Interview Explanation (What to Say)

“Simplify is an AI-based mock interview platform built using Next.js. It allows users to practice role-specific interviews and receive structured AI feedback on their answers. The project focuses on realistic interview flow, clean UI, and scalable architecture.”

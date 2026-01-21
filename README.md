# Simplify – AI-Based Mock Interview Platform

Simplify is a final-year student project developed as an AI-based mock interview platform to help students and job seekers prepare for technical and HR interviews. The application provides a realistic interview environment by generating intelligent questions, evaluating user responses, and giving structured feedback for improvement.

---

## Project Description

The goal of this project is to simulate real interview scenarios using artificial intelligence. Users can practice interviews based on different roles and receive instant feedback on their performance. The system focuses on improving communication skills, confidence, and technical understanding through repeated practice.

---

## Features

- AI-generated technical and HR interview questions  
- Role-based interview modes (Software Engineer, Frontend, Backend, Data Analyst, HR)  
- Real-time evaluation of answers based on clarity, correctness, and confidence  
- Interactive and responsive user interface  
- Interview session start, stop, and reset functionality  

---

## Technology Stack

- Frontend: Next.js 14 (App Router), TypeScript  
- Styling: Tailwind CSS  
- UI Components: shadcn/ui  
- State Management: React Hooks  
- AI Integration: Custom API Routes (OpenAI / Gemini compatible)  
- Deployment Platform: Vercel  

---

## Project Structure

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

## Installation and Setup

1. Clone the repository  
git clone https://github.com/JanaviSingh/Interview-Simplify-AI-based-Mock-Interview-Platform.git

2. Navigate to the project directory  
cd Interview-Simplify-AI-based-Mock-Interview-Platform

3. Install dependencies  
npm install  
or  
yarn install  

4. Run the development server  
npm run dev  

Open http://localhost:3000 in the browser.

---

## Environment Variables

Create a `.env.local` file in the root directory and add:

OPENAI_API_KEY=your_api_key_here  
NEXT_PUBLIC_APP_URL=http://localhost:3000  

---

## Working of the System

1. The user selects the type of interview.  
2. The system generates interview questions using AI.  
3. The user submits answers during the session.  
4. The AI analyzes the responses.  
5. Feedback and performance summary are displayed to the user.

---

## Future Scope

- Voice-based interviews with speech analysis  
- Resume-based personalized interview questions  
- User authentication and performance tracking  
- Multi-round interview simulation  

---

## Author

Sakshi Sinha  
Final Year Student – Computer Science / Information Technology

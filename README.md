nterview Simplify – AI-based Mock Interview Platform
An AI-powered mock interview application built with Next.js, designed to help users practice technical and behavioral interviews in a realistic, on-demand format. The platform generates intelligent questions, analyzes user responses, and provides structured feedback to support interview preparation.

🚀 Features
AI-Generated Interview Questions Generates role-specific technical and HR interview questions using integrated AI prompts.

Real-time Feedback & Scoring Evaluates responses for correctness, clarity, confidence, and communication.

Role-based Interview Modes Supports Software Engineer, Data Analyst, Frontend, Backend, HR rounds, and more.

Interactive UI with Next.js App Router Smooth, responsive design with modern components.

Session Tracking Users can start, stop, and reset mock interview sessions easily.

🛠️ Tech Stack
Frontend: Next.js 14 (App Router), TypeScript
Styling: Tailwind CSS
Components: shadcn/ui
State Management: React Hooks
AI Integration: Custom API routes (you can plug in OpenAI / Gemini)
Deployment: Vercel (recommended)
📦 Project Structure
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
▶️ Getting Started
1. Clone the Repository
git clone https://github.com/JanaviSingh/Interview-Simplify-AI-based-Mock-Interview-Platform.git
cd Interview-Simplify-AI-based-Mock-Interview-Platform
2. Install Dependencies
npm install
# or
yarn install
3. Run the Development Server
npm run dev
Open http://localhost:3000 in your browser.

🔧 Environment Variables
Create a .env.local file and add:

OPENAI_API_KEY=your_key_here
NEXT_PUBLIC_APP_URL=http://localhost:3000
(Replace with your actual API key.)

📘 How It Works
User selects an interview type (technical / HR / domain-specific).
App generates dynamic AI questions.
User responds in text or voice (if implemented).
AI evaluates the response using scoring metrics and gives feedback.
The dashboard displays interview summary, strengths, and improvement tips.
📊 Future Enhancements
Voice-to-text and speech sentiment analysis
Resume-based personalized interview generation
User login & performance history
Multi-round interview simulations
📩 Author
Sakshi Sinha

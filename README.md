🚀 ResuMind – AI Powered Resume Analyzer

Smart. Fast. Accurate.
AI-powered resume insights to optimize your job applications instantly.

🌐 Live App: https://ai-resume-analyzer-lovat-omega.vercel.app/

📌 Overview

ResuMind is an intelligent resume analysis platform that evaluates resumes using AI and provides:

📊 Resume scoring
🎯 ATS compatibility insights
🧠 Context-aware suggestions
📄 Keyword optimization guidance
⚡ Real-time feedback

Built using a modern React + TypeScript architecture and powered by Puter.com AI + Cloud Functions, the platform ensures fast, scalable, and secure resume analysis.

✨ Key Features
⚡ Instant AI Resume Analysis

Upload your resume and receive structured feedback within seconds.

🧠 Context-Aware Optimization

Smart suggestions based on:
Job descriptions
Industry keywords
ATS scoring logic
Formatting best practices

🎨 Modern Responsive UI
Built using Tailwind CSS
Fully responsive design
Clean and intuitive user experience
🗺️ Smooth Client-Side Routing
Powered by React Router v7 for seamless navigation.
🔐 Secure File Handling
Uses Puter.js for secure cloud + local file processing.
🧩 Efficient State Management
Zustand ensures lightweight, scalable global state handling.

⚡ Optimized Development Experience

Vite for blazing fast builds
TypeScript for type safety
Modular project structure

🛠️ Tech Stack

🎨 Frontend

React
React Router v7
TypeScript
Tailwind CSS
Zustand
Vite

☁️ Backend / AI Services

Puter.com API
Puter.js (AI Requests + File Handling)

🏗️ Architecture Overview
User Uploads Resume
        ↓
File handled via Puter.js
        ↓
Resume sent to Puter AI Engine
        ↓
AI processes content
        ↓
Structured JSON response returned
        ↓
Frontend renders score + insights

📂 Project Structure
src/
│
├── components/
├── pages/
├── store/          (Zustand state)
├── services/       (AI + API calls)
├── utils/
└── main.tsx

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/YOUR_USERNAME/ai-resume-analyzer.git
cd ai-resume-analyzer
2️⃣ Install Dependencies
npm install
3️⃣ Run Development Server
npm run dev
4️⃣ Build for Production
npm run build
🔐 Environment Variables

🚀 Deployment
Deployed on Vercel for seamless CI/CD.

To deploy manually:

vercel deploy

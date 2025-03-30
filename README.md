# 🎥 AI YouTube Shorts Generator  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/yourusername/ai-shorts-generator/pulls)  
![MERN Stack](https://img.shields.io/badge/Stack-MERN-61DAFB?logo=react&logoColor=white)  
![AI Powered](https://img.shields.io/badge/Powered%20by-AI-FF4F8B?logo=openai)  

> Automatically generate YouTube Shorts with AI-powered scripts, thumbnails, and video assembly  

## ✨ Features  

- **AI Script Writing** (GPT-3.5/4)  
- **Thumbnail Generation** (DALL·E/Stable Diffusion)  
- **Voice Synthesis** (ElevenLabs/Browser TTS)  
- **Video Composition** (FFmpeg)  
- **1-Click Export** (MP4/YouTube)  
- **User Authentication** (JWT)  

## 🛠 Tech Stack  

**Frontend:**  
• React.js + Vite  
• Tailwind CSS  
• Redux Toolkit  

**Backend:**  
• Node.js + Express  
• MongoDB Atlas  

**AI Services:**  
• OpenAI API  
• ElevenLabs API  
• Stable Diffusion API  

## 🚀 Installation  

```bash
# Clone repository
git clone https://github.com/yourusername/ai-shorts-generator.git
cd ai-shorts-generator

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install


⚙️ Configuration

Create .env file in /backend:
env
Copy
OPENAI_API_KEY=your_key
ELEVENLABS_API_KEY=your_key
MONGO_URI=mongodb+srv://...
Start development servers:
bash
Copy
# Backend
cd backend
npm run dev

# Frontend (in new terminal)
cd ../frontend
npm run dev
📂 Project Structure

Copy
ai-shorts-generator/
├── backend/
│   ├── controllers/    # API logic
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API endpoints
│   └── server.js       # Express setup
│
├── frontend/
│   ├── public/         # Static assets  
│   └── src/
│       ├── components/ # React components
│       ├── pages/      # Application screens
│       └── App.js      # Main entry point
│
├── .gitignore
└── README.md
🌟 How It Works?

User inputs topic (e.g., "3 Coding Tips")
AI generates:
📝 Script (via OpenAI)
🖼️ Thumbnail (via DALL·E)
🔊 Voiceover (via ElevenLabs)
System assembles video using FFmpeg
User exports MP4 or shares directly
📸 Screenshots

Script Generator	Thumbnail Gallery	Video Preview
Script	Thumbnail	Video




## 🎥 Demo Video
[![YouTube Demo](https://img.youtube.com/vi/yourvideoid/0.jpg)](https://youtu.be/yourvideoid)

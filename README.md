# 🧠 Debatrix – Real-Time AI Debating Platform

**Debatrix** is a full-stack real-time debating platform where users engage in live debates with an **AI video persona** or other users. Designed for students, learners, and debate enthusiasts, it brings together cutting-edge AI, live transcription, and performance feedback in an immersive, educational experience. Whether you're practicing at a **school or college level**, Debatrix helps you improve argument delivery, logic, and public speaking skills.

---

## 🚀 Features

### 🎤 Real-Time AI Debates
- Debate with an **AI video persona** powered by **GPT-4o** and rendered using D-ID or Synthesia.
- Choose between **School** and **College** levels.
- Get structured AI responses with speaking turns and argument logic.

### 📝 Live Transcription & Feedback
- Real-time **speech-to-text** powered by **Whisper API**.
- Tracks speech pacing, pauses, filler words, and clarity.
- Delivers **visual performance feedback** on the side panel instantly.

### 📊 Leaderboards & Progress Tracking
- Compete on real-time leaderboards based on skill and debate outcomes.
- Personal dashboards with win/loss ratios, growth charts, and skill-level history.
- Auto-generated resume of debate journey.

### 🧠 AI Coaching & Topic Generation
- Get intelligent hints and structured coaching during prep time.
- Instant counter-arguments by AI opponents.
- Support for multiple formats: **Lincoln-Douglas**, **British Parliamentary**, and **Policy Debate**.

### 🎥 Peer Debating 
- Real-time video rooms with **WebRTC**.
- Match with peers based on skill and availability.
- Full moderator tools and judging panels.

---

## 💻 Tech Stack

| Layer           | Tools/Technologies                          |
|----------------|---------------------------------------------|
| Frontend        | React.js, Tailwind CSS, WebRTC              |
| Backend         | Node.js, Express.js, Socket.io              |
| AI/NLP          | OpenAI GPT-4o, Whisper API                  |
| Authentication  | Firebase Authentication                     |
| Database        | MongoDB / PostgreSQL                        |
| Hosting         | Vercel (frontend), Railway / Render (API)   |
| AI Video        | D-ID API or Synthesia (for avatar)          |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/debatrix.git
cd debatrix
```
📅 Project Status
✅ Firebase Authentication
✅ Real-Time Transcription (Whisper)
✅ User Leaderboard
🔄 AI Video Debater 
🔄 Live Peer Debate Room
🔄 AI Scoring System & Judge Feedback

🗓️ Roadmap
 User login/signup with Firebase Auth

 Whisper-based speech-to-text with live updates

 Real-time leaderboard for skill tracking

 AI Persona Debater (video + GPT-4o logic)

 Peer-to-peer live debate rooms

 Post-debate reports and portfolio generation

🤖 How It Works
The user selects debate topic and level (School or College).

A live AI persona joins the session and responds in real time.

Transcription panel shows live analysis of user's speech.

Post-debate feedback is generated based on fluency, pauses, logic, and content.

The user's rank updates in the leaderboard.

👨‍💻 Tools Used This Week
React + Tailwind for frontend design

Whisper API for transcription integration

Firebase Auth for secure login

GPT-4o for debate response logic

MongoDB (planned) for user and debate session data

📚 Resources Used So Far
Frontend built with React.js + Tailwind CSS

Firebase Authentication for user management

All other features (video avatar, peer debate, scoring engine) 

✨ Inspiration
Debatrix was born from the idea of making debate practice accessible, smart, and engaging. We believe AI can coach and simulate high-quality debates, especially for students who want to improve their communication and thinking skills.


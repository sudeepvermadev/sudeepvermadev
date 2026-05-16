# <p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Sudeep%20Verma&fontSize=70&animation=fadeIn&fontAlignY=35" /></p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=6366F1&center=true&vCenter=true&width=435&lines=Software+Engineer;Full+Stack+Developer;AI+Integration+Specialist" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/sudeepvermadev"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:your-email@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.hackerrank.com/sudeepverma2006"><img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" /></a>
</p>

---

### <img src="https://img.shields.io/badge/Technical_Spotlight-1F2937?style=for-the-badge&logo=visual-studio-code&logoColor=6366F1" /> [PrepEdge — AI Mock Interview Coach](https://github.com/sudeepvermadev/aimockinterview)
> **Engineering high-fidelity AI systems for career preparation.**

---

### 📺 Visual Walkthrough

<p align="center">
  <a href="https://drive.google.com/file/d/1u3PeOtdt820JWpEIywgZr5h2KpBsM9WC/view?usp=drive_link" target="_blank">
    <img src="https://img.shields.io/badge/WATCH-FULL%20PLATFORM%20WALKTHROUGH-red?style=for-the-badge&logo=google-drive&logoColor=white" height="35px" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://drive.google.com/file/d/1MrG4uBELyn83R_efhc6RO5kFAFgMZd4V/view?usp=drive_link" target="_blank">
    <img src="https://img.shields.io/badge/WATCH-AI%20INTERVIEW%20EXPERIENCE-blue?style=for-the-badge&logo=google-drive&logoColor=white" height="35px" />
  </a>
</p>

<p align="center">
  <i>Experience the power of PrepEdge in action—from full platform analytics to live AI-driven interview sessions.</i>
</p>

---

### 🚀 Core Features

-   <img src="https://img.shields.io/badge/AI_Core-6366F1?style=flat-square&logo=google-gemini&logoColor=white" /> **Integrated AI Engines**: Leveraged **Google Gemini** & **Vapi AI** for low-latency, voice-first interview simulation and adaptive questioning.
-   <img src="https://img.shields.io/badge/Analytics-007ACC?style=flat-square&logo=google-analytics&logoColor=white" /> **Data Architecture**: Built a multi-tenant **Admin Dashboard** for real-time user performance metrics and financial tracking.
-   <img src="https://img.shields.io/badge/Quality_Assurance-2EC866?style=flat-square&logo=jest&logoColor=white" /> **Robust Reliability**: Implemented **Jest** unit testing for core scoring logic, ensuring 100% data integrity across complex AI transcripts.
-   <img src="https://img.shields.io/badge/Security-D14836?style=flat-square&logo=git&logoColor=white" /> **Clean Engineering**: Adhering to professional standards with rigorous Git history management and security-locked environment variables.

---

### 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,nodejs,firebase,gcp,mysql,postgres,ts,js,git,github,vscode,jest,postman" />
</p>

---

### 🧠 Technical Deep Dive

#### 1. Dual-AI Architecture
PrepEdge leverages two distinct AI systems to provide a seamless experience:
*   **Vapi.ai (Voice Engine)**: Manages the WebRTC connection, handle-offs, and speech-to-text/text-to-speech. This ensures sub-second latency for a natural conversation.
*   **Google Gemini (Analysis Engine)**: Processes the finalized transcript to perform "Technical Benchmarking"—comparing user answers against industry-standard "Ideal Answers."

#### 2. Intelligent Score Extraction
One of the core challenges was parsing numeric scores from conversational AI output. We implemented a **multi-stage regex parser** in `lib/utils.ts` that:
1.  Identifies score patterns (e.g., `85/100`, `Score: 90`).
2.  Handles edge cases like natural language processing for word-based scores (e.g., "Eighty-Five").

#### 3. Real-time Synchronization
The system uses **Firebase Firestore** for real-time state management, allowing the "Live Pro Tips" and "Voice Indicators" to react instantly as the AI processes the candidate's speech.

---

### 🚀 Getting Started

#### Prerequisites
- Node.js (v18+)
- API Keys for Gemini, Vapi, Stripe, and Resend

#### Installation
```bash
git clone https://github.com/sudeepvermadev/aimockinterview.git
cd aimockinterview/my-app
npm install
npm run dev

<div align="center">

# Hi, I'm Shashidhar 👋

**Full-Stack & AI Engineer · Former Lead Software Engineer [@ Spacey Science](https://www.linkedin.com/company/spaceyscience/)**

📍 Hyderabad, Telangana, India

I build production-grade, AI-powered web platforms - from real-time 3D learning interfaces to LLM-backed tutoring systems. Led a cross-functional engineering team at **Spacey Science** to architect and ship an end-to-end multi-app EdTech ecosystem: Google Gemini + LangChain, Redis-backed AI memory, 3D character models, RBAC/ABAC auth, and cloud infrastructure - all on GCP.

Currently open to **Full-Stack, AI/GenAI, or Cloud-adjacent roles.**


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shashi997)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@shashi-eminence)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:9845shashi@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shashi997)

</div>

---

## 🛠️ What I've shipped (Professional Experience)

### 🚀 [Spacey Science](https://www.linkedin.com/company/spaceyscience/) - AI EdTech Platform *(Production, Team Lead)*
>🌐 `app.spaceyscience.com` · `teacher.spaceyscience.com` · `defense.spaceyscience.com`

Led a team to architect and deliver a multi-app educational ecosystem across student, teacher, and admin surfaces. Owned system design, core technical decisions, and end-to-end delivery.

- **Context-Aware AI Tutoring Engine:** Integrated Google Gemini API + LangChain with Redis-backed persistent memory (GCP Memory Store) using a thread-per-user-lesson architecture. Each user session retains full context across interactions, enabling personalized, stateful tutoring at scale - without re-loading state on every request.

- **Immersive 3D Lesson Frontend:** Built a dynamic block-based lesson engine (Narration → Choice → AI Block → Game Interaction → Quiz) with a real-time 3D character model running in-browser via React Three Fiber, Blender, and Mixamo - delivering an immersive, game-like learning experience.

- **Security & Multi-Role Auth:** Engineered a production-grade RBAC/ABAC authorization system using Firebase Custom Claims. Admin and teacher roles are enforced server-side, with fine-grained, consent-based student–teacher data sharing across all three applications - students, teachers, and admins each see only what they're permitted to.

- **Smart Audio Pipeline (GCP TTS + GCS):** Built a cost-optimized, two-tier audio pipeline: static lesson narration blocks are pre-generated and cached in Google Cloud Storage (GCS), while dynamic AI chat responses are generated on-demand via GCP Text-to-Speech. This hybrid approach eliminates redundant TTS calls for static content, keeping costs low and latency minimal as the platform scales.

- **Interactive Tooling & Web Vision:** Engineered a highly interactive suite of admin and student features, including a node-based **Visual Lesson Builder (React Flow)** for dynamic content generation, immersive fly-in mission tracking maps via **Mapbox GL**, and an in-browser privacy layer utilizing **MediaPipe Selfie Segmentation** for real-time webcam background removal.

- Technical docs site built with Astro Starlight

> **Tech Stack:** `React 19` `Node.js` `Firebase` `Gemini API` `LangChain` `GCP Cloud Run` `GCP TTS` `GCS` `Redis (Memory Store)` `Three.js (R3F)` `React Flow` `Mapbox GL` `Astro Starlight` `Docker` `GitHub Actions`

---

## 💡 Featured Engineering Projects (Personal)

### 🌌 Spacey — AI-Powered Interactive Learning Platform
*🔗 [Live Demo](https://spacey-moo9.vercel.app) &nbsp;·&nbsp; [GitHub](https://github.com/shashi997/spacey) &nbsp;·&nbsp; [▶ YouTube Demo](https://www.youtube.com/watch?v=Ie-eOQIOk5w)*

- **AI-Driven Lesson Engine:** Built real-time Q&A and intelligent quiz evaluation using the Google Gemini API — dynamically assessing student answers with context-aware feedback rather than static answer matching.
- **Immersive Audio & Visual Layer:** Integrated Kokoro TTS for high-quality in-lesson narration and Three.js for animated 3D space environments, significantly increasing engagement compared to static slide-based content.
- **Auth & Progress Persistence:** Implemented secure user authentication and lesson progress tracking using Firebase Auth + Firestore — storing user profiles, lesson state, and quiz history across sessions.
- **Fully Responsive UI:** Designed and built with React + Tailwind CSS, delivering a consistent experience across desktop and mobile.

> **Stack:** `React` `Node.js` `Gemini API` `Kokoro TTS` `Three.js` `Firebase` `Firestore` `Tailwind CSS` `Vite`

---

### 🎯 AI Word Guesser — Wordle with an AI Brain
*🔗 [GitHub](https://github.com/shashi997/AI-WORD-GUESS) &nbsp;·&nbsp; [▶ YouTube Demo](https://www.youtube.com/watch?v=dAyt_qC5xpE)*

- **Gemini-Powered Word Selection:** Leveraged the Google Gemini API for dynamic, difficulty-aware word selection and context-sensitive clue generation — going beyond a static word list to create an adaptive challenge.
- **Rich Completion Experience:** On game completion, delivers full word breakdowns including definitions, usage examples, and contextual info — turning a game into a vocabulary learning moment.
- **Real-Time Feedback Loop:** Built a responsive React + Express frontend with instant per-guess feedback, animated state transitions, and session tracking for streaks and history.

> **Stack:** `React` `Node.js` `Express.js` `Gemini API`

---

## 📦 Other Projects

| Project | What it does | Stack | Links |
| :--- | :--- | :--- | :--- |
| **Galaxy Glide** | Interactive 3D solar system with realistic orbital mechanics and Google OAuth2. Published in IJIRSET (peer-reviewed). | Three.js · MERN · OAuth2 · MongoDB | [Live](https://galaxy-glide-frontend.vercel.app/) · [GitHub](https://github.com/shashi997/Galaxy-Glide) · [Paper ↗](https://ijirset.com/upload/2025/march/288_Galaxy.pdf) |
| **Real-time Chat App** | Full-stack multi-room chat with Socket.IO bidirectional comms and MongoDB persistence. | Socket.IO · MERN · REST APIs | [GitHub](https://github.com/shashi997/chatapp) · [▶ Demo](https://www.youtube.com/watch?v=W5jYJ6t6mDs) |

---

## 🛠️ Technical Skills & Tools

### 🤖 AI & GenAI
<p align="left">
  &nbsp;<img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Vertex AI" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white" alt="LangChain" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/MediaPipe-00C4CC?style=flat-square&logo=mediapipe&logoColor=white" alt="MediaPipe" />&nbsp;
</p>

### 💻 Frontend & 3D Interactive
<p align="left">
  &nbsp;<img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white" alt="Astro" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white" alt="Framer Motion" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Zustand-000000?style=flat-square&logo=react&logoColor=white" alt="Zustand" />&nbsp;
</p>

### ⚙️ Backend, Cloud & Databases
<p align="left">
  &nbsp;<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />&nbsp;
</p>

### 🔤 Languages
<p align="left">
  &nbsp;<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white" alt="Java" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />&nbsp;
  &nbsp;<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />&nbsp;
</p>

---

## 📺 My YouTube Videos

<div align="center">
<table border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center" valign="top" width="33%">
      <a href="https://www.youtube.com/watch?v=Ie-eOQIOk5w" target="_blank">
        <img src="https://ytcards.demolab.com/?id=Ie-eOQIOk5w&title=Explore+Spacey%3A+AI--Powered+Lessons%2C+Smart+Quizzes+%26+More%21&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&max_title_lines=2&width=280&border_radius=8" alt="Explore Spacey: AI-Powered Lessons, Smart Quizzes & More!" />
      </a>
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://www.youtube.com/watch?v=dAyt_qC5xpE" target="_blank">
        <img src="https://ytcards.demolab.com/?id=dAyt_qC5xpE&title=AI+Word+Guesser%3A+Wordle+with+an+AI+Brain+%28Google+Gemini+%26+MERN%29&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&max_title_lines=2&width=280&border_radius=8" alt="AI Word Guesser: Wordle with an AI Brain (Google Gemini & MERN)" />
      </a>
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://www.youtube.com/watch?v=W5jYJ6t6mDs" target="_blank">
        <img src="https://ytcards.demolab.com/?id=W5jYJ6t6mDs&title=Real--Time+Chat+App+with+MERN+Stack+%26+Socket.IO+%F0%9F%92%AC&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&max_title_lines=2&width=280&border_radius=8" alt="Real-Time Chat App with MERN Stack & Socket.IO 💬" />
      </a>
    </td>
  </tr>
</table>

<br/>

[![Subscribe to YouTube Channel](https://img.shields.io/badge/Subscribe_To_Channel-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/channel/UC7GdavKjWNi9lictm2zXmQw?sub_confirmation=1)
</div>


---

## 🔥 GitHub Stats

<div align="center">
<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=shashi997&show_icons=true&theme=graywhite&hide_border=true" alt="Shashidhar's GitHub Stats" height="195"/>
    </td>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shashi997&layout=compact&theme=graywhite&hide_border=true&langs_count=8" alt="Top Languages" height="195"/>
    </td>
  </tr>
</table>
</div>

---

## 📄 Publication

**Galaxy Glide: 3D Solar System Visualization** — *IJIRSET, March 2025*
Peer-reviewed, refereed, and indexed open access journal.
[Read the paper ↗](https://ijirset.com/upload/2025/march/288_Galaxy.pdf)

---

<div align="center">
  <sub>Open to work · <a href="mailto:9845shashi@gmail.com">9845shashi@gmail.com</a> · <a href="https://linkedin.com/in/shashi997">LinkedIn</a></sub>
</div>

<!--
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shashi997&layout=compact)
**shashi997/shashi997** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

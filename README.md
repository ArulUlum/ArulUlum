<h1 align="center">Hi 👋, I'm Andi Muh. Syahrul Ulum</h1>
<h3 align="center">Backend Developer | Full Stack Developer | AI/ML Enthusiast</h3>

<p align="center">
  <a href="https://linkedin.com/in/syahrululum">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:syahrululum1911@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://wa.me/6282296499244">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
  <img src="https://img.shields.io/badge/Location-Jakarta%2C%20Indonesia-informational?style=flat" alt="Location"/>
</p>

---

### 🧭 About Me

- 🎓 Computer Science graduate from **Telkom University** (GPA 3.56/4.00)
- 💼 Currently a **Backend Developer** at **PT Swamedia Informatika**
- 🐍 Hands-on experience with **Python (Flask, FastAPI)**, **PostgreSQL**, **WebMethods**, and **APIGW**
- 🧠 Big interest in **Artificial Intelligence, Machine Learning, and Deep Learning**
- 🚀 Currently building **[Kebbu.id](https://github.com/ArulUlum)** — a full ticketing platform with 80+ REST API endpoints, payment gateway integrations, and CI/CD pipelines
- 📚 Also taught as a Practicum Assistant and Assistant Lecturer (AI) at Telkom University — details below

---

### 🛠️ Tech Stack

**Languages & Frameworks**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java"/>
</p>

**Databases**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white" alt="MariaDB"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" alt="MongoDB"/>
</p>

**Tools & Platforms**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" alt="Nginx"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" alt="Vercel"/>
  <img src="https://img.shields.io/badge/WebMethods-FF6600?style=flat" alt="WebMethods"/>
</p>

---

### 💼 Experience

**PT Swamedia Informatika** — Backend Developer & Operations Team _(Mar 2023 – Present)_
Building backend logic with Python Flask, writing PostgreSQL queries, integrating APIs via WebMethods/APIGW, monitoring service health, and handling production deployments.

**Telkom Indonesia** — Backend Developer Intern _(Feb 2022 – Dec 2022)_
Built backend logic with Node.js, connected SQL (MariaDB) and NoSQL (MongoDB) databases, and deployed with Docker.

**Telkom University** — Practicum Assistant of Computer Science _(2022 – 2023)_
Supervised practitioners during practicums, reviewed their questions, and assessed practicum results.

**Telkom University** — Assistant Lecturer, Artificial Intelligence _(2021 – 2022)_
Taught AI fundamentals (searching, reasoning, and learning) and helped students with their final AI course projects.

---

### 🚀 Featured Projects

#### 🎟️ [Kebbu.id](https://kebbu.id) (Full Stack Developer)

- Built 80+ REST API endpoints (FastAPI) for auth, events, tickets, payments, and images; migrated backend from Flask to FastAPI (SQLAlchemy 2.0, Pydantic)
- Implemented JWT auth and Google OAuth login; integrated Xendit, Midtrans, and Cring QRIS payment gateways with webhooks and scheduled invoice auto-expiry (APScheduler)
- Built automated e-ticket delivery (QR code + PDF generation, email via Resend) and image storage via Cloudinary
- Built the frontend with React, Vite, and Tailwind CSS: QR check-in scanner and an organizer analytics dashboard (Recharts)
- Set up CI/CD: Dockerized backend, auto build/push to Docker Hub via GitHub Actions, deployed to a VPS behind Nginx with Let's Encrypt SSL; frontend hosted on Vercel

#### 🎬 [Clipperul](https://github.com/ArulUlum/Clipperul) — AI Video Clipping & Publishing Platform

- Turns long-form videos (file upload or YouTube link) into short vertical clips and publishes them to social media from a single editor
- Built the AI pipeline: faster-whisper transcription plus a pluggable LLM layer (OpenAI-compatible, Anthropic, Gemini, or local Ollama) that detects the video category, scores moments on hook, flow, value, and trend, and writes clip titles in the video's own language
- Built video processing with FFmpeg and OpenCV: automatic cutting, face-tracking smart crop, multiple aspect ratios, and burned-in subtitles with category-matched presets
- Built a tabbed clip editor with Next.js 15, React 19, and Tailwind CSS: trim, ratio, crop, subtitles, details, and post, all with live preview
- Implemented multi-account publishing with OAuth: post now or on a schedule, real upload progress, cancellation, and automatic retries with backoff (live on YouTube; TikTok pending platform API approval)
- Added an optional daily auto clip that picks a trending YouTube video, clips it, and posts the best clips at randomized intervals
- Designed a queue-based backend with FastAPI, Celery + Redis, PostgreSQL, and S3-compatible storage, streaming progress over server-sent events; runs on Docker Compose

#### 🤖 [Agent Arul](https://github.com/ArulUlum/agent-arul) — Self-Hosted Telegram AI Agent

- Built a self-hosted Telegram bot in Python that controls a Windows 11 laptop, with commands for system status, screenshots, files, shell, and browser tasks
- Built an agent mode where natural-language messages drive an LLM function-calling loop over an OpenAI-compatible endpoint, with automatic fallback to a JSON prompt mode when native tools are rejected
- Added permanent memory and conversation history that survive restarts, plus document reading (PDF and text files)
- Automated logged-in websites with Playwright and a dedicated browser profile, and desktop apps through window control, keyboard/mouse input, and clipboard transfer between apps
- Implemented code hot-reload without restarting: validation in an isolated namespace, a health check, and automatic rollback on failure
- Hardened it for personal use: owner-only access, button confirmation for risky actions, and automatic redaction of secrets in logs

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=ArulUlum&show_icons=true&theme=default&count_private=true" alt="Andi's GitHub stats" height="165"/>
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=ArulUlum&layout=compact&theme=default" alt="Top Languages" height="165"/>
</p>

---

### 📫 Let's Connect

<p align="left">
  <a href="https://linkedin.com/in/syahrululum">LinkedIn</a> ·
  <a href="mailto:syahrululum1911@gmail.com">Email</a> ·
  <a href="https://wa.me/6282296499244">+62 822-9649-9244</a>
</p>

# Agam Latifullah

**Software Engineer (Full-Stack) | TypeScript & Go (Golang)**  
Building production web applications from database & API design to cloud deployment — focused on clean architecture, low-latency performance, and maintainable code.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-agam--latifullah-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/agam-latifullah/)
[![Email](https://img.shields.io/badge/Email-agam.latiff%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:agam.latiff@gmail.com)
[![Live Project](https://img.shields.io/badge/Live%20Demo-Merantalk-2563EB?style=flat&logo=vercel&logoColor=white)](https://merantalk.vercel.app)

---

## Featured Project

### [Merantalk](https://merantalk.vercel.app) — Full-Stack Multi-Language Learning Platform
End-to-end gamified language learning platform engineered for Indonesian learners targeting international proficiency standards (**JLPT N5–N1** & **CEFR A1–C2** live in production, with schema modeling 6 global language tracks).

**Live Demo:** https://merantalk.vercel.app

#### Technical Architecture & Engineering Highlights
| Layer | Implementation Details |
| :--- | :--- |
| **Backend API** | **Go 1.25+ & Gin** with **Modular Clean Architecture** across **10 domain modules** (`auth`, `curriculum`, `exercise`, `flashcard`, `gamification`, `language`, `leaderboard`, `onboarding`, `user`, `health`) and **50+ REST API endpoints** documented via **OpenAPI 3.0** |
| **Database & Migrations** | **PostgreSQL 16 (Neon Serverless)** with **32 normalized tables**, **43 indexes**, **JSONB** payloads, and **17 versioned SQL migrations** powering 6,000+ exercises, 700+ lessons, 100+ grammar guides, and 2,500+ flashcards |
| **Caching & Auth** | **Upstash Redis (TLS)** for curriculum caching, rate limiting, and **30-day rotated refresh tokens** paired with **15-min JWT access tokens** and **Google OAuth 2.0** |
| **Frontend Architecture** | **React 19, TypeScript 5.9 (strict, zero-`any`), Vite, Tailwind CSS v4** using **Feature-Sliced + Headless Hook** architecture, **TanStack Query v5**, and **Zustand** across **15+ pages** |
| **Interactive Systems** | **4-skill practice engine** (`fill_blank`, `listening_choice`, `sentence_builder`, `speaking_repeat`), browser **Web Speech API** (TTS `1.0x`/`0.6x` + Speech Recognition with manual typing fallback), **HTML5 drawing canvas** for 270+ Kana/Kanji, SRS review scheduling, and 3-tier access gating (`Guest Trial`, `Free`, `Pro`) |
| **Performance & Quality** | Co-located backend & database in **Singapore (`sin1` / `ap-southeast-1`)**, Redis caching, loading skeletons, double-submit guards, **270+ automated Go tests**, and spec-driven AI-assisted engineering (**PRD → ERD → OpenAPI**) |

---

## Technical Stack

- **Languages:** Go (Golang), TypeScript, JavaScript, SQL, HTML/CSS
- **Frontend:** React, Next.js, Tailwind CSS, TanStack Query, Zustand, Axios, Vite
- **Backend:** Gin, Node.js, Express, RESTful APIs, JWT, OAuth 2.0, OpenAPI 3.0
- **Data & Caching:** PostgreSQL, MySQL, Redis
- **DevOps & Tools:** Docker, Vercel, Git, GitHub, Postman, DBeaver, LLM / Agentic AI Workflows
- **Architecture:** Clean Architecture, Layered Architecture, Feature-Sliced Design, MVC

---

## Currently Focused On

- Deepening **Go backend engineering**, PostgreSQL query/index optimization, and Redis caching patterns
- Improving product UX and scalability on **Merantalk**
- Open to **Junior Full-Stack / Backend Software Engineer** opportunities (TypeScript & Go)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=e8643c&height=120&section=header&text=Khushi%20Sharma&fontSize=42&fontColor=ffffff&fontAlignY=65&desc=Java%20Backend%20Developer&descSize=18&descAlignY=85&descColor=ffffff" width="100%"/>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-khushissharma-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khushissharma)
[![Twitter](https://img.shields.io/badge/Twitter-sharmaa__khushii-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/sharmaa_khushii)
[![Gmail](https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharmakhushi99631@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-287%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/sharmaa_khushii)

</div>

---

## About

Final-year ECE student at LNCT Bhopal building backend systems with **Java & Spring Boot** — focused on clean architecture, transactional correctness, and APIs that work in production.

Every project I ship has real DB constraints, real transactions, and real error handling. Not just `localhost` code.

Currently looking for **Java Backend Developer / Full Stack roles**.

---

## Tech Stack

```
Backend     →  Java 17 · Spring Boot 3.x · Spring Data JPA · Hibernate · REST APIs
                Transaction Management · State Machine Logic · JavaMailSender
Frontend    →  React 19 · JavaScript ES6+ · Tailwind CSS v4 · HTML5 · CSS3
Database    →  PostgreSQL · MySQL · JDBC · Schema Design
DevOps      →  Docker · Git · GitHub Actions · Maven · Render · Vercel · Neon
AI/ML       →  Groq API · Llama 3.3 70B · Prompt Engineering
```

---

## Projects

### ✈️ SkyTrack — Flight Delay Alert System
> `Spring Boot` `PostgreSQL` `React` `JPA/Hibernate` `Docker` `JavaMailSender` `State Machine`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-46E3B7?style=for-the-badge&logo=vercel&logoColor=black)](https://flight-delay-frontend-seven.vercel.app)
[![Backend](https://img.shields.io/badge/Backend-181717?style=for-the-badge&logo=github)](https://github.com/sharmakhushi18/flight-delay-alert-api)
[![Frontend](https://img.shields.io/badge/Frontend-181717?style=for-the-badge&logo=github)](https://github.com/sharmakhushi18/skytrack-frontend)

Event-driven Spring Boot API — when a flight is delayed or cancelled, alerts auto-generate for all booked passengers and real emails fire instantly.

- State machine enforces valid flight status transitions at the service layer — invalid transitions rejected before DB touch
- `@Transactional` ensures status change + alert creation rollback **atomically** on failure — no partial state
- Email wrapped in try-catch — alert DB persistence guaranteed even if SMTP fails
- Deployed on Render with PostgreSQL (Neon) via Docker

---

### 🤖 AI Resume Reviewer
> `React 19` `Vite 8` `Tailwind CSS v4` `Groq API` `Llama 3.3 70B` `Prompt Engineering` `Vercel`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-46E3B7?style=for-the-badge&logo=vercel&logoColor=black)](https://resume-reviewer-nu.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/sharmakhushi18/resume-reviewer)

AI-powered resume analyzer — paste a resume + job description, get instant structured feedback in seconds.

- Engineered a structured JSON prompt pipeline to extract **6 outputs in a single API call** — match score, ATS score, keyword gaps, strengths, weaknesses, improvement tips
- Integrated Llama 3.3 70B via Groq API with async response handling, loading states, and structured result rendering
- Deployed on Vercel with CI/CD — **7 production deployments** with proper env variable management and `.gitignore` discipline
- Sole developer — owned full stack: prompt engineering, frontend logic, API integration, deployment, documentation

---

### 🛫 Airport Management System
> `Java` `JDBC` `MySQL` `DAO Pattern` `OOP`

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/sharmakhushi18/AirportManagementSystem)

Console-based Java app with full CRUD for passengers, flights, and bookings using raw JDBC and strict DAO architecture.

- Duplicate seat validation enforced at **DB level via unique constraints** — not just application layer
- Booking cancellation auto-restores seat count — no inconsistent state possible
- Zero logic leaking into persistence layer — clean DAO separation throughout

---

## LeetCode Stats

<div align="center">

| Problems Solved | Hard | Contest Rating | Global Rank | Max Streak |
|:-:|:-:|:-:|:-:|:-:|
| **287+** | **50** | **1,556** | **Top 30%** | **62 days** |

[![LeetCode](https://img.shields.io/badge/LeetCode-sharmaa__khushii-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/sharmaa_khushii)

</div>

---



<div align="center">

*Open to Java Backend Developer · Full Stack · Remote & On-site roles*

**Let's build something → [sharmakhushi99631@gmail.com](mailto:sharmakhushi99631@gmail.com)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=e8643c&height=80&section=footer" width="100%"/>

</div>

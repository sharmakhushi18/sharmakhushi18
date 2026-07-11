<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=FF6B35&height=180&section=header&text=Khushi%20Sharma&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%7C%20Spring%20Boot%20%E2%80%A2%20PostgreSQL%20%E2%80%A2%20React&descAlignY=58&descSize=17&animation=fadeIn" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=FF6B35&center=true&vCenter=true&width=650&lines=Java+%2F+Spring+Boot+Backend+Engineer;Microservices+%C2%B7+Concurrency+%C2%B7+PostgreSQL;Building+systems+that+work+in+production;Data+Analytics+%7C+SQL+%7C+KPI+Dashboards)](https://git.io/typing-svg)

<br/>

🟢 **Open to opportunities — Backend Engineer / Full Stack Developer · Immediately Available**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khushissharma)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B35?style=for-the-badge&logo=vercel&logoColor=white)](https://sharmakhushi18.github.io/portfolio)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharmakhushi6203@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-181717?style=for-the-badge&logo=googledocs&logoColor=white)](https://sharmakhushi18.github.io/portfolio)

</div>

---

## About Me

I'm a recent B.Tech (ECE) graduate building **backend systems that hold up under real concurrency** — not just CRUD apps. My projects deliberately mix locking strategies (pessimistic vs. optimistic), event-driven design, and clean DAO/service layering, because that's the part of backend work I actually enjoy solving.

I also work on the analytics side — SQL-heavy dashboards for risk and supply-chain reporting — which gives me a rare mix: I can build the system **and** reason about the business metrics it should produce.

```java
public class KhushiSharma extends BackendEngineer {

    String college   = "LNCT Bhopal — B.Tech ECE, Class of 2026";
    String location  = "Bhopal, India";
    String status    = "Open to opportunities · Immediately available";

    String[] coreStack = {
        "Java 17", "Spring Boot 3.x", "Spring Security + JWT",
        "PostgreSQL", "Docker", "React.js"
    };

    String[] analyticsStack = {
        "Advanced SQL", "Python (pandas)", "Excel/Power BI Dashboards",
        "KPI Design", "Operational Risk & Supply Chain Analytics"
    };

    String currentFocus() {
        return "GSSoC 2026 Contributor — open source, backend systems, AI integrations";
    }
}
```

---

## Tech Stack

<div align="center">

**Backend**
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Hibernate](https://img.shields.io/badge/JPA_Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Data & Analytics**
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python_pandas-3776AB?style=flat-square&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Database & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Frontend & Tools**
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

## Featured Projects

### Backend & Full Stack

| Project | What it does | Notable engineering | Tech | Links |
|---|---|---|---|---|
| **SkyTrack — Flight Delay Alert System** | Event-driven API that auto-notifies passengers on flight delays, with a React dashboard on top. | State-machine-driven flight status, **pessimistic locking** to prevent race conditions on seat/status updates | Spring Boot · React · PostgreSQL · Docker | [Live](https://flight-delay-frontend-seven.vercel.app) · [API Docs](https://flight-delay-alert-api.onrender.com/swagger-ui/index.html) · [Repo](https://github.com/sharmakhushi18/flight-delay-alert-api) |
| **PayFlow — Wallet Microservices** | Digital wallet system split into 4 microservices: auth, wallet, transactions, notifications. | **Pessimistic locking** on wallet balance — prioritizes correctness over throughput, since a wrong balance is far costlier than a queued request | Spring Boot · Microservices · Redis · Docker | [Repo](https://github.com/sharmakhushi18/payflow-wallet-api) |
| **AI Resume Reviewer** | Scores resumes against job descriptions, flags keyword gaps and suggests fixes. | LLM-powered scoring pipeline via Groq API | React · Vite · Tailwind · Groq API | [Repo](https://github.com/sharmakhushi18/resume-reviewer) |
| **Airport Management System** | Console-based system for managing passengers, flights, and bookings. | Raw JDBC (no ORM), DAO architecture, seat-conflict validation enforced at the DB level | Java · JDBC · MySQL | [Repo](https://github.com/sharmakhushi18/AirportManagementSystem) |

### Analytics & Reporting

| Project | What it does | Scope | Tech | Links |
|---|---|---|---|---|
| **Operational Risk Analytics Dashboard** | End-to-end risk reporting for a banking-style dataset. | 600 records · 9 KPIs · SLA compliance tracking · escalation analysis · 9 SQL queries | Excel · SQL · Python | [Repo](https://github.com/sharmakhushi18/operational-risk-analytics-dashboard) |
| **Supply Chain Analytics Dashboard** | Logistics performance dashboard for vendor and shipment tracking. | 550 shipment records · vendor scoring · OTD tracking · stockout alerts · monthly trends | Excel · SQL · Python | [Repo](https://github.com/sharmakhushi18/supply-chain-logistics-analytics) |

> A note on the locking choice: both SkyTrack (seat booking) and PayFlow (wallet balance) use pessimistic locking deliberately — in both cases, a wrong result (double-booked seat, incorrect balance) is far more costly than a briefly queued request. Combined with a DB-level unique constraint as the final safety net in SkyTrack, this reflects the same underlying judgment call: when correctness is non-negotiable, block first, optimize throughput later.

---

## GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=sharmakhushi18&show_icons=true&theme=tokyonight&hide_border=true&title_color=FF6B35&icon_color=FF6B35&text_color=c9d1d9&bg_color=0d1117&count_private=true" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sharmakhushi18&layout=compact&theme=tokyonight&hide_border=true&title_color=FF6B35&text_color=c9d1d9&bg_color=0d1117&langs_count=6" />

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=sharmakhushi18&theme=tokyonight&hide_border=true&stroke=FF6B35&ring=FF6B35&fire=FF9A6C&currStreakNum=ffffff&currStreakLabel=FF6B35&sideNums=ffffff&sideLabels=c9d1d9&background=0d1117&dates=c9d1d9" />

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=sharmakhushi18&theme=tokyo-night&hide_border=true&color=FF6B35&line=FF6B35&point=ffffff&area=true&area_color=FF6B3520)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## Problem Solving

<div align="center">

[![LeetCode](https://leetcard.jacoblin.cool/sharmaa_khushii?theme=dark&font=JetBrains%20Mono&ext=heatmap&border=0&radius=16)](https://leetcode.com/sharmaa_khushii)

| Solved | Hard | Contest Rating | Max Streak | Global Rank |
|:-:|:-:|:-:|:-:|:-:|
| 287+ | 50 | 1556 | 62 days | Top 30% |

</div>

---



---

## What I'm Looking For

```
Roles       Backend Engineer · Full Stack Developer
            Data Analyst · Business/Operations Analyst
Available   Immediately (B.Tech ECE, LNCT Bhopal — Class of 2026)
Looking for Teams that care about code quality and ship real systems —
            not just localhost demos.
Contact     sharmakhushi6203@gmail.com
```

<div align="center">

**Build systems that work in production — not just on localhost.**

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khushissharma)
[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharmakhushi6203@gmail.com)
[![Portfolio](https://img.shields.io/badge/View_Portfolio-FF6B35?style=for-the-badge&logo=vercel&logoColor=white)](https://sharmakhushi18.github.io/portfolio)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=FF6B35&height=100&section=footer&animation=fadeIn" />

</div>

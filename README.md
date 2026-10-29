<!--
  Dhairya Oza · GitHub profile README
  Lives at github.com/Dhairya-007/Dhairya-007 — this file renders on the profile page.

  Positioning: full-stack engineer who builds AI into the stack.
  Frontend and backend lead; the cross-platform client work sits further down.

  Palette (keep these consistent if you edit):
    deep navy #0B1020
    indigo    #4F46E5
    violet    #7C3AED
    teal      #0E7C6B

  THINGS TO FILL IN LATER
    - The AI section is the thinnest part of the public story. Ship 2-3 AI repos
      (agent harness, a RAG service, an n8n workflow pack) and link them here.
    - Push Siddheshwari Investment to a public repo and link it in the table.
    - Pin: citrine-growth, detonator, portfolio, DSA, GushWorks
      (profile -> Customize your pins).
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:4F46E5,100:7C3AED&height=200&section=header&text=Hi%2C%20I%27m%20Dhairya&fontColor=ffffff&fontSize=46&fontAlignY=36&desc=Full-Stack%20Engineer%20%C2%B7%20AI%20%26%20Agentic%20Systems&descAlignY=56&descSize=18" alt="Hi, I'm Dhairya" />
</p>

<p align="center">
  <a href="https://github.com/Dhairya-007">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=7C3AED&center=true&vCenter=true&width=700&lines=Full-stack+engineer+at+Halma+plc;Angular+%C2%B7+Next.js+%C2%B7+NestJS+%C2%B7+PostgreSQL+%C2%B7+Kafka;I+build+LLM+agents+and+automation+into+the+stack;RAG%2C+agent+harnesses+and+n8n+orchestration;From+the+database+to+the+dashboard" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dhairya-oza-7723b2200/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://dhairyaoza007.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0E7C6B?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:ozadhairya73@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## 👋 About me

I'm a **full-stack engineer** at **Halma plc**, building the whole path: PostgreSQL schemas and NestJS services at the back, Kafka and Redis in the middle, Angular and Next.js dashboards at the front, and Docker/Kubernetes underneath it all.

The half I'm most interested in right now is **AI in the engineering loop**. I've built a custom **LLM agent harness** and **n8n** automation that my team uses daily, and I work with RAG, vector search and agentic frameworks like BMAD and GSD. Not models — systems: the orchestration, the tool layer, the retrieval, and the glue that makes an agent useful instead of impressive.

I studied Computer Science at **SVNIT Surat**, graduating in 2024 ranked 5th of 135 with a 9.19 CGPA.

<p align="left">
  <img src="https://img.shields.io/badge/Full--Stack-4F46E5?style=flat-square&logoColor=white" alt="Full-Stack" />
  <img src="https://img.shields.io/badge/AI_%26_Agents-7C3AED?style=flat-square&logoColor=white" alt="AI and Agents" />
  <img src="https://img.shields.io/badge/Distributed_Systems-0E7C6B?style=flat-square&logoColor=white" alt="Distributed Systems" />
  <img src="https://img.shields.io/badge/Cloud_%26_DevOps-C98A12?style=flat-square&logoColor=white" alt="Cloud and DevOps" />
</p>

---

## 🏗️ Full-stack engineering

### 🌐 Sensor data platform · `Angular` `NestJS` `PostgreSQL` `Kafka`

`Halma plc` &nbsp; `2024 – present`

A platform that ingests high-volume sensor data and puts it in front of customers as live dashboards. I work across the whole stack on it.

**Backend**
- Engineered the **REST API surface** and backend services on **NestJS**.
- Built the ingestion path with **Apache Kafka** event streaming, **Redis** caching and **BullMQ** job queues, so high-volume sensor data lands reliably instead of dropping under burst load.
- Designed for scale and fault tolerance — the data arrives faster than any single service wants to handle.

**Frontend**
- Built real-time **HighCharts** visualizations on Angular, including interactive **wind-rose plots** and correction dashboards, so customers can read live field data at a glance.

**Infrastructure**
- Containerized services with **Docker**, deployed on **Kubernetes**, and wired up **CI/CD pipelines** for scalable, fault-tolerant releases.

**Performance**
- Refactored data-intensive modules and optimized LiteDB queries in a legacy UWP desktop app — reports and grids load up to **75% faster**.

---

## 🤖 AI and agentic engineering

### 🧠 LLM agent harness and workflow automation

`Halma plc`

The part of my work I'd happily talk about all day. I build the systems around models, not the models themselves.

- Built a **custom LLM agent harness** for internal use — the orchestration layer that gives a model a tool surface, a context budget and a place to fail safely.
- Built internal automation on **n8n** workflow orchestration, wiring engineering tasks into repeatable pipelines.
- Researched and integrated **agentic AI development frameworks** — **BMAD** and **GSD** — into the team's daily engineering workflow.

**What I work with:** LLM APIs (Claude, OpenAI) · prompt engineering · **RAG** · vector search · agentic workflows · tool/function calling · n8n

<p align="left">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/RAG-0E7C6B?style=for-the-badge&logoColor=white" alt="RAG" />
  <img src="https://img.shields.io/badge/Agentic_Workflows-4F46E5?style=for-the-badge&logoColor=white" alt="Agentic Workflows" />
</p>

### How I think about agent systems

```mermaid
flowchart LR
    R[Request]
    P[Planner<br/>decompose the task]
    C[Context layer<br/>RAG · vector search]
    T{Tool surface}
    T1[Repo and files]
    T2[APIs and services]
    T3[Shell and CI]
    E[Execute step]
    V[Verify<br/>tests · checks]
    O[Result]

    R --> P
    P --> C
    C --> T
    T --> T1 & T2 & T3
    T1 & T2 & T3 --> E
    E --> V
    V -- needs another pass --> P
    V -- done --> O

    classDef entry fill:#0B1020,stroke:#0B1020,color:#fff
    classDef brain fill:#7C3AED,stroke:#7C3AED,color:#fff
    classDef tool fill:#4F46E5,stroke:#4F46E5,color:#fff
    classDef check fill:#0E7C6B,stroke:#0E7C6B,color:#fff
    class R,O entry
    class P,C brain
    class T,T1,T2,T3 tool
    class E,V check
```

---

## 🧩 Full-stack projects

| Project | What it is | Stack | Links |
| --- | --- | --- | --- |
| **Citrine Growth** | A digital agency platform — marketing site plus a full admin panel, with dual light/dark theming throughout. | Next.js 14 · NestJS · Prisma · PostgreSQL | [Code](https://github.com/Dhairya-007/citrine-growth) |
| **Detonate the Bomb** | A browser puzzle game: 50 hand-built levels, instruction-driven gameplay, timer system, scoring and level progression, all client-side. | Next.js · TypeScript · CSS3 | [Live](https://detonatebomb.netlify.app/) · [Code](https://github.com/Dhairya-007/detonator) |
| **Portfolio** | A single-page portfolio built as a Formula 1 racing dashboard — 10+ custom animations, dynamic gauges, interactive navigation, responsive to phone width. | Next.js · TypeScript · CSS animations | [Live](https://dhairyaoza007.netlify.app/) · [Code](https://github.com/Dhairya-007/portfolio) |
| **Siddheshwari Investment** | A business site for an investment firm: 10+ content sections, tuned for load performance and cross-browser support. | Angular · TypeScript · Netlify | [Live](https://siddheshwariinvestment.netlify.app/) |
| **DSA** | Where my data structures and algorithms practice lives. | Java | [Code](https://github.com/Dhairya-007/DSA) |

---

## 🔌 The shape of what I build

End to end, most of my work is this path:

```mermaid
flowchart LR
    SRC[Data sources<br/>sensors · clients]
    API[NestJS<br/>REST API]
    Q[Kafka · BullMQ<br/>Redis]
    SVC[Services<br/>processing]
    DB[(PostgreSQL)]
    UI[Angular · Next.js<br/>HighCharts dashboards]
    AI[LLM agents<br/>n8n automation]
    K8S[Docker · Kubernetes<br/>CI/CD]

    SRC --> API
    API --> Q
    Q --> SVC
    SVC <--> DB
    SVC --> UI
    AI --> API
    DB --> AI
    K8S -.- API
    K8S -.- SVC

    classDef edge fill:#0B1020,stroke:#0B1020,color:#fff
    classDef back fill:#4F46E5,stroke:#4F46E5,color:#fff
    classDef data fill:#0E7C6B,stroke:#0E7C6B,color:#fff
    classDef front fill:#C98A12,stroke:#C98A12,color:#fff
    classDef ai fill:#7C3AED,stroke:#7C3AED,color:#fff
    class SRC edge
    class API,SVC back
    class Q,DB data
    class UI front
    class AI ai
    class K8S edge
```

---

## 📱 Also: cross-platform client work

The front end of that platform isn't only a browser. At Halma I also lead the mobile and desktop clients that talk to the hardware directly:

- **Flutter app** for Sensit gas-detection instruments — a multi-protocol connectivity layer (BLE, Wi-Fi, LAN, serial), an **offline-first ObjectBox store** with bidirectional cloud sync and automatic reconciliation on reconnect, real-time charts, Gantt timeline views, multi-template report generation, firmware updates and calibration workflows. I shipped the foundational MVP.
- **.NET MAUI settings application** — configures ~50 instrument parameters through a guided UI, packaged as byte arrays written over BLE. Removed **over 99%** of manual configuration effort.
- **React Native app** — BLE data download, SQLite persistence and cloud sync across Android and iOS from one shared codebase, **40% less** development effort.

### 🏦 Earlier: test automation at Barclays

`Business Analyst (BA4) Intern` &nbsp; `Pune, 2023`

Built an automated testing framework with **Java** and **Selenium WebDriver** that raised coverage across critical workflows by **90%**, and wired it into **Jenkins** to run on every commit.

---

## 🧰 Tech I use

**Frontend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=angular,react,nextjs,ts,js,html,css&perline=7" alt="Frontend" />
</p>

HighCharts · React Native · Responsive and cross-browser work

**Backend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,py,java,cs,dotnet,prisma&perline=7" alt="Backend" />
</p>

REST APIs · Microservices · Message queues · BullMQ · ASP.NET

**Data and messaging**

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka,sqlite&perline=6" alt="Data and messaging" />
</p>

SQL Server · LiteDB · ObjectBox · Vector search

**AI and LLM**

<p align="left">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</p>

Agent harness · RAG · Vector search · Prompt engineering · Tool calling · BMAD / GSD

**Cloud and DevOps**

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,azure,aws,jenkins,git,github,netlify,postman&perline=9" alt="Cloud and DevOps" />
</p>

Azure DevOps · CI/CD · Flutter and .NET MAUI for client work

---

## 🗺️ How I got here

```mermaid
timeline
    2020 : AIR 8886 (99.22 percentile) in JEE Mains : Started B.Tech CSE at SVNIT Surat
    2023 : Business Analyst intern at Barclays, Pune : Java and Selenium test automation
    2024 : Graduated 5th of 135 with a 9.19 CGPA : Joined Halma plc as a Software Engineer
    2025 : Shipped cross-platform clients for Sensit instruments : Built the .NET MAUI settings tool
    2026 : Backend and dashboards on NestJS, Kafka and Angular : LLM agent harness and n8n automation for the team
```

---

## 🧠 What's on my mind

```mermaid
flowchart LR
    U((Dhairya))
    U --- A[AI engineering]
    U --- F[Full stack]
    U --- S[Systems]
    U --- O[Off the keyboard]
    A --- A1[Agent harnesses]
    A --- A2[RAG and<br/>vector search]
    A --- A3[n8n automation]
    A --- A4[BMAD and GSD]
    F --- F1[NestJS and<br/>REST design]
    F --- F2[Next.js and<br/>Angular]
    F --- F3[PostgreSQL<br/>schema design]
    S --- S1[Event-driven<br/>architecture]
    S --- S2[Kafka and queues]
    S --- S3[Kubernetes]
    O --- O1[Formula 1]
    O --- O2[Teaching juniors]
    O --- O3[Hackathons]

    classDef root fill:#0B1020,stroke:#0B1020,color:#fff
    classDef ai fill:#7C3AED,stroke:#7C3AED,color:#fff
    classDef full fill:#4F46E5,stroke:#4F46E5,color:#fff
    classDef sys fill:#0E7C6B,stroke:#0E7C6B,color:#fff
    classDef off fill:#C98A12,stroke:#C98A12,color:#fff
    class U root
    class A,A1,A2,A3,A4 ai
    class F,F1,F2,F3 full
    class S,S1,S2,S3 sys
    class O,O1,O2,O3 off
```

---

## 🌱 Right now

- 🤖 **Building agentic tooling into daily engineering.** n8n orchestration, a custom LLM agent harness, and frameworks like BMAD and GSD — the goal is an agent that reliably finishes a task, not one that demos well.
- 🔍 **Going deeper on RAG and retrieval.** Chunking strategies, vector search, and how much context is actually worth paying for.
- ⚙️ **Scaling the backend.** Event-driven architecture, concurrency and fault tolerance, for when sensor data arrives faster than one service can handle.
- 🧩 **Keeping fundamentals sharp** in [my DSA repo](https://github.com/Dhairya-007/DSA).

---

## 🏆 Achievements

| | |
| --- | --- |
| 🎯 **JEE Mains 2020** | All India Rank **8886** — 99.22 percentile among 1.1 million candidates |
| 🎯 **JEE Advanced 2020** | All India Rank **~10,000** — 95+ percentile among 1.6 lakh candidates |
| 🎓 **SVNIT Surat, 2024** | Ranked **5th of 135** in B.Tech Computer Science and Engineering, 9.19/10 CGPA |
| 🧑‍🏫 **ACM NIT Surat** | Executive — organized hackathons and ran technical sessions for juniors |
| 💻 **MLSA NIT Surat** | Junior Developer — built event websites and supported technical events |

---

## 🤝 Let's talk

Happy to talk about full-stack architecture, event-driven backends, or putting LLM agents somewhere they actually earn their keep.

📫 [ozadhairya73@gmail.com](mailto:ozadhairya73@gmail.com) · [LinkedIn](https://www.linkedin.com/in/dhairya-oza-7723b2200/) · [Portfolio](https://dhairyaoza007.netlify.app)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:4F46E5,100:0B1020&height=110&section=footer" alt="" />
</p>

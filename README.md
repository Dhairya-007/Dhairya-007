<!--
  Dhairya Oza · GitHub profile README
  Lives at github.com/Dhairya-007/Dhairya-007 — this file renders on the profile page.

  Positioning, in priority order:
    1. Upstream contributor — 142 changes merged into Apache Camel, Elasticsearch,
       Netty, Quarkus, Micronaut, Home Assistant, typeshed, the PEPs and Google's
       Dart repos. This is the rarest thing here, so it leads.
    2. Maintainer — lattice (Flutter data grid, on pub.dev) and datagrid-core.
    3. Primary developer on SyncIT at Halma.
    4. Everything else.

  Palette (keep these consistent if you edit):
    deep navy #0B1020
    indigo    #4F46E5
    violet    #7C3AED
    teal      #0E7C6B

  MAINTENANCE
    - PR counts are live-verifiable:
        merged:    gh api -X GET search/issues -f q='author:Dhairya-007 type:pr is:merged' --paginate
        in review: gh api -X GET search/issues -f q='author:Dhairya-007 type:pr is:open'   --paginate
      Exclude repos under Dhairya-007/ — only upstream counts. Update the "as of" date.
    - Pin these six: lattice, agent-harness, rag-service, datagrid-core,
      voiceagent, lights-out (profile -> Customize your pins).
    - Add the lattice web demo link here once GitHub Pages is live.
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:4F46E5,100:7C3AED&height=200&section=header&text=Hi%2C%20I%27m%20Dhairya&fontColor=ffffff&fontSize=46&fontAlignY=36&desc=Full-Stack%20Engineer%20%C2%B7%20Upstream%20Contributor%20%C2%B7%20AI%20Systems&descAlignY=56&descSize=18" alt="Hi, I'm Dhairya" />
</p>

<p align="center">
  <a href="https://github.com/search?q=author%3ADhairya-007+is%3Apr+is%3Amerged+-user%3ADhairya-007&type=pullrequests">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3400&pause=900&color=7C3AED&center=true&vCenter=true&width=760&lines=142+changes+merged+into+Apache+Camel%2C+Elasticsearch%2C+Netty;I+hunt+the+bugs+a+project%27s+CI+structurally+cannot+catch;Maintainer+of+lattice+%E2%80%94+a+free+data+grid+for+Flutter;Full-stack+engineer+at+Halma+plc+%C2%B7+Angular+%C2%B7+NestJS+%C2%B7+Kafka;Primary+dev+on+SyncIT+%E2%80%94+Flutter+for+gas-detection+hardware;I+build+LLM+agents+and+automation+into+the+stack" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dhairya-oza-7723b2200/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://dhairyaoza007.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0E7C6B?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" /></a>
  <a href="https://pub.dev/packages/lattice_core"><img src="https://img.shields.io/badge/pub.dev-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="pub.dev" /></a>
  <a href="mailto:ozadhairya73@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<table align="center">
  <tr>
    <td align="center" width="25%"><b>142</b><br/><sub>changes merged<br/>into upstream projects</sub></td>
    <td align="center" width="25%"><b>12</b><br/><sub>projects, incl. Apache<br/>Python, Netty, Google</sub></td>
    <td align="center" width="25%"><b>2</b><br/><sub>open-source libraries<br/>published and maintained</sub></td>
    <td align="center" width="25%"><b>3</b><br/><sub>platforms I ship<br/>a product on</sub></td>
  </tr>
</table>

> **The short version.** I'm a full-stack engineer at Halma plc, and in my own time I hunt one class of bug on purpose: the kind a project's CI **structurally cannot catch**. A default hidden behind `**kwargs` that `stubtest` has no parameter to compare against. A log line whose placeholders outnumber its arguments. A hand-written catalog entry that drifts from the enum it describes. A format string that throws the moment debug logging is switched on. Linters do not look there, so the defects sit in released code for years. **142 of those are now fixed in Apache Camel, Elasticsearch, Netty, Quarkus, Home Assistant and friends.**

---

## 🌍 Upstream contributions

<p align="left">
  <img src="https://img.shields.io/badge/merged_upstream-142-0E7C6B?style=for-the-badge&labelColor=0B1020" alt="142 merged upstream" />
  <img src="https://img.shields.io/badge/in_review-16-4F46E5?style=for-the-badge&labelColor=0B1020" alt="16 in review" />
  <img src="https://img.shields.io/badge/shipped_to-Apache_·_Python_·_Netty_·_Google_·_Elastic-7C3AED?style=for-the-badge&labelColor=0B1020" alt="Shipped to Apache, Python, Netty, Google and Elastic projects" />
</p>

Every typing change is verified the same way before it goes out: `stubtest` against the real installed package, then `mypy --strict` and `pyright` on a usage file full of `assert_type`, so the error count before and after is the evidence. I only count a change once maintainers merge it.

### 📦 By project

| Project | Merged | In review |
| --- | ---: | ---: |
| [Apache Camel](https://github.com/apache/camel/pulls?q=is%3Apr+author%3ADhairya-007) | 120 | — |
| [drift](https://github.com/simolus3/drift/pulls?q=is%3Apr+author%3ADhairya-007) | 5 | — |
| [typeshed](https://github.com/python/typeshed/pulls?q=is%3Apr+author%3ADhairya-007) | 4 | 4 |
| [the PEPs](https://github.com/python/peps/pulls?q=is%3Apr+author%3ADhairya-007) | 3 | — |
| [Netty](https://github.com/netty/netty/pulls?q=is%3Apr+author%3ADhairya-007) | 2 | — |
| [Micronaut](https://github.com/micronaut-projects/micronaut-core/pulls?q=is%3Apr+author%3ADhairya-007) | 2 | 2 |
| [Elasticsearch](https://github.com/elastic/elasticsearch/pulls?q=is%3Apr+author%3ADhairya-007) | 1 | 1 |
| [more-itertools](https://github.com/more-itertools/more-itertools/pulls?q=is%3Apr+author%3ADhairya-007) | 1 | 1 |
| [shelf](https://github.com/dart-lang/shelf/pulls?q=is%3Apr+author%3ADhairya-007) | 1 | 1 |
| [Quarkus](https://github.com/quarkusio/quarkus/pulls?q=is%3Apr+author%3ADhairya-007) | 1 | — |
| [Home Assistant](https://github.com/home-assistant/core/pulls?q=is%3Apr+author%3ADhairya-007) | 1 | — |
| [native](https://github.com/dart-lang/native/pulls?q=is%3Apr+author%3ADhairya-007) | 1 | — |
| [CPython](https://github.com/python/cpython/pulls?q=is%3Apr+author%3ADhairya-007) | — | 1 |
| [better-ajv-errors](https://github.com/atlassian/better-ajv-errors/pulls?q=is%3Apr+author%3ADhairya-007) | — | 2 |
| [eslint-plugin-vitest](https://github.com/vitest-dev/eslint-plugin-vitest/pulls?q=is%3Apr+author%3ADhairya-007) | — | 2 |
| [intl (dart-lang/i18n)](https://github.com/dart-lang/i18n/pulls?q=is%3Apr+author%3ADhairya-007) | — | 1 |
| [dart-lang/tools](https://github.com/dart-lang/tools/pulls?q=is%3Apr+author%3ADhairya-007) | — | 1 |
| **Total** | **142** | **16** |

Every PR is public and verifiable: [all merged](https://github.com/search?q=author%3ADhairya-007+is%3Apr+is%3Amerged+-user%3ADhairya-007&type=pullrequests) · [all in review](https://github.com/search?q=author%3ADhairya-007+is%3Apr+is%3Aopen+-user%3ADhairya-007&type=pullrequests). Counts as of **25 Nov 2026**.

---

## 📦 Open source I maintain

Libraries I build and keep, not demos. Both grid projects exist for the same reason: every capable data grid in their ecosystem is behind a licence key.

### 🧮 [lattice](https://github.com/Dhairya-007/lattice) · a data grid for Flutter that doesn't ask for a licence key

<p align="left">
  <a href="https://pub.dev/packages/lattice_core"><img alt="lattice_core on pub.dev" src="https://img.shields.io/pub/v/lattice_core.svg?label=lattice_core&color=0175C2&style=for-the-badge" /></a>
  <img alt="MIT" src="https://img.shields.io/badge/licence-MIT-0E7C6B?style=for-the-badge" />
  <img alt="Dart" src="https://img.shields.io/badge/Dart_3.8+-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter_3.47+-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
</p>

Flutter's data grid story is Syncfusion and friends — powerful, and gated behind a paid licence. **lattice** does the hard parts and asks for nothing: frozen columns, multi-column sorting, a filter row, grouping with subtotals, tree rows, virtual scrolling, range selection, inline editing and CSV export. No licence key, no paid tier, no evaluation banner.

**[pub.dev](https://pub.dev/packages/lattice_core)** · **[Code](https://github.com/Dhairya-007/lattice)** · MIT

### ⚙️ [datagrid-core](https://github.com/Dhairya-007/datagrid-core) · the same engine, headless, for TypeScript

Sorting, filtering, grouping with aggregates, tree rows, virtualization, selection, editing with undo and CSV export — as a pure state machine. No renderer, no framework, **no dependencies**. Bring your own React, Vue, Svelte or plain DOM.

### 🤖 The AI work, in public

The agent systems I build at work live in a private codebase, so here are the same ideas, runnable.

| Repo | What it is | Built with |
| --- | --- | --- |
| **[agent-harness](https://github.com/Dhairya-007/agent-harness)** | A typed agent harness for Claude. The loop is the easy part — this is the rest: tool inputs validated before they run, approval gates over parsed arguments, a context budget that clears old tool output, a verification pass that can send the model back, and distinct errors for refusal, truncated tool input and context overflow. **39 tests, no network.** | TypeScript · Zod · Anthropic SDK |
| **[rag-service](https://github.com/Dhairya-007/rag-service)** | Grounded document Q&A. Hybrid BM25 + dense retrieval fused by rank, a NestJS API and a Next.js UI. Retrieval is a *tool the model calls repeatedly*, not a prompt prefix, and an answer that cites nothing is rejected and sent back. **52 tests.** | NestJS · Next.js · TypeScript · agent-harness |
| **[voiceagent](https://github.com/Dhairya-007/voiceagent)** | Streaming voice agent for phone calls: STT → LLM → TTS with barge-in, Twilio telephony and per-turn latency tracing. **696 ms p50.** Runs free and offline. | Python · Twilio · streaming STT/TTS |

---

## 👋 About me

I'm a **full-stack engineer** at **Halma plc**, building the whole path: PostgreSQL schemas and NestJS services at the back, Kafka and Redis in the middle, Angular and Next.js dashboards at the front, and Docker/Kubernetes underneath it all.

Outside of work, I do two things. I **contribute upstream** — 142 changes merged into Apache Camel, Elasticsearch, Netty, Quarkus, Home Assistant and the Python and Dart ecosystems, all of one kind: the defect a project's own tooling cannot see. And I **maintain libraries** that fill a gap I hit myself — [lattice](https://github.com/Dhairya-007/lattice), a data grid for Flutter that doesn't need a licence key, and [datagrid-core](https://github.com/Dhairya-007/datagrid-core), the same engine headless for TypeScript.

The half of my day job I'm most interested in is **AI in the engineering loop**. I've built a custom **LLM agent harness** and **n8n** automation that my team uses daily, and I work with RAG, vector search and agentic frameworks like BMAD and GSD. Not models — systems: the orchestration, the tool layer, the retrieval, and the glue that makes an agent useful instead of impressive.

The other half is hardware-facing. I'm the primary developer on **SyncIT**, the application that manages Sensit's gas-detection instruments over BLE, Wi-Fi, LAN and serial, on Android, iOS and Windows from one Flutter codebase.

I also mentor juniors and colleagues on the codebase, and work with the project manager and engineering manager in **Wrike** on task breakdown, sizing and distribution.

<p align="left">
  <img src="https://img.shields.io/badge/Open_Source-0E7C6B?style=flat-square&logoColor=white" alt="Open Source" />
  <img src="https://img.shields.io/badge/Full--Stack-4F46E5?style=flat-square&logoColor=white" alt="Full-Stack" />
  <img src="https://img.shields.io/badge/AI_%26_Agents-7C3AED?style=flat-square&logoColor=white" alt="AI and Agents" />
  <img src="https://img.shields.io/badge/Distributed_Systems-0E7C6B?style=flat-square&logoColor=white" alt="Distributed Systems" />
  <img src="https://img.shields.io/badge/Cloud_%26_DevOps-C98A12?style=flat-square&logoColor=white" alt="Cloud and DevOps" />
  <img src="https://img.shields.io/badge/Cross--Platform-02569B?style=flat-square&logoColor=white" alt="Cross-platform" />
  <img src="https://img.shields.io/badge/Mentoring-0B1020?style=flat-square&logoColor=white" alt="Mentoring" />
</p>

---
## 📱 SyncIT · instrument management platform

### 🛰️ Cross-platform product for gas-detection instruments · `Flutter` `Dart` `Melos` `ObjectBox`

`Sensit Technologies · Halma India` &nbsp; `2025 – present` &nbsp; `Android · iOS · Windows`

<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/BLE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white" alt="BLE" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="iOS" />
  <img src="https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/manual_effort_removed-99%25-0E7C6B?style=for-the-badge&labelColor=0B1020" alt="99 percent of manual effort removed" />
  <img src="https://img.shields.io/badge/app_performance-30--35%25_faster-0E7C6B?style=for-the-badge&labelColor=0B1020" alt="30 to 35 percent faster" />
  <img src="https://img.shields.io/badge/settings_automated-50-4F46E5?style=for-the-badge&labelColor=0B1020" alt="50 settings automated" />
  <img src="https://img.shields.io/badge/older_apps_retired-5-7C3AED?style=for-the-badge&labelColor=0B1020" alt="5 older apps retired" />
</p>

<table>
  <tr>
    <td align="center"><b>−99%</b><br/><sub>manual production<br/>effort removed</sub></td>
    <td align="center"><b>30–35%</b><br/><sub>faster after schema<br/>and query work</sub></td>
    <td align="center"><b>50</b><br/><sub>instrument settings<br/>pushed automatically</sub></td>
    <td align="center"><b>4</b><br/><sub>transports: BLE, Wi-Fi<br/>LAN, serial</sub></td>
    <td align="center"><b>3</b><br/><sub>platforms from<br/>one codebase</sub></td>
    <td align="center"><b>5</b><br/><sub>older apps merged into<br/>SyncIT Lite and Plus</sub></td>
    <td align="center"><b>25–30</b><br/><sub>person team across<br/>3 countries</sub></td>
  </tr>
</table>

[Sensit](https://sensit-tech.com/gas-leak-detection-software/) has made gas-detection instruments for utilities, firefighters and hazmat teams for over 40 years. **SyncIT** is its next-generation instrument management platform. It retired **5 older Sensit apps**, with all their functions consolidated into SyncIT Lite and SyncIT Plus.

I'm the **primary developer** on it, working with a **25–30 person team** across software, firmware, hardware, QA, project management and marketing, split between **Ahmedabad**, **Valparaiso (Indiana)** and **Bolzano (Italy)**.

**What I did**

- Took SyncIT from a **proof of concept to a production-ready MVP**, and have kept evolving it since through new features, architectural improvements and client-driven changes.
- **Retired 5 older apps** and moved all their functions into SyncIT Lite and Plus.
- Structured it as a **Melos monorepo** with two product variants on a shared core package and a dedicated **log-parsing SDK**.
- Built the **device communication modules** — **BLE** for gas-detection instruments, and **Wi-Fi, LAN and serial** for calibration stations — covering log download, parsing, visualization, firmware update workflows and multi-format export.
- Suggested and built a **settings application for three instruments**, with an automated BLE update flow across **50 settings**. Working with the firmware team, this cut manual production effort by about **99%**.
- **Performance:** improved app performance by about **30–35%** by optimizing the database schema and queries.
- **Robustness:** built the **offline-first ObjectBox store** with bidirectional cloud sync and automatic reconciliation on reconnect, for reliable operation in low-connectivity field environments.
- Built the data-heavy screens on top of it: real-time charts, Gantt timeline views and multi-template report generation.
- Reworked the app's **UI, navigation flow and data visualization**, creating the wireframes with the engineering manager.
- Built **Windows-scheduled reporting** for LAN-connected devices, with customizable export configurations.
- **Own the full release pipeline**: build generation, versioning, packaging and distribution on every platform.

**Beyond the code**

I joined Halma as an intern in January 2024 and have been the primary developer on SyncIT since 2025.

- **Spotted a production bottleneck and removed it.** I proposed the settings application and built it with the firmware team. Manual production effort dropped by about **99%**.
- **Own releases on 3 platforms.** Builds, versioning, packaging and distribution for Android, iOS and Windows, with **Azure DevOps** in the toolchain.
- **Primary developer for a 25–30 person team.** That means working with **6 disciplines in 3 countries**: software, firmware, hardware, QA, project management and marketing.
- **Keep delivery organised in Wrike.** I create tasks, size them, distribute them across the team and track them through to release.
- **Mentor juniors and colleagues** on the codebase and help them get unblocked.
- **Brought agentic tooling into daily engineering.** I built a custom LLM agent harness and **n8n** automation for the team, and integrated **BMAD** and **GSD** into its workflow.

| Variant | What it is |
| --- | --- |
| **SyncIT Lite** | Offline-first, for field evaluation |
| **SyncIT Plus** | Cloud sync, advanced reporting and premium integrations |

**Stack:** Flutter · Dart · Melos · ObjectBox · BLE · Wi-Fi, LAN and serial · Azure DevOps CI/CD · Wrike · n8n · Claude Code

<p align="left">
  <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white" alt="Azure DevOps" />
  <img src="https://img.shields.io/badge/Wrike-08CF5D?style=flat-square&logo=wrike&logoColor=white" alt="Wrike" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Mentoring_%26_task_distribution-C98A12?style=flat-square&logoColor=white" alt="Mentoring and task distribution" />
</p>

```mermaid
flowchart LR
    INST[Gas-detection<br/>instruments]
    CAL[Calibration<br/>stations]
    BLE[BLE layer]
    NET[Wi-Fi · LAN · serial]
    SDK[Log-parsing SDK]
    CORE[Shared core package<br/>Melos monorepo]
    DB[(ObjectBox<br/>offline-first)]
    CLOUD[(Cloud sync)]
    LITE[SyncIT Lite<br/>Android · iOS · Windows]
    PLUS[SyncIT Plus<br/>reporting · integrations]
    OUT[Charts · reports · exports<br/>firmware updates · settings]

    INST --> BLE
    CAL --> NET
    BLE --> SDK
    NET --> SDK
    SDK --> CORE
    CORE <--> DB
    CORE --> LITE
    CORE --> PLUS
    PLUS <--> CLOUD
    LITE --> OUT
    PLUS --> OUT

    classDef hw fill:#0B1020,stroke:#0B1020,color:#fff
    classDef link fill:#4F46E5,stroke:#4F46E5,color:#fff
    classDef data fill:#0E7C6B,stroke:#0E7C6B,color:#fff
    classDef app fill:#7C3AED,stroke:#7C3AED,color:#fff
    classDef out fill:#C98A12,stroke:#C98A12,color:#fff
    class INST,CAL hw
    class BLE,NET,SDK link
    class CORE,DB,CLOUD data
    class LITE,PLUS app
    class OUT out
```

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


## 🧩 Things I've built for fun

| Project | What it is | Stack | Links |
| --- | --- | --- | --- |
| **lights-out** | Formula 1 races replayed in the browser in 3D, with real engine sound, team radio, and the race story found automatically from timing data. | Three.js · Web Audio · OpenF1 | [Live](https://dhairya-007.github.io/lights-out/) · [Code](https://github.com/Dhairya-007/lights-out) |
| **billber** | Split shared expenses in three taps. No account, no server, works offline. | TypeScript · PWA | [Code](https://github.com/Dhairya-007/billber) |
| **ochre-pass-rally** | A 3D rally game in Python: career mode, AI rivals, online multiplayer, four generated stages, physically based rendering. | Python · Panda3D | [Code](https://github.com/Dhairya-007/ochre-pass-rally) |
| **Detonate the Bomb** | A browser puzzle game: 50 hand-built levels, instruction-driven gameplay, timer, scoring and level progression, all client-side. | Next.js · TypeScript · CSS3 | [Live](https://detonatebomb.netlify.app/) · [Code](https://github.com/Dhairya-007/detonator) |
| **Portfolio** | A single-page portfolio built as a Formula 1 racing dashboard — 10+ custom animations, dynamic gauges, interactive navigation, responsive to phone width. | Next.js · TypeScript · CSS animations | [Live](https://dhairyaoza007.netlify.app/) · [Code](https://github.com/Dhairya-007/portfolio) |
| **Citrine Growth** | A digital agency platform — marketing site plus a full admin panel, with dual light/dark theming throughout. | Next.js 14 · NestJS · Prisma · PostgreSQL | [Code](https://github.com/Dhairya-007/citrine-growth) |
| **Siddheshwari Investment** | A business site for an investment firm: 10+ content sections, tuned for load performance and cross-browser support. | Angular · TypeScript · Netlify | [Live](https://siddheshwariinvestment.netlify.app/) |
| **Desi board games** | Ludo with cuts and safe stars, snakes and ladders with hand-drawn SVG snakes and a 3D dice, and an Ahmedabad property board game. | React · Vite · SVG | [ludo](https://github.com/Dhairya-007/ludo-katta) · [saap-sidi](https://github.com/Dhairya-007/saap-sidi) · [amdavad](https://github.com/Dhairya-007/amdavad-business) |

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

## 📱 Other instrument clients at Halma

Two more clients for the same instruments:

- **.NET MAUI settings application** — the app behind the 99% figure above. It configures ~50 instrument parameters through a guided UI, packaged as byte arrays and written to the instrument's Customer Profile region over BLE.
- **React Native app** — BLE data download, SQLite persistence and cloud sync across Android and iOS from one shared codebase, **40% less** development effort.

---

## 🏦 Before Halma: test automation at Barclays

`Business Analyst (BA4) Intern` &nbsp; `Pune, 2023`

Built an automated testing framework with **Java** and **Selenium WebDriver** that raised coverage across critical workflows by **90%**, and wired it into **Jenkins** to run on every commit.

---

## 🧰 Tech I use

**Frontend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=angular,react,nextjs,flutter,dart,ts,js,html,css&perline=9" alt="Frontend" />
</p>

HighCharts · Flutter · React Native · .NET MAUI · Responsive and cross-browser work

**Backend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,py,java,cs,dotnet,prisma&perline=7" alt="Backend" />
</p>

REST APIs · Microservices · Message queues · BullMQ · ASP.NET

**Data and messaging**

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka,sqlite&perline=6" alt="Data and messaging" />
</p>

SQL Server · LiteDB · ObjectBox · Vector search · Melos monorepos

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

Azure DevOps · CI/CD · Multi-platform release pipelines (Android, iOS, Windows) · Wrike · Task planning and distribution

---

## 🗺️ How I got here

```mermaid
timeline
    2020 : AIR 8886 (99.22 percentile) in JEE Mains : Started B.Tech CSE at SVNIT Surat
    2023 : Business Analyst intern at Barclays, Pune : Java and Selenium test automation
    2024 : Graduated 5th of 135 with a 9.19 CGPA : Joined Halma plc as a Software Engineer
    2025 : Primary developer on SyncIT for Sensit instruments : Proof of concept to production-ready MVP
    2026 : SyncIT Lite and Plus on a Melos monorepo : Backend and dashboards on NestJS, Kafka and Angular : LLM agent harness and n8n automation for the team
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
    S --- S4[Release pipelines<br/>and DevOps]
    O --- O1[Formula 1]
    O --- O2[Mentoring juniors<br/>and colleagues]
    O --- O3[Hackathons]

    classDef root fill:#0B1020,stroke:#0B1020,color:#fff
    classDef ai fill:#7C3AED,stroke:#7C3AED,color:#fff
    classDef full fill:#4F46E5,stroke:#4F46E5,color:#fff
    classDef sys fill:#0E7C6B,stroke:#0E7C6B,color:#fff
    classDef off fill:#C98A12,stroke:#C98A12,color:#fff
    class U root
    class A,A1,A2,A3,A4 ai
    class F,F1,F2,F3 full
    class S,S1,S2,S3,S4 sys
    class O,O1,O2,O3 off
```

---


## 🌱 Right now

- 🧮 **Growing [lattice](https://github.com/Dhairya-007/lattice) past 1.0.** A web demo, more grid features, and the long tail of things people actually need from a data grid once they start using it in anger.
- 🌍 **Contributing upstream, one CI blind spot at a time.** 142 changes merged into Apache Camel, Elasticsearch, Quarkus, Home Assistant, typeshed, the PEPs, Netty, Micronaut, more-itertools, drift and the Dart SDK repos — each one a defect the project's own linters and test suites could not reach — and 16 more in review.
- 🤖 **Building agentic tooling into daily engineering.** n8n orchestration, a custom LLM agent harness, and frameworks like BMAD and GSD — the goal is an agent that reliably finishes a task, not one that demos well.
- 🔍 **Going deeper on RAG and retrieval.** Chunking strategies, hybrid search and rank fusion, and how much context is actually worth paying for — most of it ends up in [rag-service](https://github.com/Dhairya-007/rag-service).
- 📡 **Growing SyncIT past its MVP.** Two product variants on one Melos monorepo, a shared core package, a log-parsing SDK, and the device communication layer underneath both.
- ⚙️ **Scaling the backend.** Event-driven architecture, concurrency and fault tolerance, for when sensor data arrives faster than one service can handle.

---

## 📊 GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Dhairya-007&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0B1020&icon_color=7C3AED&title_color=4F46E5" alt="GitHub stats" />
  <img src="https://streak-stats.demolab.com?user=Dhairya-007&theme=tokyonight&hide_border=true&background=0B1020&ring=7C3AED&fire=C98A12&currStreakLabel=4F46E5" alt="Contribution streak" />
</p>

---

## 🏆 Background

| | |
| --- | --- |
| 🎓 **SVNIT Surat, 2024** | B.Tech Computer Science — ranked **5th of 135**, 9.19/10 CGPA |
| 🧑‍🏫 **ACM NIT Surat** | Executive — organized hackathons and ran technical sessions for juniors |
| 💻 **MLSA NIT Surat** | Junior Developer — built event websites and supported technical events |

---
## 🤝 Let's talk

Happy to talk about full-stack architecture, event-driven backends, or putting LLM agents somewhere they actually earn their keep.

📫 [ozadhairya73@gmail.com](mailto:ozadhairya73@gmail.com) · [LinkedIn](https://www.linkedin.com/in/dhairya-oza-7723b2200/) · [Portfolio](https://dhairyaoza007.netlify.app)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:4F46E5,100:0B1020&height=110&section=footer" alt="" />
</p>

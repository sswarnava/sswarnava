<!-- Header wave (subtle, no text) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:2f81f7&height=110&section=header">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:dbeafe,100:2f81f7&height=110&section=header" width="100%" alt="" />
</picture>

<div align="center">

<sub><code>01 · INTRODUCTION</code></sub>

### PRODUCT-MINDED SOFTWARE ENGINEER

<a href="https://github.com/sswarnava">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=2500&pause=1200&color=2F81F7&center=true&vCenter=true&width=520&height=40&lines=I+wonder.;I+build.;I+find+out." alt="I wonder. I build. I find out." />
</a>

Most interesting things start with a question. Some lead to a solution, others to a rabbit hole I didn’t plan to enter. I’m interested in both.

`Bengaluru` · `Software` ·  `Full Stack` · `Systems & Products` ·

</div>

<br/>

---

<h2><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=1800&pause=100000&repeat=false&color=2F81F7&width=520&height=36&lines=02+%C2%B7+About" alt="02 About" /></h2>

### Curious by nature. Technical by practice.

I build software across the stack, from React and TypeScript interfaces to backend services, APIs, and data layers using Node.js, Go, PostgreSQL, and Prisma.

My work spans production applications, real-time systems, and AI-powered workflows. I’m particularly interested in system design, distributed systems, and the engineering decisions that make software reliable beyond the happy path.

I use AI-assisted development tools as part of my workflow, but the interesting part isn’t generating code. It’s understanding the system, making sound decisions, and shipping something that works.

<p align="center">
  <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react,ts,nodejs,go,postgres,prisma&theme=dark">
  <img src="https://skillicons.dev/icons?i=react,ts,nodejs,go,postgres,prisma&theme=light" alt="React, TypeScript, Node.js, Go, PostgreSQL, Prisma" />
</picture>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=1400&pause=1800&color=8B949E&center=true&vCenter=true&width=700&height=30&lines=NOTICE;NOTICE+%E2%86%92+QUESTION;NOTICE+%E2%86%92+QUESTION+%E2%86%92+EXPLORE;NOTICE+%E2%86%92+QUESTION+%E2%86%92+EXPLORE+%E2%86%92+BUILD;NOTICE+%E2%86%92+QUESTION+%E2%86%92+EXPLORE+%E2%86%92+BUILD+%E2%86%92+BREAK;NOTICE+%E2%86%92+QUESTION+%E2%86%92+EXPLORE+%E2%86%92+BUILD+%E2%86%92+BREAK+%E2%86%92+UNDERSTAND;NOTICE+%E2%86%92+QUESTION+%E2%86%92+EXPLORE+%E2%86%92+BUILD+%E2%86%92+BREAK+%E2%86%92+UNDERSTAND+%E2%86%92+REPEAT" alt="NOTICE → QUESTION → EXPLORE → BUILD → BREAK → UNDERSTAND → REPEAT" />
</p>

<br/>

---

<h2><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=1800&pause=100000&repeat=false&color=2F81F7&width=520&height=36&lines=03+%C2%B7+Professional+Engineering" alt="03 Professional Engineering" /></h2>

<p>
  <img src="https://img.shields.io/badge/Wattmotive_Energy-2F81F7?style=for-the-badge&logo=lightning&logoColor=white" alt="Wattmotive Energy" />
  <img src="https://img.shields.io/badge/Software_Development_Engineer_I-30363D?style=for-the-badge" alt="Software Development Engineer I" />
</p>

> Building production-facing interfaces and platform features for EV charging infrastructure.

- Developed Admin and Super Admin interfaces, including role based access control and operational workflows.
- Integrated REST APIs across platform features and contributed to payment-related user flows.
- Worked with real time charger telemetry and WebSocket powered monitoring dashboards.

<sub>Previously: Junior Development Engineer (Part-time) · Software Engineering Intern</sub>

<br/>

---

<h2><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=1800&pause=100000&repeat=false&color=2F81F7&width=520&height=36&lines=04+%C2%B7+Project" alt="04 Project" /></h2>

<details open>
<summary><b>01 · Learnly</b> — Learning Platform</summary>

<br/>

- **What it is:** A full-stack education platform integrating course discovery, secure payments, and an embedded AI assistant.
- **Why I built it:** I wanted to move beyond passive video-playing apps and engineer a complete, end-to-end learning journey rom initial checkout to active, AI-assisted study within a single ecosystem.
- **Engineering Challenges:**
  - **Refactoring Legacy Code:** The hardest and most rewarding part was returning to the codebase years later. I had to audit broken flows, migrate to modern standards (like Better Auth), and restore reliability without falling into the trap of unnecessary feature creep.
  - **Workflow Orchestration:** Securely tying together Razorpay webhooks, database state (Prisma), protected enrollment routes, and the OpenAI API so the user never has to leave the platform to ask a question.
- **Tech Stack:** Next.js, React, TypeScript, PostgreSQL, Prisma, Better Auth, Razorpay, OpenAI.
- **Outcome:** Connected course enrollment, payment verification, and AI-assisted learning into a unified platform, while strengthening the reliability of legacy workflows through targeted refactoring.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nextjs,react,ts,postgres,prisma&theme=dark">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,postgres,prisma&theme=light" alt="Learnly tech stack" />
</picture>

</details>

<details>
<summary><b>02 · EV Charging Emulator</b> — Real-Time System</summary>

<br/>

- **What it is:** A software-based emulator that models virtual EV chargers, manages session state transitions, and streams live telemetry to a synchronized dashboard.
- **Why I built it:** I wanted to understand the internal mechanics of EV infrastructure beyond just reading dashboard metrics. Building a virtual system allowed me to explore complex charger behaviors and telemetry edge cases without being bottlenecked by physical hardware.
- **Engineering Challenges:**
  - **State & Session Modeling:** Architecting a robust state machine to accurately represent the lifecycle and transitions of an active charging session.
  - **Real-Time Synchronization:** Generating continuous telemetry and pushing it via WebSockets while ensuring the client dashboard stays perfectly in sync without performance degradation.
  - **Network Unreliability & Timing:** Handling the hard parts of real-time systems—managing dropped WebSocket connections, delayed updates, and preventing UI race conditions when the underlying system state changes mid-render.
- **Tech Stack:** React, TypeScript, Node.js, WebSockets, SQLite
- **Outcome:** Built a software-based environment for experimenting with charger state transitions, live telemetry synchronization, and network failure scenarios without requiring physical charging hardware.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react,ts,nodejs,sqlite&theme=dark">
  <img src="https://skillicons.dev/icons?i=react,ts,nodejs,sqlite&theme=light" alt="EV Charging Emulator tech stack" />
</picture>

</details>

<details>
<summary><b>03 · Pheri</b> — Product Engineering</summary>

<br/>

- **What it is:** A cross-platform mobile mobility application that orchestrates the end-to-end local journey between passengers and drivers.
- **Why I built it:** I wanted to build software that interacts with the physical world. Pheri was an exercise in translating a complex, two-sided marketplace concept into a working mobile experience, dealing heavily with real-world constraints rather than just data on a screen.
- **Engineering Challenges:**
  - **Multi-Actor State Management:** Structuring the complex, intertwined state transitions between the passenger's request flow and the driver's acceptance/transit flow so the journey progresses coherently for both users.
  - **Location-Aware Constraints:** Handling the physical realities of mobile applications, including GPS location validation, ride verification, and managing interactions when users are on the move.
  - **Physical-World Edge Cases:** Designing the application architecture to gracefully handle situations where the intended journey breaks down—such as dropped connections, state mismatches, or sudden cancellations.
- **Tech Stack:** React Native, TypeScript, React, Node.js, PostgreSQL
- **Outcome:** Translated a two-sided mobility concept into a cross-platform application, exploring how passenger-driver coordination, location validation, and real-world journey edge cases shape product architecture.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react,ts,nodejs,postgres&theme=dark">
  <img src="https://skillicons.dev/icons?i=react,ts,nodejs,postgres&theme=light" alt="Pheri tech stack" />
</picture>

</details>

<details>
<summary><b>04 · LifeOS</b> — Personal Operating System</summary>

<br/>

- **What it is:** A full-stack personal management system that centralizes goals, daily tasks, habit tracking, and reflections into a single interconnected application.
- **Why I built it:** My workflows were fragmented across multiple disconnected tools for tasks, notes, and planning. I wanted to engineer a single source of truth that adapted to how I actually work, rather than forcing myself to conform to off-the-shelf software.
- **Engineering Challenges:**
  - **Unified Data Architecture:** Designing a database schema capable of handling highly diverse, interconnected entities—linking long-term goals to daily tasks and historical habit logs—without creating massive data bloat.
  - **Temporal State Modeling:** Translating shifting daily plans, completed activities, and historical records into meaningful, persistent application state that accurately visualizes progress over time.
  - **Dogfooding & Schema Evolution:** Using the application daily meant instantly feeling UX friction. This drove continuous iteration, requiring me to safely migrate the Prisma schema and update business logic on the fly as my needs evolved.
- **Tech Stack:** React, Node.js, Express, PostgreSQL, Prisma, JWT Authentication.
- **Outcome:** Evolved a personal productivity system through daily use, connecting goals, tasks, habits, and historical records while continuously refining its data model and planning workflows around real-world needs.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react,nodejs,express,postgres,prisma&theme=dark">
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,postgres,prisma&theme=light" alt="LifeOS tech stack" />
</picture>

</details>

<details>
<summary><b>05 · AI Profile Matching Engine</b> — Applied AI</summary>

<br/>

- **What it is:** An experimental retrieval augmented generation (RAG) system that leverages vector embeddings to intelligently parse, rank, and match candidate profiles based on deep context.
- **Why I built it:** I wanted to evaluate where AI genuinely improves a software workflow. Instead of blindly wrapping a model around a dataset, I used this to test how semantic retrieval can solve edge cases that traditional keyword-based filtering misses.
- **Engineering Challenges:**
  - **Semantic Retrieval Pipeline:** Designing the context selection using Gemini Embeddings and LanceDB to fetch highly relevant, isolated data chunks, ensuring the model only receives what it needs instead of bloating the context window.
  - **Hybrid Architecture:** Defining the strict boundary between deterministic logic and AI. I had to map out exactly which decisions required conventional application logic (hard filters) versus where non-deterministic LLM reasoning actually added value.
  - **Productionizing LLMs:** Managing the engineering realities of AI integration—enforcing structured outputs (JSON), optimizing token costs, minimizing API latency, and building robust fallback behaviors for failed model calls.
- **Tech Stack:** TypeScript, Gemini API, LanceDB, RAG, Embeddings.
- **Outcome:** Built a semantic matching pipeline using Gemini embeddings and LanceDB, exploring how vector retrieval and deterministic filtering can complement LLM reasoning to identify relevant candidate profiles.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,gcp&theme=dark">
  <img src="https://skillicons.dev/icons?i=ts,gcp&theme=light" alt="AI Profile Matching Engine tech stack" />
</picture>

</details>

<details>
<summary><b>06 · GraphQL Exploration</b> — API Engineering</summary>

<br/>

- **What it is:** A full-stack delivery and order management application designed to explore how GraphQL unifies client data fetching, business logic, and relational databases beneath a single API surface.
- **Why I built it:** I wanted to understand GraphQL in a realistic context rather than through isolated tutorials. The delivery domain with its complex relational ties between users, orders, and couriers provided the perfect testing ground for deep data fetching, mutations, and role based access control.
- **Engineering Challenges:**
  - **Resolver Architecture & Data Flow:** Architecting the server to efficiently map complex, nested client queries through resolvers to the underlying PostgreSQL database (via Prisma), ensuring data is fetched cleanly without hitting performance bottlenecks.
  - **Relational Mutations:** Managing state changing operations where a single GraphQL mutation needs to safely update multiple interconnected database tables to reflect changing order statuses.
  - **Graph-Level Authorization:** Implementing strict Role-Based Access Control (RBAC). I engineered the backend to enforce authentication and permission checks directly at the resolver level, ensuring different user roles (customers vs. delivery drivers) only access appropriate data.
- **Tech Stack:** GraphQL, Node.js, TypeScript, PostgreSQL, Prisma, React.
- **Outcome:** Applied GraphQL to a relational delivery workflow, implementing nested data access, multi-entity mutations, and resolver-level authorization to understand how API design shapes data access and security.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=graphql,nodejs,ts,postgres,prisma,react&theme=dark">
  <img src="https://skillicons.dev/icons?i=graphql,nodejs,ts,postgres,prisma,react&theme=light" alt="GraphQL Exploration tech stack" />
</picture>

</details>

<br/>

---

<h2><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=1800&pause=100000&repeat=false&color=2F81F7&width=520&height=36&lines=Elsewhere" alt="Elsewhere" /></h2>

<p align="center">
  <a href="https://swarnavadev.in"><img src="https://img.shields.io/badge/%F0%9F%8C%90-swarnavadev.in-2F81F7?style=for-the-badge" alt="https://swarnavadev.in" /></a>
  <a href="https://linkedin.com/in/swarnavadev"><img src="https://img.shields.io/badge/LinkedIn-swarnavadev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="https://linkedin.com/in/swarnavadev" /></a>
  <a href="https://github.com/sswarnava"><img src="https://img.shields.io/badge/GitHub-sswarnava-181717?style=for-the-badge&logo=github&logoColor=white" alt="https://github.com/sswarnava" /></a>
  <a href="mailto:swarnavadev.tech@gmail.com"><img src="https://img.shields.io/badge/Email-swarnavadev.tech@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="swarnavadev.tech@gmail.com" /></a>
</p>

<!-- Footer wave -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:2f81f7,100:0d1117&height=90&section=footer">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f81f7,100:dbeafe&height=90&section=footer" width="100%" alt="" />
</picture>

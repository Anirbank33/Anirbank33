<div align="center">

# Anirban Kar
### Software Engineer — Full-Stack & Frontend (JavaScript & TypeScript)

📍 Bengaluru, India &nbsp;•&nbsp; **Open to Remote Engineering Opportunities (India & Worldwide)**

<p align="center">
  <a href="https://anirbank33.github.io/portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Portfolio-Sketchy%20Dark%20React%2018-0284C7?style=for-the-badge&logo=react&logoColor=white" alt="Live Portfolio" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/anirban-kar-23645414a/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:anirbankar23@gmail.com">
    <img src="https://img.shields.io/badge/Email-Get%20in%20Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://github.com/Anirbank33?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositories-10B981?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
  </a>
</p>

</div>

---

### 👨‍💻 Executive Summary

Software Engineer specializing in **JavaScript (ES6+)**, **TypeScript**, **React**, and **Node.js**. Focused on developing reliable full-stack web applications, contract-first RESTful APIs, and responsive interactive interfaces. Experienced in end-to-end type safety (OpenAPI / Zod), clean layered backend architecture, real-time WebSockets, and automated integration testing.

Actively seeking **Remote Software Engineer / Full-Stack / Frontend** opportunities across India and globally.

---

### 🛠️ Technical Skills (Grounded in Uploaded Projects)

| Domain | Verified Technologies & Tooling |
| :--- | :--- |
| **Languages** | **TypeScript**, **JavaScript (ES6+)**, HTML5, Modern CSS |
| **Frontend Engineering** | **React 18**, Vite, Tailwind CSS, TanStack Query, Responsive UI, DOM APIs |
| **Backend & APIs** | **Node.js**, **Express.js**, RESTful APIs, WebSockets, OpenAPI 3.0, Zod (Runtime Schema Validation) |
| **Architecture & Patterns** | Clean Layered Architecture (`routes → controllers → services → store`), Middleware Pipelines, Error Handling |
| **Testing & Quality** | Integration Testing (`supertest`), Node.js Test Runner (`node:test`), Defensive Coding |
| **DevOps & Workflow** | Git, GitHub Actions, GitHub Pages, pnpm / npm Workspaces, Postman, macOS / Linux Shell |

---

### 🚀 Featured Engineering Projects

#### 1. [Minimalist Sketchy Dark Portfolio (React 18)](https://github.com/Anirbank33/portfolio)
> **Tech Stack**: `React 18` · `JavaScript (ES6+)` · `HTML5` · `CSS3 Dark Mode` · `GitHub Pages`

* **The Problem**: Standard developer portfolios are bloated, visually overwhelming, and fail to demonstrate clean React component design, disciplined code structure, or responsive dark UX to busy recruiters.
* **The Solution**: Engineered a zero-bundler React 18 portfolio using pure CSS hand-drawn sketch borders (`border-radius: 255px 15px...`), an animated 3D avatar, state-driven project/skill filters, and WCAG AAA contrast on pure black (`#050505`).
* **Real-World Impact**: Demonstrates modular design system tokens, critical rendering path optimization, and accessible cross-browser UI execution applicable to high-scale enterprise SaaS products.
* **Links**: [Live Website ↗](https://anirbank33.github.io/portfolio/) · [GitHub Repository ↗](https://github.com/Anirbank33/portfolio)

---

#### 2. [JARVIS — AI Voice & Desktop Operating Assistant](https://github.com/Anirbank33/jarvis-ai-assistant)
> **Tech Stack**: `TypeScript` · `React 18` · `Node.js` · `Express` · `WebSockets` · `Gemini AI` · `Tailwind CSS`

* **The Problem**: Desktop multitasking requires repetitive window switching, mouse clicks, and manual status lookups. Connecting AI voice agents directly to native OS actions also introduces critical security risks of accidental or unverified command execution.
* **The Solution**: Built a hands-free desktop voice assistant combining browser Web Speech recognition with Google Gemini AI for contextual reasoning. Architected a WebSocket streaming server broadcasting live system telemetry (CPU, RAM, battery, network) and implemented an explicit **Security Confirmation Gateway** intercepting potentially destructive shell or file operations before execution.
* **Real-World Value**: Delivers hands-free desktop control and live hardware monitoring while enforcing strict permission safeguards against unauthorized system modifications.
* **Links**: [GitHub Repository ↗](https://github.com/Anirbank33/jarvis-ai-assistant)

---

#### 3. [Wardline — Clinical Department & Patient Census Management System](https://github.com/Anirbank33/medical-department-tracker)
> **Tech Stack**: `TypeScript` · `React 18` · `Vite` · `Express` · `Zod` · `OpenAPI 3.0` · `TanStack Query` · `pnpm`

* **The Problem**: Clinical charge nurses and unit managers face heavy cognitive overhead during shift handovers due to slow, cluttered legacy hospital software, creating delays in bed turnover, pending admissions, and priority task triage.
* **The Solution**: Developed a calm, high-density hospital operations command center organized as a TypeScript pnpm monorepo. Established a contract-first architecture using an authoritative OpenAPI 3.0 specification (`lib/api-spec/openapi.yaml`) with automated code generation for type-safe React Query hooks and runtime Zod validation schemas, ensuring complete frontend-to-backend data integrity.
* **Real-World Impact**: Gives hospital floor coordinators instant visibility into live bed occupancy ratios, searchable patient censuses, and chronological shift activity logs.
* **Links**: [GitHub Repository ↗](https://github.com/Anirbank33/medical-department-tracker)

---

#### 4. [Production Document REST API & Microservice Engine](https://github.com/Anirbank33/backend-demo)
> **Tech Stack**: `Node.js` · `Express.js` · `JavaScript` · `Supertest` · `Helmet` · `Clean Architecture`

* **The Problem**: Backend microservices frequently encounter unhandled edge cases in REST semantics (`PUT` vs `PATCH`), unvalidated request payloads, race conditions in file storage during concurrent writes, and vulnerability to client request flooding.
* **The Solution**: Architected a production-grade RESTful microservice implementing clean layered architecture (`routes → controllers → services → store → middleware`). Implemented atomic serialized file locks to eliminate lost updates, an in-memory per-IP sliding window rate limiter, Helmet security headers, and an automated 16-test suite using Node's native `node:test` runner and Supertest.
* **Real-World Impact**: Provides a predictable, secure, and stress-tested backend with explicit REST status handling (`201` + `Location`, `204`, `400`, `405` + `Allow`, `409`, `415`, `429` + `Retry-After`) and 100% automated test coverage.
* **Links**: [GitHub Repository ↗](https://github.com/Anirbank33/backend-demo)

---

#### 5. [GitHub Activity Telemetry Dashboard](https://github.com/Anirbank33/github-activity-2021-2026)
> **Tech Stack**: `JavaScript` · `HTML5 Canvas` · `CSS Custom Properties` · `GitHub GraphQL API`

* **The Problem**: Default GitHub contribution graphs are limited to a single year and lack comparative analytics across multi-year engineering journeys.
* **The Solution**: Built a zero-dependency telemetry dashboard querying the GitHub GraphQL API to visualize 5-year contribution velocity, month-by-month activity distributions, and responsive heatmaps with dark/light mode compatibility.
* **Real-World Impact**: Provides technical recruiters and engineering leads with a transparent, comprehensive audit of long-term coding consistency and project velocity.
* **Links**: [Live Dashboard ↗](https://anirbank33.github.io/github-activity-2021-2026/) · [GitHub Repository ↗](https://github.com/Anirbank33/github-activity-2021-2026)

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ghstats.vercel.app/api?username=Anirbank33&show_icons=true&theme=transparent&hide_border=true&title_color=00F0FF&icon_color=00F0FF&text_color=C9D1D9&rank_icon=github" />
    <source media="(prefers-color-scheme: light)" srcset="https://ghstats.vercel.app/api?username=Anirbank33&show_icons=true&theme=transparent&hide_border=true&title_color=0284C7&icon_color=0284C7&text_color=334155&rank_icon=github" />
    <img height="150" src="https://ghstats.vercel.app/api?username=Anirbank33&show_icons=true&theme=transparent&hide_border=true&title_color=00F0FF&icon_color=00F0FF&text_color=C9D1D9&rank_icon=github" alt="GitHub Stats" />
  </picture>
  &nbsp;&nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ghstats.vercel.app/api/top-langs/?username=Anirbank33&layout=compact&theme=transparent&hide_border=true&title_color=00F0FF&text_color=C9D1D9&langs_count=5" />
    <source media="(prefers-color-scheme: light)" srcset="https://ghstats.vercel.app/api/top-langs/?username=Anirbank33&layout=compact&theme=transparent&hide_border=true&title_color=0284C7&text_color=334155&langs_count=5" />
    <img height="150" src="https://ghstats.vercel.app/api/top-langs/?username=Anirbank33&layout=compact&theme=transparent&hide_border=true&title_color=00F0FF&text_color=C9D1D9&langs_count=5" alt="Top Languages" />
  </picture>
</div>

---

### 📬 Connect & Collaborate

Actively interviewing for **Remote Full-Stack, Frontend, and Backend Software Engineering roles** (India & Global).

* **Email**: [anirbankar23@gmail.com](mailto:anirbankar23@gmail.com)
* **LinkedIn**: [linkedin.com/in/anirban-kar-23645414a](https://www.linkedin.com/in/anirban-kar-23645414a/)
* **Portfolio**: [anirbank33.github.io/portfolio](https://anirbank33.github.io/portfolio/)
* **X / Twitter**: [@3anir33](https://x.com/3anir33)

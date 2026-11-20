<div align="center">

<!-- Animated Header Wave Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0F766E,0D9488,14B8A6,06B6D4,3B82F6&height=220&section=header&text=Gamal%20Ahmed&fontSize=48&fontAlignY=36&fontColor=ffffff&desc=Lead%20Full-Stack%20Software%20Engineer%20%7C%20System%20Architect&descAlignY=58&descAlign=50&descSize=18&animation=twinkling" width="100%" alt="Gamal Ahmed Header" />

<!-- Animated Typing SVG -->
<p align="center">
  <a href="https://github.com/ga5e8je99">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=1100&color=14B8A6&center=true&vCenter=true&multiline=false&width=650&height=48&lines=%F0%9F%9A%80+Lead+Full-Stack+Architect+%26+Engineer;%E2%9A%A1+Next.js+15%2C+React+19+%26+TypeScript+Specialist;%F0%9F%8F%A2+Architecting+ACID-Safe+Enterprise+ERP+Platforms;%F0%9F%9B%A1%EF%B8%8F+Concurrency-Safe+PostgreSQL+%26+Prisma+Transactions;%F0%9F%8C%8D+Building+High-Performance+3D+%26+AI+Web+Applications" alt="Typing SVG Animation" />
  </a>
</p>

<!-- Social & Portfolio Badges -->
<p align="center">
  <a href="https://gamal-iota.vercel.app"><img src="https://img.shields.io/badge/Portfolio-gamalahmed.dev-0F766E?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/gamal-ahmed--"><img src="https://img.shields.io/badge/LinkedIn-gamal--ahmed-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:gamal.ahmed.dev@gmail.com"><img src="https://img.shields.io/badge/Email-gamal.ahmed.dev@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/ga5e8je99"><img src="https://img.shields.io/badge/GitHub-ga5e8je99-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<br/>

```typescript
const gamalAhmed: SoftwareEngineer = {
  name: "Gamal Ahmed",
  role: "Lead Full-Stack Engineer & System Architect",
  location: "Cairo, Egypt",
  education: "B.Sc. in Computer Science & Informatics (2025)",
  focus: ["Enterprise ERP Systems", "ACID Transactions", "Concurrency Control", "3D WebGL & AI"],
  stack: ["Next.js 15", "React 19", "TypeScript", "Prisma ORM", "PostgreSQL", "Node.js", "Tailwind CSS"],
  status: "Open to High-Impact Full-Time Engineering Roles & Enterprise Contracts"
};
```

</div>

---

## 🛠️ Animated Tech Stack & Tools

<div align="center">

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,postgres,prisma,nodejs,express,mongodb,docker,git,vite,redux,threejs&theme=dark" alt="Animated Tech Stack Icons" />
  </a>
</p>

</div>

---

## 🏛️ System Architecture & Engineering Blueprint

As a full-stack engineer, I design applications around **data consistency, transactional integrity (ACID), zero race conditions**, and smooth, responsive UI/UX across RTL and LTR locales:

```mermaid
flowchart TD
  subgraph Client ["Client & Presentation Layer (RTL / LTR)"]
    direction TB
    UI["Next.js 15 App Router & React 19"]
    STYLING["Tailwind CSS v4 + shadcn/ui"]
    I18N["next-intl (Bilingual ar-EG / en-US)"]
    VIZ["Interactive Recharts & 3D WebGL"]
  end

  subgraph Gateway ["Edge & Security Middleware"]
    direction TB
    EDGE["Edge Routing & CSP Nonce Guard"]
    AUTH["Auth.js v5 (Edge Session Validation)"]
    RATELIMIT["Postgres-Backed Persistent Rate Limiting"]
    RBAC["Granular Role-Based Access Control (RBAC)"]
  end

  subgraph Domain ["Domain & Transaction Engine"]
    direction TB
    TX["ACID $transaction Coordination"]
    LOCK["Row-Level Locks (SELECT FOR UPDATE)"]
    ACCOUNTING["Automated Double-Entry General Ledger"]
    MONEY["Fixed Precision Money Engine (Decimal 15,2)"]
  end

  subgraph Data ["Data & Storage Layer"]
    direction TB
    PRISMA["Prisma ORM (Schema & Migrations)"]
    POSTGRES[("PostgreSQL 16 Engine")]
    MONGO[("MongoDB Collections")]
    BLOB["Vercel Blob Storage"]
  end

  Client --> Gateway
  Gateway --> Domain
  Domain --> Data
```

---

## 🚀 Flagship Projects

<table>
  <thead>
    <tr>
      <th width="30%">Project</th>
      <th width="45%">Architecture & Technical Highlights</th>
      <th width="25%">Links & Live Demos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <b>🏢 Masar ERP (مسار)</b><br/>
        <sub>Enterprise Resource Planning & Financial System</sub>
      </td>
      <td>
        • <b>Next.js 15 App Router + React 19 + TypeScript + Prisma ORM + PostgreSQL</b><br/>
        • Full double-entry financial accounting with automated general ledger posting.<br/>
        • Multi-warehouse inventory with <code>SELECT FOR UPDATE</code> row-level concurrency locks.<br/>
        • Edge-compatible Auth.js v5, DB-backed rate limiting, and bilingual RTL/LTR dashboards.
      </td>
      <td>
        <a href="https://erp-system-one-alpha.vercel.app"><b>🌐 Live Application</b></a><br/>
        <a href="https://github.com/ga5e8je99/erp-system"><b>💻 Source Code</b></a>
      </td>
    </tr>
    <tr>
      <td>
        <b>🌍 Sky – 3D Weather Globe</b><br/>
        <sub>Interactive Atmospheric Telemetry Platform</sub>
      </td>
      <td>
        • <b>React + Three.js + WebGL + Tailwind CSS + OpenWeather API</b><br/>
        • Real-time 3D interactive globe with day/night terminator lighting at 60 FPS.<br/>
        • Geographic latitude/longitude to 3D sphere coordinate vector projection.<br/>
        • Granular 7-day predictive forecasts, UV tracking, wind velocity & humidity metrics.
      </td>
      <td>
        <a href="https://sky-five-sage.vercel.app"><b>🌐 Live Application</b></a><br/>
        <a href="https://github.com/ga5e8je99/sky"><b>💻 Source Code</b></a>
      </td>
    </tr>
    <tr>
      <td>
        <b>🤖 JobMatch AI</b><br/>
        <sub>Smart ATS Resume Analyzer & Builder</sub>
      </td>
      <td>
        • <b>Next.js 15 + TypeScript + Tailwind CSS + Framer Motion</b><br/>
        • Real-time ATS parser evaluating keyword density, formatting, and structural compliance.<br/>
        • Missing keyword extraction matrix mapped against target job descriptions.<br/>
        • Clean single-column ISO A4 machine-readable PDF resume export.
      </td>
      <td>
        <a href="https://ai-resume-lilac-seven.vercel.app"><b>🌐 Live Application</b></a><br/>
        <a href="https://github.com/ga5e8je99/AI-Resume"><b>💻 Source Code</b></a>
      </td>
    </tr>
    <tr>
      <td>
        <b>🍕 PizzaHouse Delivery</b><br/>
        <sub>E-Commerce Food Ordering Platform</sub>
      </td>
      <td>
        • <b>React + Redux Toolkit + Node.js + Express + MongoDB</b><br/>
        • Interactive stone-baked pizza customizer with dynamic multi-topping calculations.<br/>
        • Persistent Redux Toolkit cart state with promo-code validation and delivery math.<br/>
        • Responsive mobile-first interface with sub-second cart updates.
      </td>
      <td>
        <a href="https://pizza-delivery-app.vercel.app"><b>🌐 Live Application</b></a><br/>
        <a href="https://github.com/ga5e8je99/pizza-lab"><b>💻 Source Code</b></a>
      </td>
    </tr>
    <tr>
      <td>
        <b>📚 BookStore</b><br/>
        <sub>Curated Digital Reading & Book E-Commerce</sub>
      </td>
      <td>
        • <b>Next.js + Node.js + Express + MongoDB (MVC Architecture)</b><br/>
        • High-speed multi-criteria catalog search across 15,000+ curated literature titles.<br/>
        • Secure JWT authentication, quick preview modal spotlight, and encrypted checkout.
      </td>
      <td>
        <a href="https://dashboard-mu-ochre-23.vercel.app"><b>🌐 Live Application</b></a><br/>
        <a href="https://github.com/ga5e8je99/book-store"><b>💻 Source Code</b></a>
      </td>
    </tr>
    <tr>
      <td>
        <b>💬 NeoChat</b><br/>
        <sub>Multimodal AI Assistant & Visual Studio</sub>
      </td>
      <td>
        • <b>React 19 + Material-UI (MUI v7) + Google Gemini 2.5 + FLUX AI</b><br/>
        • Multimodal visual image reasoning via drag-and-drop & clipboard paste.<br/>
        • High-resolution AI artwork synthesis with FLUX and live Web Speech voice dictation.
      </td>
      <td>
        <a href="https://neo-pi-six.vercel.app"><b>🌐 Live Application</b></a><br/>
        <a href="https://github.com/ga5e8je99/neo"><b>💻 Source Code</b></a>
      </td>
    </tr>
  </tbody>
</table>

---

## 🐍 Contribution Graph & Activity

<div align="center">

<!-- Animated Contribution Snake -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ga5e8je99/ga5e8je99/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ga5e8je99/ga5e8je99/output/github-contribution-grid-snake.svg">
  <img alt="GitHub Contribution Snake Animation" src="https://raw.githubusercontent.com/ga5e8je99/ga5e8je99/output/github-contribution-grid-snake-dark.svg" width="100%">
</picture>

<br/>

<!-- Animated Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ga5e8je99&theme=tokyo-night&bg_color=070b14&color=14b8a6&line=06b6d4&point=ffffff&area=true&hide_border=true" width="100%" alt="Contribution Activity Wave" />

<br/>

<!-- GitHub Analytics Cards with Fire Animation -->
<img src="https://github-readme-stats.vercel.app/api?username=ga5e8je99&show_icons=true&theme=tokyonight&hide_border=true&bg_color=070b14&title_color=14b8a6&icon_color=06b6d4&text_color=94a3b8" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ga5e8je99&layout=compact&theme=tokyonight&hide_border=true&bg_color=070b14&title_color=14b8a6&text_color=94a3b8" height="165" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ga5e8je99&theme=tokyonight&hide_border=true&background=070b14&ring=14b8a6&fire=06b6d4&currStreakLabel=14b8a6" alt="Streak Stats with Fire Animation" />

</div>

---

<!-- Animated Footer Wave Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0F766E,0D9488,14B8A6,06B6D4&height=120&section=footer" width="100%" alt="Footer Wave" />

<div align="center">
  <b>Let's build something exceptional together!</b><br/>
  💼 Available for Full-Time & Contract Roles • ✉️ <a href="mailto:gamal.ahmed.dev@gmail.com">gamal.ahmed.dev@gmail.com</a> • 🌐 <a href="https://gamal-iota.vercel.app">gamalahmed.dev</a>
</div>

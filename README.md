<div align="center">

# 👨‍💻 Gamal Ahmed
### **Full-Stack Software Engineer & System Architect**
Building high-performance, scalable, and concurrency-safe web applications.

[![Portfolio](https://img.shields.io/badge/Portfolio-gamalahmed.dev-0F766E?style=for-the-badge&logo=vercel&logoColor=white)](https://gamal-iota.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gamal--ahmed-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gamal-ahmed--)
[![Email](https://img.shields.io/badge/Email-gamal.ahmed.dev@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gamal.ahmed.dev@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ga5e8je99-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ga5e8je99)

<br/>

```typescript
const gamalAhmed: SoftwareEngineer = {
  name: "Gamal Ahmed",
  role: "Lead Full-Stack Engineer & System Architect",
  location: "Cairo, Egypt",
  education: "B.Sc. in Computer Science & Informatics (2025)",
  focus: ["Enterprise ERP Systems", "Transactional Concurrency", "Distributed Systems", "AI Integrations"],
  stack: ["Next.js 15", "React 19", "TypeScript", "Prisma ORM", "PostgreSQL", "Node.js", "Tailwind CSS"],
  status: "Open to Full-Time Engineering & High-Impact Contracts"
};
```

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

## 🛠️ Technical Arsenal

<div align="center">

### Frontend & Core
![Next.js](https://img.shields.io/badge/Next.js%2015-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React 19](https://img.shields.io/badge/React%2019-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript (ES6+)](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)

### Backend & Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%2016-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma ORM](https://img.shields.io/badge/Prisma%20ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Auth.js v5](https://img.shields.io/badge/Auth.js%20v5-black?style=for-the-badge&logo=auth0&logoColor=white)

### Testing, DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ga5e8je99&show_icons=true&theme=tokyonight&hide_border=true&bg_color=070b14&title_color=14b8a6&icon_color=06b6d4&text_color=94a3b8" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ga5e8je99&layout=compact&theme=tokyonight&hide_border=true&bg_color=070b14&title_color=14b8a6&text_color=94a3b8" height="165" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ga5e8je99&theme=tokyonight&hide_border=true&background=070b14&ring=14b8a6&fire=06b6d4&currStreakLabel=14b8a6" alt="Streak Stats" />

</div>

---

<div align="center">
  <b>Let's build something exceptional together!</b><br/>
  💼 Available for Full-Time & Contract Roles • ✉️ <a href="mailto:gamal.ahmed.dev@gmail.com">gamal.ahmed.dev@gmail.com</a> • 🌐 <a href="https://gamal-iota.vercel.app">gamalahmed.dev</a>
</div>

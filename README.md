<div align="center">

  <!-- Hero gradient header -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:3b82f6&height=200&section=header&text=Ayush%20Kumar&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36" width="100%" />

  <!-- Role tag -->
  <br/>
  <sub>🔭 Full‑stack engineer · AI‑integrated products · Shipping to production</sub>
  <br/>

  <!-- Contact pills -->
  <div>
    <a href="https://www.linkedin.com/in/ayush-kumar-562666346/">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="mailto:ayushpanther@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    <a href="https://x.com/AyushkumarXD">
      <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/>
    </a>
    <a href="https://github.com/99Ayush">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
    </a>
  </div>

</div>

<br/>

## 👨‍💻 About Me

I build full‑stack products that go from an empty repository to a deployed URL real people can use. I’m obsessed with the parts most people skip: deterministic code behind every number, PII masking before it leaves the machine, and “I couldn’t find evidence” being a valid verdict instead of a guessed true/false.

I ship four projects live right now, and I’m always looking for problems where the front‑end, API and model have to work together.

<br/>

## 🚀 Selected Work

| Project | What it does | Stack | Live |
|---|---|---|---|
| **Fin‑Buddy** | Reads offer letters & payslips, extracts numbers, flags risky clauses, compares offers on **in‑hand pay**. LLM extracts; deterministic code calculates. | React · Node · Express · MongoDB · Tesseract OCR | [GitHub](https://github.com/99Ayush/fin-buddy) |
| **Nivora** *(team lead)* | Student housing platform: verified PG/hostel listings with interactive maps, peer reviews, role‑based auth. I wrote 203 of 207 commits. | React · Express · Firebase · Leaflet · Radix UI | [GitHub](https://github.com/99Ayush/NIVORA) · [Demo](https://nivora-pi.vercel.app) |
| **Verity** | Evidence‑first fact‑checking: retrieves independent web sources, returns a verdict with **verbatim quoted citations**, and abstains deterministically instead of guessing. | React · Express · TypeScript · Gemini · Tavily | [GitHub](https://github.com/99Ayush/verity) · [Demo](https://verity-nine-lyart.vercel.app) |
| **InAmigos ERP** | NGO operations system: volunteer triage, CSR funding pipeline, initiative tracking, full audit trail. | React · Express · Supabase · PostgreSQL | [GitHub](https://github.com/99Ayush/inamigos-erp) · [Demo](https://in-amigos-foundation-ai-application-ecru.vercel.app) |
| **Grand Prix** | F1 pit‑wall telemetry: calibrated tyre‑compound scoring, aquaplaning risk modelling and pit‑crossover strategy windows, every recommendation shipped with its inputs. | React · Node · MongoDB · Chart.js | [GitHub](https://github.com/99Ayush/grandprix) |
| **Banking API Simulator** | Money movement treated seriously: atomic transfers inside MongoDB transactions, idempotent retries, immutable double‑entry ledger and reconciliation. Backend only – Swagger & Postman, no UI. | Node · Express · MongoDB · Redis · JWT | [GitHub](https://github.com/99Ayush/banking-app-simulator) |
| **Pokepedia** | Pokedex in vanilla JavaScript — no framework, no build step, hand‑rolled caching and DOM rendering. | JavaScript · CSS3 · PokeAPI | [GitHub](https://github.com/99Ayush/pokepedia) · [Demo](https://pokepedia-tan.vercel.app) |

<br/>

## 🛠️ How I Build

| Principle | What it means |
|---|---|
| **Deterministic over clever** | In Fin‑Buddy the language model is only allowed to read and explain a document — never to do the arithmetic. Salary math is plain JavaScript with a visible formula behind every number, because a model that quietly gets tax wrong is worse than no model at all. |
| **Privacy is an ordering problem** | In Fin‑Buddy, personal data gets redacted before it leaves the machine, not after. Raw documents never reach a third‑party API — the masking runs first because that is the only ordering that means anything. |
| **Abstention is an answer** | In Verity, “I could not find evidence” is a first‑class verdict. A system that guesses when it doesn’t know is more dangerous than one that says so, and the same logic applies to any model I put in front of a user. |
| **Ship, then sharpen** | Every project here is deployed rather than demoed from a laptop. Feedback from a broken deployment teaches more than three weeks of local polish. |

<br/>

## 💡 Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Tesseract_OCR-5A45FF?style=for-the-badge&logo=tesseract&logoColor=white" />
</div>

<br/>

## 📚 Education

| Degree | Institution | Duration | CGPA |
|---|---|---|---|
| **B.Tech, Computer Science & Engineering** | Bhagwan Parshuram Institute of Technology (GGSIPU), New Delhi | 2024–2028 | **8.0 / 10** |

<br/>

## 🏆 Achievements

- **Smart India Hackathon** — cleared two internal screening rounds at BPIT in consecutive editions, improving from the college's top 50 teams in 2025 to the top 20 in 2026.
  - SIH 2025 — Nivora (student housing platform) — cleared 2 rounds, college top 50
  - SIH 2026 — Mediksha (ABDH healthcare platform) — cleared 2 rounds, college top 20

<br/>

## 🎯 Currently

- Going deeper on **agentic AI** — multi‑agent orchestration, tool use and evaluation
- Strengthening **TypeScript** and **DSA** fundamentals
- Open to **SDE, full‑stack, front‑end, forward‑deployed and AI engineering** internships and full‑time roles

<br/>

<div align="center">

  <!-- Footer waving -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:3b82f6&height=120&section=footer" width="100%" />

</div>

<br/>

*⭐️ This profile is a curated showcase of projects I'm proud of. Each repo has a professional README, MIT licence, topics, and CI where applicable. Feel free to explore, fork, or drop a message!*
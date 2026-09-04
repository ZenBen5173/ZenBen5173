<h1 align="center">Hi, I'm Zen Ben 👋</h1>

<p align="center">
  I build things that actually get used, not projects that sit on a shelf.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based%20in-Klang%2C%20Malaysia-4f46e5" alt="Klang, Malaysia" />
  <img src="https://img.shields.io/badge/Open%20to-Internships%20(Jan%202027)-brightgreen" alt="Open to internships from January 2027" />
  <a href="https://www.linkedin.com/in/zen-ben"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:teozenben05@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I'm a Data Analytics undergrad at **Sunway University** (CGPA 3.77) who kept noticing the same
thing: real problems around me, from university bureaucracy to smallholder farms to small
businesses run out of a WhatsApp group, were waiting on software nobody had bothered to build
well. So I started building it, mostly as agentic AI systems, and shipping it to real users.

- Building **FlowNote Solutions**, a SaaS for SME workflow digitalisation
- Vice President @ **Sunway University AWS Student Builder Group**

---

## What I'm building

Most of my recent work is the same idea pointed at different problems: let an AI *decide and act*
inside a real workflow, with a human able to see and override every step.

### [Service Desk Command Center](https://github.com/ZenBen5173/service-desk-command-center) · Autopilot Asia 2026, 3rd of 1200+

An AI service desk built on a contrarian idea: the fastest ticket is the one nobody has to raise.
Rather than closing tickets faster, it clusters them by root cause, proposes the permanent fix for
each, refuses to act when it should stop, and never reports a metric it can't back with real data.
Placed 3rd of 1200+ participants in the Customer Support track, built as a team of two.

- **Stack:** Next.js, FastAPI, PostgreSQL, Docker, Supervity Auto agents

### [UniGuide](https://github.com/ZenBen5173/uniguide) · UMHackathon 2026, 2nd Runner-Up

An AI co-pilot for university paperwork. Instead of a static form, Z.AI's GLM reads the official
SOP and the applicant's history and emits the next step at runtime, so students are never stuck
guessing what comes next and coordinators get pre-digested briefings and editable decision letters.

- Three role surfaces: student portal, coordinator inbox, admin dashboard
- Auto-extracted briefings with confidence scores and SOP citations
- Letter generation with hallucination checks and a 5-minute decision-undo window
- **Stack:** Next.js 15, TypeScript, Supabase (Postgres + pgvector + Realtime), Z.AI GLM-4.6, Vercel

### GustFlow · FlowNote Solutions *(in production)*

A multi-tenant SaaS that lets a small business model its exact task-and-approval workflow instead
of bending its process around rigid or paywalled tools. Role-based permissions decide who can act,
and each approval routes to specific people. Deployed for a first paying client, a Malaysian
hardware business.

- **Role:** Sole developer, end-to-end product development
- **Stack:** Next.js, TypeScript, Supabase, Tailwind, Vercel

### [AgroSim](https://github.com/ZenBen5173/agrosimulator) · MyAI Future Hackathon Finalist

AI farm management for Malaysian smallholder farmers: satellite farm mapping, photo-based crop
disease detection, and AI-generated daily plans, giving small farms the precision tools normally
reserved for big commercial operations.

- **Stack:** Next.js, TypeScript, Gemini AI, Firebase Genkit, Supabase

### [Sound file transfer](https://github.com/ZenBen5173/sound-file-transfer) · data over sound

Chirp moves a link or a note between two phones using sound alone: one phone plays a short
musical chirp, the other listens and reads it back. No wifi, no Bluetooth pairing, no camera,
no app install. It is a static site with no build step, and it uses a fountain code so an image
can survive being carried across dozens of lossy chirps, joining mid-transfer and still finishing. **[Try it live](https://sound-file-transfer.vercel.app/)** on two phones.

- **Stack:** vanilla HTML/CSS/JS, ggwave (audio modem), Web Crypto (AES-GCM), a GF(2) fountain code

---

## More things I've built

- **[HelpMeGuru](https://github.com/ZenBen5173/helpmeguru)** · Devin x Qwen Hackathon. An AI mentor
  that reads a project brief and hands each student in a group a *different* role with a reason,
  over Telegram, running on Qwen.
- **myTask** *(private)* · a full task manager with a web dashboard (list, board, table and
  calendar views, workload and completion charts) plus a WhatsApp way in: text it in plain
  language and an AI turns it into a task, mirrored to Google Calendar. It also tracks its own
  running cost and connection health.
- **[Flight Delay Big Data study](https://github.com/ZenBen5173/IST3134-Flight-Delay-BigData)** · pandas
  on one machine vs. PySpark on AWS EMR, benchmarked over 62M flight records.
- **[Component library](https://github.com/ZenBen5173/component-library)** · 77 UI components with the
  micro-interactions already built in, browsable in a [live gallery](https://component-library-rho.vercel.app/).
- **SQL & NoSQL injection demos** · vulnerable-vs-hardened pairs for
  [Oracle](https://github.com/ZenBen5173/oracle-sql-experiment) and
  [MongoDB](https://github.com/ZenBen5173/mongo_nosql_injection), showing the attack and the one change
  that stops it.

---

## Toolbox

**Data**
<br />
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/SAS-0766D1?logo=sas&logoColor=white" alt="SAS" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/pgvector-4169E1" alt="pgvector" />

**Frontend / Backend**
<br />
<img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white" alt="Tailwind" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white" alt="Supabase" />
<img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI" />

**Cloud**
<br />
<img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white" alt="Vercel" />

**AI tooling**
<br />
<img src="https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white" alt="Claude Code" />
<img src="https://img.shields.io/badge/Claude%20API-D97757?logo=anthropic&logoColor=white" alt="Claude API" />
<img src="https://img.shields.io/badge/Z.AI%20GLM-4f46e5" alt="Z.AI GLM" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/Firebase%20Genkit-FFCA28?logo=firebase&logoColor=black" alt="Firebase Genkit" />

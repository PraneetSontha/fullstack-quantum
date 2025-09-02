# Fullstack Quantum

> A living portfolio of full-stack projects by **Praneet Sontha** — built while pursuing NxtWave’s full-stack program and beyond.

---

## About Me

Hi! I’m **Praneet Sontha**, an electronics student at **The National Institute of Engineering, Mysuru** with hands-on experience in circuit design, debugging, and system analysis. I’m currently sharpening my **full-stack engineering** skills (frontend + backend + databases) through **NxtWave** and building real projects to ship production-ready features.

* 🧭 **Goal:** Turn ideas into usable products, with a strong focus on reliability, quality, and measurable impact.
* 🛠️ **What I’m coding:** Modern web apps with **React**, **Node.js/Express**, **SQL (MySQL/PostgreSQL)**, REST APIs, authentication/authorization, testing, and deployment.
* 📦 **Update cadence:** Weekly (aiming for daily).

I also enjoy projects that blend hardware with software. A few earlier builds include: an **Interactive Air Mouse for Virtual Displays**, a **Temperature Data Logger (Si7051 + I2C EEPROM)**, and a **GNSS-Based Toll Collection System (GPS + RFID)**.

---

## Table of Contents

* [Projects](#projects)
* [Tech Stack](#tech-stack)
* [Quality & Conventions](#quality--conventions)
* [Planned Roadmap](#planned-roadmap)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)
* [Personal Notes](#personal-notes)

---

## Projects

🔎 Each project lives in its own folder with a dedicated README, screenshots, and (where possible) live demos.

**Current Projects:**

* [`Static Website - Advanced Technology/`](./Static%20Website%20-%20Advanced%20Technology/) — Static website titled **Advanced Technology**  
	(Files: [`Index.html`](./Static%20Website%20-%20Advanced%20Technology/Index.html) - Main HTML, [`index.css`](./Static%20Website%20-%20Advanced%20Technology/index.css) - Stylesheet)

* [`Static Website - Flats/`](./Static%20Website%20-%20Flats/) — Static website **Sunrise Avenue (Flats Listing)**  
	(Files: [`flats_index.html`](./Static%20Website%20-%20Flats/flats_index.html) - Main HTML, [`flats_index.css`](./Static%20Website%20-%20Flats/flats_index.css) - Stylesheet)

**Structure (example):**

```
fullstack-quantum/
├─ frontend/
│  ├─ <project-name>/
│  └─ ...
├─ backend/
│  ├─ <project-name>/
│  └─ ...
├─ fullstack/
│  ├─ <project-name>/
│  └─ ...
├─ playgrounds/        # quick experiments, POCs
├─ docs/               # shared docs, diagrams, notes
└─ tools/              # scripts, generators, CI helpers
```

---

## Tech Stack

**Frontend**

* React, Vite/Next.js
* HTML5, CSS3, Tailwind CSS
* TypeScript, Zustand/Redux

**Backend**

* Node.js, Express / Fastify
* REST APIs, JWT/OAuth, role-based auth
* Validation with Zod/Yup

**Databases & Data**

* MySQL / PostgreSQL
* Prisma / Sequelize
* Basic MongoDB where document models fit

**DevEx & Tooling**

* Git & GitHub, Husky + lint-staged
* ESLint, Prettier
* Jest (unit), Supertest (API), Cypress/Playwright (e2e)
* Docker (dev containers), GitHub Actions (CI)

---

## Quality & Conventions

* **Code style:** ESLint + Prettier (strict).
* **Commits:** Conventional Commits (`feat:`, `fix:`, `docs:`, `refactor:`, `test:` …).
* **Branching:** `main` (stable) ← feature branches (`feat/<scope>`, `fix/<scope>`).
* **Testing:** Unit (Jest), API (Supertest), and e2e (Cypress/Playwright).
* **Security:** No secrets in VCS. Use `.env` for environment variables.
* **Docs:** Each project includes architecture notes and screenshots/GIFs.

---

## Planned Roadmap

* ✅ Baseline CRUD apps with clean architecture
* ✅ AuthN/AuthZ foundation (sessions + refresh tokens)
* 🔜 Deploy selected projects to Vercel/Render/Railway
* 🔜 Add PostgreSQL + Prisma migrations and seed scripts
* 🔜 Introduce caching (Redis) for hot endpoints
* 🔜 Monitoring & logging (pino + Prometheus/Grafana, or hosted APM)

I update this repository **weekly** (aiming for daily).

---

## Contact

* GitHub: [@PraneetSontha](https://github.com/PraneetSontha)
* Email: [professional127me@gmail.com](mailto:professional127me@gmail.com)
* LinkedIn: [linkedin.com/in/praneet-sontha](https://www.linkedin.com/in/praneet-sontha)

If you’re a recruiter or hiring manager, feel free to explore the `fullstack/` folder first for end‑to‑end apps and the `backend/` folder for API craftsmanship.

---

## Acknowledgements

* **NxtWave** for the structured full‑stack curriculum and project‑driven approach.
* Mentors, peers, and the open-source community.

---

## Personal Notes

<details>
<summary>⚙️ Internal notes (ignore)</summary>

* 📦 Update cadence: Weekly (aiming for daily). Reminder: keep consistency.
* 🛠️ Tech stack: TypeScript, Zustand/Redux *(where helpful — suggestion for me)*.
* 🛠️ Databases: MongoDB *(optional, for me if needed)*.
* 📜 Past projects: Air Mouse, Data Logger, GNSS Toll System *(personal background context — not part of this repo)*.
* 📂 Projects: Each should include README, screenshots, and live demo links *(expectation for me — follow this pattern)*.
* 📁 Repo structure: use frontend/backend/fullstack folders *(guideline for me — future organization)*.
* 🧪 Quality: run lint/format before commits, write unit + e2e tests *(checklist for me)*.
* 📈 Roadmap milestones: deployment, database migrations, caching, monitoring *(reminders for me)*.
* ⏰ Commitment: update weekly/daily *(commitment reminder for me)*.

</details>

---

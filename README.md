<h1 align="center">Hi, I'm Alaa</h1>
<p align="center">IT Graduate · Cybersecurity Focus · Web Developer</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alaa-alfaifi-48432435a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:rgmalaa@gmail.com">
    <img src="https://img.shields.io/badge/Email-rgmalaa%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/ajx-dev">
    <img src="https://img.shields.io/badge/GitHub-ajx--dev-181717?style=flat&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

## About Me

Recent IT graduate with a cybersecurity focus, currently building full-stack
web applications and looking for a web developer role. My projects lean
toward getting the fundamentals right — real authentication, validated
inputs, and documented security tradeoffs — rather than just shipping
features.

## Featured Projects

### Thimar — Blockchain Agricultural Supply Chain Platform

My graduation project: a full-stack platform for tracking agricultural crop
batches through the supply chain. Farmers register and manage crop batches,
regulatory authorities verify and approve them, and consumers scan a QR
code to instantly see a product's origin, harvest details, and
blockchain-verified status.

- **Frontend:** React 19, Vite, React Router, Tailwind CSS, Radix UI,
  TanStack Query, Recharts, QR scanning (html5-qrcode / jsQR)
- **Backend:** Node.js, Express, MongoDB Atlas + Mongoose, Firebase
  Firestore + Admin SDK, JWT auth, bcrypt, Nodemailer
- **Blockchain:** Solidity smart contract (`ThimarBatches.sol`) that
  anchors batch data hashes on the Ethereum Sepolia testnet, built and
  deployed with Hardhat via ethers.js
- **My role:** Team project — full-stack developer responsible for
  building the entire web platform (frontend, backend, and deployment)
- **Repo:** [github.com/ajx-dev/thimar-platform](https://github.com/ajx-dev/thimar-platform)

### SprintOS — Team Accountability Platform

A solo full-stack project: instead of a private todo list, commitments and
deadlines are visible to the whole team the moment they're made. Includes
deadline-driven commitments with named-assignee subtasks, per-user and
team streaks, a cross-team leaderboard, in-app notifications, and a
dashboard/calendar view.

- **Backend:** Node.js, Express, TypeScript, Prisma ORM, PostgreSQL,
  Redis, Zod validation, JWT auth with bcrypt
- **Frontend:** React, Vite, TypeScript, Tailwind CSS, TanStack Query,
  React Router
- **Infra:** pnpm/Turborepo monorepo, Docker Compose, GitHub Actions CI
- **My role:** Solo — designed and built the entire stack, then ran three
  rounds of self-directed security review (backend, frontend, repo/infra
  hygiene), documented in [`SECURITY_AUDIT.md`](https://github.com/ajx-dev/SprintOS/blob/main/SECURITY_AUDIT.md)
- **Repo:** [github.com/ajx-dev/SprintOS](https://github.com/ajx-dev/SprintOS)

### Other Projects

- **[color-palette-generator](https://github.com/ajx-dev/color-palette-generator)** —
  a small browser-based tool for generating color palettes.

## Skills

Levels reflect real usage in the projects above, not self-rating.

**Languages**
- JavaScript, TypeScript, HTML/CSS — *Intermediate* (used across both major projects)
- Solidity — *Learning* (one smart contract, written for Thimar)

**Frontend**
- React, Vite, React Router, TanStack Query, Tailwind CSS — *Intermediate*
- Radix UI, Recharts — *Learning*

**Backend**
- Node.js, Express, REST API design — *Intermediate*
- JWT authentication, bcrypt password hashing, Zod validation — *Intermediate*
- Prisma ORM, MongoDB/Mongoose, Firebase (Auth, Firestore, Admin SDK) — *Learning*

**Databases & Infrastructure**
- PostgreSQL, Redis, MongoDB Atlas — *Learning*
- Docker / Docker Compose, GitHub Actions CI — *Learning*

**Blockchain**
- Solidity, Hardhat, ethers.js, Ethereum testnet deployment — *Learning*

**Security**
- Secure auth patterns (server-side JWT validation, never trusting
  client-supplied identity), input validation — *Intermediate*
- Structured security self-review and documentation (see SprintOS's
  security audit above) — *Intermediate*
- Broader application security (OWASP-aligned secure coding) — *Learning*,
  building on cybersecurity coursework

## Currently Learning

Expanding backend and infrastructure depth (CI/CD, containerized
deployments) and continuing to apply my cybersecurity background to
everyday web development — treating auth, validation, and threat modeling
as part of building the feature, not an afterthought.

<div align="center">

<img src="https://raw.githubusercontent.com/hatchup-io/.github/main/profile/assets/banner.svg" alt="HatchUp — build, fund, and scale with structure" width="100%">

<br>

[![Website][badge-web]][link-web]
[![LinkedIn][badge-li]][link-li]
[![X][badge-x]][link-x]
[![Email][badge-mail]][link-mail]

**Dubai&nbsp;·&nbsp;United Arab Emirates&nbsp;&nbsp;|&nbsp;&nbsp;Montreal&nbsp;·&nbsp;Canada**

</div>

---

**HatchUp Investment LLC** is a multi-layered ecosystem built to discover, build, fund, and internationalize
high-potential ventures. We don't only write checks — we design the operating systems, ship the software, and
run the infrastructure alongside our founders and clients.

This organization holds the engineering behind that ecosystem. **Our repositories are private**, so what you'll
find below are the products themselves and the people who build them.

> **Structure before scale.** Sustainable growth starts with disciplined operational design — not louder ambition.

<br>

## The ecosystem

Four business lines. Each is built to stand alone — and engineered to compound when used together.

| | Line | What it does |
| :--: | :-- | :-- |
| 💠 | **[VC](https://hatchup.capital/capital)** | Strategic capital and board-level governance for growth-stage ventures, backed by our own operating infrastructure. |
| 🧪 | **[Venture Studio](https://hatchup.capital/foundry)** | Where we found, fund, and build our own startups — from opportunity mapping to go-to-market. |
| 🚀 | **[Launchpad](https://hatchup.capital/launchpad)** | Legal, financial, and operational structure that lets startups and businesses go global without going solo. |
| 🔧 | **[Adapt Lab](https://hatchup.capital/adapt-lab)** | Structural modernization for established businesses — operational redesign, digitization, and market expansion. |

<br>

## What we build

### Venture Studio — our own ventures

| Product | What it is | Live |
| :-- | :-- | :-- |
| **Katavex** | AI-assisted OKR and performance management that keeps organizational goals alive across teams instead of turning them into static documents. | [katavex.com](https://katavex.com) |
| **Pathinnova** | AI-powered immigration pathway analysis that guides applicants through complex legal and procedural routes. | [pathinnova.com](https://pathinnova.com) · [app](https://app.pathinnova.com) |
| **Phronexia** | Enterprise decision engine that pairs LLMs with Multi-Criteria Decision Making to turn unstructured inputs into quantifiable, explainable rankings. | *private beta* |
| **Ordnix** | Order and workflow management for operations teams. | *in development* |

### VC — the platform behind the capital

| Product | What it is | Live |
| :-- | :-- | :-- |
| **Venture Discovery** | Founder and venture intake, screening, and pipeline for the studio and the fund. | [venture.hatchup.capital](https://venture.hatchup.capital) |
| **Venture Platform** | Portfolio, deal, and governance workspace used across our investments. | [app.vc.hatchup.capital](https://app.vc.hatchup.capital) |
| **Valuation Simulator** | Monte Carlo startup valuation model — scenario ranges instead of a single optimistic number. | [valuation.hatchup.capital](https://valuation.hatchup.capital) |

### Launchpad — infrastructure for international operations

| Product | What it is | Live |
| :-- | :-- | :-- |
| **Launchpad** | Company registration, free-zone setup, compliance, and the financial workflows of operating cross-border from the UAE. | [launchpad.hatchup.capital](https://launchpad.hatchup.capital) · [app](https://app.launchpad.hatchup.capital) |

### Adapt Lab — platforms we build for others

| Product | What it is | Live |
| :-- | :-- | :-- |
| **yFace** | Face-proportion analysis and aesthetic-surgery recommendation powered by Face Mesh and LLMs, with dedicated patient and practitioner panels. | [app.yface.clinic](https://app.yface.clinic) |
| **Bayat Group** | Immigration and second-citizenship counsel platform — case intake, eligibility, and client workflow. | [bayatgroup.pathinnova.com](https://bayatgroup.pathinnova.com) |
| **MatchPointIQ** | B2B matchmaking and deal management — sources suppliers via directory scraping and vector search, then handles contracts and compliance end to end. | *private* |
| **Adapt Lab Assistant** | Multi-tenant RAG platform that lets a business train an assistant on its own documents and embed it anywhere. | *private* |

<br>

## The team

The four of us who are actively building the ecosystem today, by where our commits actually land.

<table>
  <tr>
    <td align="center" width="25%">
      <a href="https://github.com/NimaNaghibi143">
        <img src="https://github.com/NimaNaghibi143.png?size=120" width="96" height="96" alt="Nima Naghibi"><br>
        <b>Nima Naghibi</b>
      </a><br>
      <sub>@NimaNaghibi143</sub><br><br>
      <sub>Product engineering across<br>Pathinnova, Katavex, and<br>Adapt Lab platforms —<br>backend and frontend.</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/alirezaqnti">
        <img src="https://github.com/alirezaqnti.png?size=120" width="96" height="96" alt="Alireza"><br>
        <b>Alireza</b>
      </a><br>
      <sub>@alirezaqnti</sub><br><br>
      <sub>Launchpad and shared<br>services — onboarding,<br>payments, IAM, and<br>third-party integrations.</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/Homanloo">
        <img src="https://github.com/Homanloo.png?size=120" width="96" height="96" alt="Mohammad Homanloo"><br>
        <b>Mohammad Homanloo</b>
      </a><br>
      <sub>@Homanloo</sub><br><br>
      <sub>Venture Studio platform —<br>the HatchUp platform stack,<br>Katavex, and the MCDM<br>decision engine.</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/1995parham">
        <img src="https://github.com/1995parham.png?size=120" width="96" height="96" alt="Parham Alvani"><br>
        <b>Parham Alvani</b>
      </a><br>
      <sub>@1995parham</sub><br><br>
      <sub>Infrastructure and platform —<br>deployment, backend<br>architecture, and review<br>across the portfolio.</sub>
    </td>
  </tr>
</table>

<br>

## How we build

Every product in the ecosystem is bootstrapped from the same internal templates and deployed onto the same
infrastructure, so a new venture starts with day-one compliance, auth, payments, and CI already solved.

| Layer | Stack |
| :-- | :-- |
| **Backend** | Django REST Framework · FastAPI · Celery · PostgreSQL · MinIO |
| **Frontend** | Next.js · React · TypeScript · Vite · Tailwind · shadcn/Radix |
| **AI** | LLM orchestration · vector search & embeddings · RAG · MCDM scoring |
| **Platform** | Docker Swarm · Ansible · GitHub Actions · GHCR |
| **Shared services** | identity & access management · payments & billing · document workflows |

<br>

## Work with us

Whether you're building a new venture, scaling an existing business, expanding internationally, or modernizing a
traditional operation — there's a pathway inside the ecosystem for it.

<div align="center">

**[hatchup.capital](https://hatchup.capital)** &nbsp;·&nbsp; **[Schedule a consultation](https://hatchup.capital/contact-us)** &nbsp;·&nbsp; **[info@hatchup.capital](mailto:info@hatchup.capital)**

<sub>© HatchUp Investment LLC · Dubai, UAE · Montreal, QC</sub>

</div>

[link-web]:  https://hatchup.capital
[link-li]:   https://linkedin.com/company/hatchup-capital
[link-x]:    https://x.com/HatchupCapital
[link-mail]: mailto:info@hatchup.capital

<!-- Badge definitions. LinkedIn carries an inline data-URI mark because simple-icons
     (which shields.io draws from) no longer ships a `linkedin` logo slug. -->

[badge-web]:  https://img.shields.io/badge/hatchup.capital-0a1e34?style=for-the-badge&logo=safari&logoColor=e4b562
[badge-x]:    https://img.shields.io/badge/@HatchupCapital-0a1e34?style=for-the-badge&logo=x&logoColor=fcf6e9
[badge-mail]: https://img.shields.io/badge/info@hatchup.capital-0a1e34?style=for-the-badge&logo=maildotru&logoColor=e4b562
[badge-li]:   https://img.shields.io/badge/LinkedIn-0a1e34?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDAxLTIuMDYzLTIuMDY1IDIuMDY0IDIuMDY0IDAgMTEyLjA2MyAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyNSAweiIvPjwvc3ZnPg%3D%3D

<div align="center">

# MyPrepa

**The preparation platform for ambitious students — starting with Tunisia's preparatory classes, growing to France and Morocco.**

[myprepa.tn](https://myprepa.tn) · [myprepa.org](https://myprepa.org) · [Service status](https://status.myprepa.tn)

</div>

---

## What we build

Preparing for a competitive exam means juggling an official programme, years of past papers, scattered
course material and a lot of uncertainty about where you stand. MyPrepa brings all of it into one place.

| | |
|---|---|
| **Official programmes** | Every subject, chapter by chapter, reconstructed from the published texts — with personal progress tracking. |
| **Past exams** | National competitive-exam papers, organised by stream, subject and year. |
| **Document library** | Courses, problem sets and solutions, protected and searchable. |
| **Community & orientation** | Cohorts, peer help, and guidance on choosing an engineering school. |
| **AI-assisted learning** *(in progress)* | A retrieval-augmented assistant grounded in our curated dataset, and personal tutor agents. |

**Where we are:** live in Tunisia for preparatory-class students (MP, PC, T, BG) at [myprepa.tn](https://myprepa.tn),
with video courses at [myprepa.org](https://myprepa.org). France and Morocco are next.

## How it is built

- **Platform** — a single Next.js application serving the student site and our internal consoles.
- **Data pipeline** — crawls official sources, extracts facts with provenance and reconciles them into a canonical
  dataset (bronze → silver → gold) that feeds the platform and, soon, the AI assistant.
- **Operations** — CI-built, human-approved deploys; monitoring at [status.myprepa.tn](https://status.myprepa.tn);
  AI agents that assist the team under explicit human approval.

Our product code is private. Public repositories:

| Repository | Purpose |
|---|---|
| [`myprepa-status`](https://github.com/myprepa/myprepa-status) | Uptime monitoring and the public status page. |
| [`.github`](https://github.com/myprepa/.github) | This profile and organisation-wide community files. |

## Contact

- **Email:** contact@myprepa.tn
- **Facebook:** [facebook.com/myprepa.tn](https://www.facebook.com/myprepa.tn)
- **Security issues:** please follow our [security policy](https://github.com/myprepa/.github/blob/main/SECURITY.md).

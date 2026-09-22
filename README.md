# Victorgesicht

**Security Engineer & Full-Stack Developer** based in Nairobi, Kenya.

I work across the full application lifecycle: building web applications, designing APIs, and finding and fixing the vulnerabilities in them. My public projects span Django/.NET/React development, API design, and security research — from IDOR write-ups and CORS misconfiguration analysis to open-redirect PoCs and browsing through payload collections.

---

## About

- Building secure full-stack applications and REST APIs
- Security research focused on broken access control (IDOR/DOLA), CORS misconfigurations, open redirects, and authentication flaws
- Standing up observability and monitoring stacks (Grafana + Prometheus) to make system behaviour visible
- Writing up findings clearly so the issues get understood, reproduced, and fixed

## Tech Stack

### Languages
Python | JavaScript | C# | PHP | HTML | CSS / SCSS

### Frameworks & Libraries
Django & Django REST Framework | .NET Core | React (Tailwind, Axios) | Laravel

### Security & Testing
OWASP top-ten testing | IDOR / broken access-control testing | CORS policy auditing | open-redirect analysis | payload crafting

### Tooling & Platforms
Git & GitHub | Grafana & Prometheus | SQLite / PostgreSQL | Apache Airflow | Anywhere / Render / pythonanywhere deployments

---

## Selected Projects

### Security research

- **IDOR via predictable ID (client-supplied MD5 hash)** — A write-up on a broken access-control case where an attacker who guesses a valid resource identifier and submits its MD5 hash can access or modify resources they should not be able to.
- **Inconsistent CORS enforcement (.NET)** — Sample bug report and PoC demonstrating how improperly configured CORS can lead to unauthorized data access and privilege escalation (since patched).
- **Referer-based open redirect** — PoC and bug report for a referer-based open redirect found during testing.
- **CORS exploitability POC** — Preflight conditions that determine whether a CORS misconfiguration is actually exploitable.
- **IDOR vulnerability report** — Broken access control write-up covering an application that relied solely on user-controlled input for authorization.
- **payload-Motel** — A personal collection of payloads used to test parameterized endpoints.

### Web application development

- **Django Fullstack** — Django application using DRF view sets with Markdown (Martor) content rendering.
- **m-verify** — C#/React verification application (API + UI) deployed on Render.
- **collectibles** — React + Tailwind marketplace platform for trading manga, magazines, stamps, coins, tech gadgets, and novels.
- **edu-logic** — Django + Django REST API application.

### Observability & tooling

- **agent-monitoring** — AI-coded observability stack: a Grafana dashboard (port 9999) fed by Prometheus and a small Python exporter that reads opencode's local SQLite store and exposes agent-usage metrics (tokens, sessions, activity) — everything bound to localhost.
- **Apache Airflow** — Data-engineering experiments with Airflow.
- **axios-dashboard** — Data dashboard built with React + Axios against a fake JSON API.

---

## Contact

- Blog: [saragossa.pythonanywhere.com](https://saragossa.pythonanywhere.com)
- GitHub: [github.com/victorgesicht](https://github.com/victorgesicht)

---

*Profile generated from the public project history — repositories, languages, and topic tags reflect practical, shipped work.*
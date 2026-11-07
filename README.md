# Hi, I'm Sinan

Computer science student at UT Dallas (transferred from Austin Community College), focused on **open source, security, and backend systems**. I'm looking for part-time or contract open-source maintenance and security work.

---

## Security & open source

In July 2026 I found malicious code in a contribution submitted to an open-source project, reviewed it, and reported it to the maintainer. The project's sandboxed Docker environment contained its execution. The UK AI Security Institute later contacted me, and my findings were referenced in its public incident report (August 2026).

---

## Things I've built

**[IMS: Inventory Management System](https://github.com/sinan-can-demir/ims)**: event-sourced inventory backend (FastAPI, PostgreSQL) with a dbt/DuckDB analytics pipeline and Prophet demand forecasting. Multi-tenancy shipped across 16 self-reviewed PRs, including a fix for a bug that would have wiped inventory state across organizations and several IDOR fixes. CI scans dependencies, secrets, and containers on every PR.

**[Orbital Mechanics Engine](https://github.com/sinan-can-demir/orbital-mechanics-engine)**: C++17 N-body simulator with five integrators (RK4, Leapfrog, Yoshida4, RK45, Hermite), a Schwarzschild 1PN correction, JPL HORIZONS/SPICE data, and a Python API. Zenodo-archived: [10.5281/zenodo.21215316](https://doi.org/10.5281/zenodo.21215316).

**[Telepathy](https://github.com/sinan-can-demir/Telepathy)**: end-to-end encrypted anonymous chat, forked from the open-source "pentour" project and extended with forward secrecy (HMAC sender-key ratchet), TOFU key verification, hash-chained transcripts, WebSockets, and a Tor hidden-service deployment.

**[PR Scanner](https://github.com/sinan-can-demir/pr-scanner)** *(in progress)*: static scanner that flags signs of malicious code in pull requests, with explainable, rule-based findings.

**[AI Influencer](https://github.com/sinan-can-demir/ai_influencer)**: persona content pipeline with a human draft-and-approve gate (nothing posts without review) and audit logs.

---

## Tech

Python, C++17, SQL, Bash, FastAPI, PostgreSQL, Linux, Git, GitHub Actions.

---

## Let's connect

LinkedIn: https://www.linkedin.com/in/sinan-can-demir

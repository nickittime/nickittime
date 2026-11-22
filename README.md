<!--
  Profile README for github.com/nickittime.
  Goes in a PUBLIC repo named exactly "nickittime" (not yet created), with the two
  banner SVGs in an "assets" folder next to it.
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img src="./assets/banner-light.svg" width="100%" alt="Manvender Singh. Software Engineer Trainee: C++, C, Python. Open to work, Bengaluru, India.">
</picture>

<div align="center">

<div align="center">

# Manvender Singh

**Software Engineer (2027 Grad) · C++ · Python · Backend & Guardrailed AI**

*I build backend, storage, and AI systems in C++ and Python—and verify them against invariants, crash states, and deterministic guardrails.*

<br>

[![Status](https://img.shields.io/badge/Open_to_Work-SDE--1_%7C_Backend_%7C_Systems_%7C_Applied_AI-16a34a?style=for-the-badge)](mailto:work.singhmanvender16@gmail.com)
[![Availability](https://img.shields.io/badge/Available-Jan_2027_(Full--Time)-2563eb?style=for-the-badge)](mailto:work.singhmanvender16@gmail.com)

<br>

[![Email](https://img.shields.io/badge/Email-work.singhmanvender16%40gmail.com-1e293b?style=flat-square&logo=gmail&logoColor=white)](mailto:work.singhmanvender16@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manvender_Singh-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manvender-singh-90a53a300)
[![Portfolio](https://img.shields.io/badge/Portfolio-nickittime.github.io-0f172a?style=flat-square&logo=github&logoColor=white)](https://nickittime.github.io)

</div>

---

## At a Glance

| Category | Highlights |
| :--- | :--- |
| **Education** | **B.E. in Information Science Engineering** — Sir M. Visvesvaraya Institute of Technology, Bengaluru *(2023 – 2027)* |
| **Published Patent** | Co-inventor — *Context-Aware Device Usage Identification Using Sensor Transformation and Lightweight Knowledge Distillation* (`Pub. No. IN202641130247 A1`) |
| **Research** | Accepted conference paper on longitudinal smartphone behavioral forecasting at **DSISys 2026** |
| **Problem Solving** | **200+** Data Structures & Algorithms problems solved across **C++** and **Python** |

---

## Featured Projects

### 1. `kvlite` — Crash-Safe Key-Value Store in C++17
> `C++17` · `CMake` · `GoogleTest` · `GitHub Actions` · `AddressSanitizer`

* **Core Engine:** In-memory key-value store supporting **$O(1)$ LRU eviction** (hash map + doubly linked list), TTL key expiration, and an append-only log replayed on restart.
* **Crash Recovery:** Detects and truncates incomplete trailing log records caused by simulated crashes to guarantee state consistency on startup.
* **Verification & CI:** Validated by **34 GoogleTest tests**—including **20,000 randomized operations** verified against a reference model—with CI running across GCC, Clang, MSVC, and AddressSanitizer.

### 2. `Freight Cost Watcher` — Anomaly Detection with a Guardrailed LLM
> `Python` · `pandas` · `ChromaDB` · `Groq LLM API` · `pytest` · `Docker`

* **Core Engine:** Detects sudden rate spikes and slow cost creep across **7 Indian road corridors (728 route-weeks)** using own-route and peer-route baselines with a hysteresis rule.
* **Guardrailed AI:** Pairs LLM root-cause proposals across 22 flagged candidates with **5 deterministic guardrails** that validate and filter every explanation before acceptance.
* **Verification & Determinism:** Backed by **39 offline tests**—catching **9/9 planted events**, producing identical output across **3 cold runs**, and running deterministically without an API key.

### 3. `Aegis Risk Engine` — Financial Risk-Management API
> `Python` · `FastAPI` · `PostgreSQL` · `ClickHouse` · `Redis` · `Docker`

* **Core Engine:** Implements credit, market, and operational risk engines alongside automated RBI provisioning and regulatory-return generation.
* **Security & Ingestion:** Enforces JWT authentication, MFA for elevated roles, and four-eyes approval for credit overrides, paired with SFTP batch ingestion into ClickHouse.
* **Verification & CI:** Covered by **11 unit tests** with a GitHub Actions pipeline running **Ruff**, **Bandit**, and **pytest** on every push.

---

## Tech Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| **Languages** | `C++ (C++17)` · `C` · `Python` · `SQL` · `TypeScript` |
| **Backend & Data** | `FastAPI` · `Node.js` · `PostgreSQL` · `ClickHouse` · `Redis` · `pandas` · `NumPy` · `ChromaDB` |
| **Testing & DevOps** | `GoogleTest` · `pytest` · `CMake` · `Git` · `GitHub Actions` · `Docker` · `Linux` |
| **CS Fundamentals** | `Data Structures & Algorithms` · `OOP` · `Operating Systems` · `DBMS` · `Computer Networks` |

---

<div align="center">

### Get in Touch

**Bengaluru, India** *(Open to relocation)* · Fastest response via **[work.singhmanvender16@gmail.com](mailto:work.singhmanvender16@gmail.com)**

[GitHub](https://github.com/nickittime) · [LinkedIn](https://www.linkedin.com/in/manvender-singh-90a53a300) · [Portfolio](https://nickittime.github.io)

</div>

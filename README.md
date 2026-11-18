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

### Software Developer (fresher) · C++ · C · Python

Final-year B.E. Information Science student in Bengaluru.<br>
I build small systems and test them properly, in C++ and Python.

**Open to work:** Software Engineer Trainee and fresher roles in Bengaluru

[![Email](https://img.shields.io/badge/Email-work.singhmanvender16%40gmail.com-2743c8?style=flat-square&logo=gmail&logoColor=white)](mailto:work.singhmanvender16@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-manvender--singh-2743c8?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manvender-singh-90a53a300)
[![Portfolio](https://img.shields.io/badge/Portfolio-nickittime.github.io-2743c8?style=flat-square)](https://nickittime.github.io)
[![Resume](https://img.shields.io/badge/Resume-PDF-2743c8?style=flat-square)](https://nickittime.github.io/resume.pdf)

</div>

---

## About

- **Education:** B.E. Information Science Engineering, Sir M. Visvesvaraya Institute of Technology, Bengaluru (2023 to 2027)
- **Patent:** Co-inventor on a published Indian patent, *Context-Aware Device Usage Identification Using Sensor Transformation and Lightweight Knowledge Distillation* (App. No. 202641130247 A)
- **Research:** Conference paper on longitudinal behavioral forecasting, accepted at DSISys 2026
- **Practice:** 200+ data structures and algorithms problems solved in C++ and Python

## Tech stack

| | |
|---|---|
| **Languages** | C++, C, Python, SQL |
| **Backend and data** | FastAPI, PostgreSQL, ClickHouse, Redis, pandas, NumPy, ChromaDB |
| **Testing and tools** | GoogleTest, pytest, CMake, Git, GitHub Actions, Docker, Linux |
| **Fundamentals** | Data structures and algorithms, OOP, operating systems, DBMS, computer networks |

## Featured projects

### [kvlite](https://github.com/nickittime/kvlite): key-value store in C++17
> `C++17` `CMake` `GoogleTest` `GitHub Actions`

- In-memory store with **LRU eviction**, **expiring keys** and an **append-only file** that is replayed on restart
- O(1) LRU from a hash map plus a doubly linked list. An incomplete last log record from a crash is detected and cut off.
- **34 GoogleTest tests**, including 20,000 random operations checked against a reference model. CI on GCC, Clang, MSVC and AddressSanitizer.

### [Freight Cost Watcher](https://github.com/nickittime/freight-cost-watcher): anomaly detection with a checked LLM
> `Python` `pandas` `ChromaDB` `Groq LLM API` `pytest` `Docker`

- Finds sudden spikes and slow **cost creep** across 7 Indian road corridors (728 route-weeks), using own-route and peer-route baselines with a hysteresis rule
- An LLM proposes a cause for each of the 22 candidates, and **5 deterministic guardrails** decide whether to accept it
- 39 offline tests. Caught 9/9 planted events, and output was identical across 3 cold runs. [Runs without an API key](https://github.com/nickittime/freight-cost-watcher#run-it).

### [Aegis Risk Engine](https://github.com/nickittime/aegis-risk-engine): risk-management API for a lender
> `Python` `FastAPI` `PostgreSQL` `ClickHouse` `Redis` `Docker`

- Credit, market and operational risk engines, plus RBI provisioning and regulatory-return generation
- JWT login, MFA for elevated roles, and four-eyes approval for credit overrides. SFTP batch ingestion into ClickHouse.
- 11 unit tests. GitHub Actions runs Ruff, Bandit and pytest.

<!--
GitHub stats cards are left out on purpose. The public stats server is often rate-limited
or paused, which leaves a broken image, and your contribution graph already shows below.
-->

## Contact

Email is the fastest way to reach me: **[work.singhmanvender16@gmail.com](mailto:work.singhmanvender16@gmail.com)**
Also on [LinkedIn](https://www.linkedin.com/in/manvender-singh-90a53a300), and my portfolio is at [nickittime.github.io](https://nickittime.github.io).

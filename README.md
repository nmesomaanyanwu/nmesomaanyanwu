<h1 align="center">Nmesoma Anyanwu</h1>

<p align="center">
  Computer Science @ The University of Manchester
</p>

---

## Experience

- **Software Engineering Intern — Compare the Market** (Jul – Sep 2026)
  Shipped OAuth 2.0 flows and scope validation in a production .NET identity service, and added contract tests that catch schema changes at build time. Won Most Ambitious and Best Execution at the internal hackathon; prompt prefix caching cut LLM token usage by 69%.

- **Deputy Sector Lead — Algorithmic Trading Society, University of Manchester** (Sep 2026 – present)
  Co-lead market research and signal development across equities, FX, commodities and fixed income. Design the Algothon simulation grading and wrote the training packs used by sector leads.

- **Technical Lead — Soirée** (Feb 2026 – present)
  Built the frontend and backend of a platform connecting creative students across four Manchester universities. React Native, FastAPI, Supabase. MVP in two weeks, closed beta with 20+ students, launched Oct 2026.

- **Engineering Work Experience — Williams Racing F1** (Jul 2026)
  Selected from 3,000+ applicants for a week at Grove with Vehicle Performance engineers. Ran tyre-degradation simulations comparing compounds across circuits to assess position-loss risk and pit-stop timing.

- **Nomura Women in Quantitative Finance** (Oct 2026)
  Programme on quantitative finance in fixed income and FX. Built a logistic regression model on 10,000 RFQ records to predict bond quote win probability and invert it into the spread needed for a target win rate (~80% precision on held-out data).

---

## Featured Project

**[SPARSE9](https://github.com/nmesomaanyanwu/SPARSE9) — Limit Order Book Matching Engine** (C++20, TCP/IP, CMake)
Matching engine with full price-time priority and LIMIT, MARKET, IOC and FOK orders, with O(1) cancellation. Measured **84 ns median / 584 ns p99** matching-core latency and **4.8 µs / 11.6 µs** end-to-end order-to-ack over 10M orders. Single-writer book fed by a bounded MPSC queue. Currently adding Kalshi and Polymarket market-data handlers to test whether displayed prediction-market prices are executable at quoted size.

---

## Achievements

- **Morgan Stanley FX Trading Challenge** — 1st place (EUR/GBP mean reversion, 1 of 9 teams)
- **QuantiHack 2026** (Jane Street and Optiver) — 3rd of 300+ teams, Best Algorithm by P&L; 8th of 43 at the finals
- **UKIEPC 2026** (ICPC UK & Ireland Subregional) — Top 16%
- **Jane Street Monthly Puzzle** — Published solver (*Andy's Afternoon Amble*)

---

## Technical Skills

**Systems and low latency:** C++ · C · multithreading · atomics and memory ordering · lock-free queues · TCP/IP · Linux · perf · gdb
**Quant and data:** Python · pandas · NumPy · backtesting · time-series analysis · statistics
**Backend and web:** C# · .NET · FastAPI · PostgreSQL · TypeScript · React · React Native · Supabase · AWS · Docker · GitHub Actions

---

## Current Focus

- Extending SPARSE9 with cross-venue prediction-market data (Kalshi, Polymarket)
- Lock-free data structures and concurrency
- Operating systems and computer architecture

---

## Writing

I write about systems programming and the design decisions behind SPARSE9 on [The Latency Log](https://nmesomaanyanwu.hashnode.dev).

- [The Networking Layer](https://nmesomaanyanwu.hashnode.dev/latency-the-networking-layer)
- [Traversal Order Is Ownership Order](https://nmesomaanyanwu.hashnode.dev/traversal-order-is-ownership-order)

---

## Connect

<p>
  <a href="https://www.linkedin.com/in/nmesoma-anyanwu-5a40a131b">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:nmesomaanyanwu.work@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=linkedin&logoColor=white" alt="Email"/>
  </a>
</p>

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

### [SPARSE9](https://github.com/nmesomaanyanwu/SPARSE9) — Limit Order Book Matching Engine
*C++20 · TCP/IP · CMake*

- Matches buy and sell orders over TCP with full price-time priority, supporting LIMIT, MARKET, IOC and FOK orders
- Cancels any order in O(1) by mapping each order ID straight to its place in the book
- Feeds a single-writer book from a bounded MPSC queue, avoiding locks so updates can't tear or deadlock
- Matches in 84 ns median / 584 ns p99, and acknowledges orders end to end in 4.8 µs / 11.6 µs over 10M orders
- Next up: Kalshi and Polymarket market-data handlers, to test whether displayed prediction-market prices are executable at quoted size
---

## Achievements

- **Morgan Stanley FX Trading Challenge** — 1st place (EUR/GBP mean reversion, 1 of 9 teams)
- **QuantiHack 2026** (Jane Street and Optiver) — 3rd of 300+ teams, Best Algorithm by P&L; 8th of 43 at the finals
- **UKIEPC 2026** (ICPC UK & Ireland Subregional) — Top 16%
- **Jane Street Monthly Puzzle** — Published solver (*Andy's Afternoon Amble*)

---

## Technical Skills

**Systems and low latency**
<table>
  <tr>
    <td><img src="https://img.shields.io/badge/C%2B%2B-1f6feb?style=for-the-badge" alt="C++"/></td>
    <td><img src="https://img.shields.io/badge/C-1f6feb?style=for-the-badge" alt="C"/></td>
    <td><img src="https://img.shields.io/badge/Multithreading-1f6feb?style=for-the-badge" alt="Multithreading"/></td>
    <td><img src="https://img.shields.io/badge/Atomics%20%26%20Memory%20Ordering-1f6feb?style=for-the-badge" alt="Atomics and Memory Ordering"/></td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/Lock--Free%20Queues-1f6feb?style=for-the-badge" alt="Lock-Free Queues"/></td>
    <td><img src="https://img.shields.io/badge/TCP%2FIP-1f6feb?style=for-the-badge" alt="TCP/IP"/></td>
    <td><img src="https://img.shields.io/badge/Linux-1f6feb?style=for-the-badge" alt="Linux"/></td>
    <td><img src="https://img.shields.io/badge/perf-1f6feb?style=for-the-badge" alt="perf"/></td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/gdb-1f6feb?style=for-the-badge" alt="gdb"/></td>
  </tr>
</table>

**Quant and data**
<table>
  <tr>
    <td><img src="https://img.shields.io/badge/Python-2ea043?style=for-the-badge" alt="Python"/></td>
    <td><img src="https://img.shields.io/badge/pandas-2ea043?style=for-the-badge" alt="pandas"/></td>
    <td><img src="https://img.shields.io/badge/NumPy-2ea043?style=for-the-badge" alt="NumPy"/></td>
    <td><img src="https://img.shields.io/badge/Backtesting-2ea043?style=for-the-badge" alt="Backtesting"/></td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/Time--Series%20Analysis-2ea043?style=for-the-badge" alt="Time-Series Analysis"/></td>
    <td><img src="https://img.shields.io/badge/Statistics-2ea043?style=for-the-badge" alt="Statistics"/></td>
  </tr>
</table>

**Backend and web**
<table>
  <tr>
    <td><img src="https://img.shields.io/badge/C%23-8957e5?style=for-the-badge" alt="C#"/></td>
    <td><img src="https://img.shields.io/badge/.NET-8957e5?style=for-the-badge" alt=".NET"/></td>
    <td><img src="https://img.shields.io/badge/FastAPI-8957e5?style=for-the-badge" alt="FastAPI"/></td>
    <td><img src="https://img.shields.io/badge/PostgreSQL-8957e5?style=for-the-badge" alt="PostgreSQL"/></td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/TypeScript-8957e5?style=for-the-badge" alt="TypeScript"/></td>
    <td><img src="https://img.shields.io/badge/React-8957e5?style=for-the-badge" alt="React"/></td>
    <td><img src="https://img.shields.io/badge/React%20Native-8957e5?style=for-the-badge" alt="React Native"/></td>
    <td><img src="https://img.shields.io/badge/Supabase-8957e5?style=for-the-badge" alt="Supabase"/></td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/AWS-8957e5?style=for-the-badge" alt="AWS"/></td>
    <td><img src="https://img.shields.io/badge/Docker-8957e5?style=for-the-badge" alt="Docker"/></td>
    <td><img src="https://img.shields.io/badge/GitHub%20Actions-8957e5?style=for-the-badge" alt="GitHub Actions"/></td>
  </tr>
</table>

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

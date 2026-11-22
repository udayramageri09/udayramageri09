# Uday Ramageri

Final-year Information Science student at BMS College of Engineering, Bangalore.
I build systems software and the tooling around it (hardware models in C++ and SystemC,
Linux diagnostics, CI pipelines that prove the code works) and full-stack web applications
with real databases, tests and honest documentation.

## Featured projects

### Systems

| Project | What it does | Built with |
|---|---|---|
| [**MiniSoC**](https://github.com/udayramageri09/minisoc) | A SystemC/TLM-2.0 virtual prototype of a small SoC. Firmware and Tcl tests run on modelled hardware (bus, UART, timer, interrupt controller) before silicon exists, with a parallel regression that buckets failures and sanitizer builds in CI. | C++17, SystemC, TLM-2.0, Tcl, Python, CMake, GitHub Actions |
| [**CloudPulse**](https://github.com/udayramageri09/cloud-pulse) | A dependency-free Linux and network diagnostics CLI. Reads host metrics straight from `/proc`, runs DNS, TCP, HTTP and TLS-expiry checks concurrently, and is tested end to end against a Docker failure lab. Published as a container image. | Python, Linux, Docker Compose, Nginx, pytest, GitHub Actions |

### Full-stack

| Project | Status | What it does | Built with |
|---|---|---|---|
| [**FinSphere**](https://github.com/udayramageri09/fin-sphere-major-project) | ![Completed](https://img.shields.io/badge/status-completed-brightgreen) | A student personal-finance web app (academic major project, faculty demo October 2026). Record or import transactions (including OCR from statement images), track goals, debts and investments, and get analysis: linear-regression forecasts, Isolation Forest anomaly detection and spending clustering in a private Python service. Session-cookie auth with owner-scoped queries, a local Account Aggregator simulator with synthetic data, and CI that runs lint, build and test suites against disposable PostgreSQL databases. | React, Vite, Tailwind, Express, PostgreSQL, FastAPI, scikit-learn, Tesseract, GitHub Actions |
| [**BiteCampus**](https://github.com/udayramageri09/bitecampus) | ![In progress](https://img.shields.io/badge/status-in%20progress-orange) | A hostel-mess platform designed for a controlled BMSCE pilot (~500 students). Hostellers are booked automatically each day; at the mess entrance a terminal shows a rotating QR that students scan in the app, and each meal coupon is redeemed exactly once, enforced by database constraints, transactions and idempotency keys. Specification and architecture are complete; implementation started November 2026. | TypeScript, React, Express, PostgreSQL, Prisma, Zod, Vitest |
| [**HireSync**](https://github.com/udayramageri09/hire-sync) | ![In progress](https://img.shields.io/badge/status-in%20progress-orange) | A campus placement tracker. The current prototype has a job feed with tier filters, a student profile form and an applications page, using asynchronous data loading over mock data; the backend and database are next. | HTML, CSS, JavaScript |

## Tools I work with

**Languages:** C++, C, Python, TypeScript, JavaScript, Tcl, Bash, SQL<br>
**Systems:** Linux (`/proc`, processes, signals), GDB, SystemC/TLM-2.0, TCP/IP, DNS, HTTP, TLS<br>
**Web:** React, Vite, Tailwind CSS, Node.js, Express, PostgreSQL, FastAPI<br>
**Build and CI:** Git, CMake, Docker, GitHub Actions, pytest, AddressSanitizer

## Beyond code

- Placement Coordinator for the ISE 2027 batch at BMSCE, elected by my class
- Vice Chairperson, BMSCE IEEE Student Branch (2025), and Bangalore Section Co-Lead for IEEEXtreme 19.0
- IEEE Bangalore Section Student Scholarship 2026 (one of 50 recipients across 125+ student branches)

## Find me

[LinkedIn](https://www.linkedin.com/in/udayramageri09/) · [LeetCode](https://leetcode.com/u/uday_ramageri09/) · udayramageriofficial09@gmail.com

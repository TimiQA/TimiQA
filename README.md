# Hi, I'm Artem Berestov 👋

QA Automation Engineer with 5+ years in commercial testing (API, UI, integration, mobile). I build Python-based automation frameworks, CI/CD pipelines, and — when it helps — the systems I test.

## 🛠 Tech Stack

- **Automation:** Python, Pytest, Playwright, Selenium, Requests
- **API Testing:** Postman, REST, JSON Schema validation, SQL
- **CI/CD & Infra:** GitHub Actions, Docker, Nginx, Linux/Bash, Git
- **Reporting:** Allure, JUnit XML

## 📁 Key Projects

### 🔹 [ipgis-qa-automation](https://github.com/TimiQA/ipgis-qa-automation)
Hybrid UI + API test framework for [IPGIS.cc](https://ipgis.cc) — a live IP intelligence & geolocation service I built and maintain myself.
- Stabilized UI tests against async React rendering using Playwright's smart-wait assertions instead of hardcoded sleeps
- Found and documented a backend validation bug (silent fallback instead of `400` on invalid input) — see `BUG_REPORT.md`
- Automated via GitHub Actions with Allure/JUnit reporting

### 🔹 Enterprise UI Test Infrastructure & Autonomous AI Diagnostics

A showcase of architecture patterns for stabilizing large-scale GUI automation in headless containerized environments, enhanced with LLM-assisted triage via Model Context Protocol (MCP).

* **Headless Display Orchestration:** Configured isolated Linux Docker runners using virtual framebuffers (Xvfb) and lightweight window managers, resolving modal window blocking and focus locks during unattended test runs.
* **Live Session Telemetry:** Integrated on-demand Web-VNC inspection proxies into CI pipelines, allowing engineers to visually monitor headless container execution during failure events.
* **AI Tooling & MCP Integration:** Designed agentic workflows connecting local LLMs with test execution environments via JSON-RPC protocols to automate failure analysis and configuration adjustments.
* **Robust Pipeline Triage:** Built custom Python triage utilities to parse multi-suite JUnit reports and process execution logs, preventing silent failure propagation in complex enterprise CI workflows.

*Note: Proprietary enterprise binaries and commercial ERP metadata have been abstracted into vendor-agnostic architecture patterns in this showcase.*

### 🔹 [nodus](https://github.com/TimiQA/nodus) ⭐ 18
Self-hosted deployment of a Matrix-based messenger — Docker, Nginx, TLS, TURN/NAT traversal for WebRTC, one-command provisioning on a bare Debian VPS.

### 🔹 [nodus_tests_playwright](https://github.com/TimiQA/nodus_tests_playwright)
UI test automation for the Nodus messenger, built on Page Object Model.
- Localization testing (Russian / English) via parametrized browser contexts
- Secrets isolated via `.env`, zero hardcoded credentials

---
📫 [LinkedIn](https://www.linkedin.com/in/temasb)

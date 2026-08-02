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

### 🔹 [nodus](https://github.com/TimiQA/nodus) ⭐ 18
Self-hosted deployment of a Matrix-based messenger — Docker, Nginx, TLS, TURN/NAT traversal for WebRTC, one-command provisioning on a bare Debian VPS.

### 🔹 [nodus_tests_playwright](https://github.com/TimiQA/nodus_tests_playwright)
UI test automation for the Nodus messenger, built on Page Object Model.
- Localization testing (Russian / English) via parametrized browser contexts
- Secrets isolated via `.env`, zero hardcoded credentials

---
📫 [LinkedIn](https://www.linkedin.com/in/temasb)

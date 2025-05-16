# egddy 🛡️

**egddy** is an open-source modular toolkit for SOC simulation, learning, and incident response — made for hackers, defenders, and learners alike.

Built with Python. Designed for speed. Easy to extend.

> **egddy** lets you simulate attacks, triage incidents, and stay notified — all from one place.

---

## ✨ Features (planned)

- [ ] 🔥 **Log Generator**
  - [ ] Offensive profiles (SSH brute, SQLi, ransomware)
  - [ ] Custom YAML-based templates
  - [ ] Emit logs in Syslog, JSONL, and CEF format
  - [ ] Real-time streaming via UDP or Kafka

- [ ] 🖥️ **Incident Triage Panel**
  - [ ] FastAPI + HTMX frontend
  - [ ] Live alert stream (Elastic/Wazuh integration)
  - [ ] Enrichment via GeoIP, AbuseIPDB, VirusTotal
  - [ ] Playbook viewer and response tagging

- [ ] 🤖 **Telegram Bot**
  - [ ] Push alerts with context
  - [ ] Inline triage buttons (FP / Escalate)
  - [ ] Mini App with incident summary and links

- [ ] 🐳 **Docker + Lab**
  - [ ] ELK or Wazuh stack integration
  - [ ] Preloaded dashboards
  - [ ] Seeded alerts from egddy-core

- [ ] 🧪 **Testing & CI**
  - [ ] `pytest` for each component
  - [ ] GitHub Actions (CI with flake8 and tests)
  - [ ] Demo screenshots, GIFs and asciinema recording

---

## 📦 Install & Setup

### Requirements

- Python 3.12+
- [uv](https://github.com/astral-sh/uv) (fast dependency manager)
- Docker (optional for full lab)

### Quickstart

```bash
git clone https://github.com/YOUR-USERNAME/egddy.git
cd egddy
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
```

# Chris Huber

**Lead Cybersecurity Coach** at [RapidAscent](https://www.rapidascent.com) | U.S. Air Force Veteran | AI + Security Builder

I train the next generation of cybersecurity professionals through hands-on apprenticeship programs that place graduates at Lockheed Martin, Boeing, BAE Systems, and 20+ defense and enterprise employers. Outside the classroom, I build production AI systems that solve real security problems.

Everything here runs on infrastructure I built and maintain — a multi-host cyber range on Proxmox with OPNsense, Wazuh SIEM, WireGuard, and a fleet of purpose-built VMs.

## Featured Projects

### [ThreatBrief](https://github.com/ChrisHuber1/threatbrief)
Autonomous SOC analyst — a 6-agent LangGraph pipeline that triages security alerts end-to-end. Multimodal ingestion (JSON, PDF, screenshots, audio), zero-shot classification, RAG over CVE/MITRE ATT&CK with pgvector, sentence-similarity dedup, Claude-powered triage reasoning, and executive briefing generation.

`LangGraph` `FastAPI` `pgvector` `HuggingFace Transformers` `Claude API` `Docker`

### [Trading Bot](https://github.com/ChrisHuber1/trading-bot)
Dual crypto trading system on Kraken. Bot1: rule-based MACD + StochRSI across 12 pairs. Bot3: ML-driven with XGBoost/CUDA, 40 dynamic pairs, champion-challenger retraining pipeline. Both run continuously with TimescaleDB for time-series storage and GPU-accelerated model training.

`Python` `XGBoost` `CUDA` `TimescaleDB` `PostgreSQL` `Kraken API`

### [Claude Project Manager](https://github.com/ChrisHuber1/claude-project-manager)
AI agent that autonomously manages 12+ projects across a multi-host cyber range. Feature branches, safety guardrails, human-in-the-loop triggers, credential isolation, Obsidian knowledge base integration, and a dead-drop relay for multi-machine coordination.

`Claude API` `Python` `SSH` `Obsidian` `Proxmox`

### [SIEM Automation](https://github.com/ChrisHuber1/siem-automation)
Built after my SIEM went down for 3 days and nobody noticed. Wazuh watchdog with health monitoring, AI-powered alert triage, CVE validation against NVD, and push notifications via ntfy. Runs as a systemd service with automatic recovery.

`Python` `Wazuh` `Claude API` `ntfy` `systemd`

### [Network Security Audit](https://github.com/ChrisHuber1/network-security-audit)
Complete security assessment methodology: 17 evidence artifacts, CIS-benchmarked SSH auditing, findings with risk ratings, remediation tracking, and handoff documentation. Built from a real audit of a production network.

`Bash` `CIS Benchmarks` `SSH` `OPNsense`

## Tech Stack

**Languages:** Python, Bash, KQL, SQL
**AI/ML:** LangGraph, Claude API, XGBoost, HuggingFace Transformers, sentence-transformers, RAG, pgvector
**Security:** Wazuh, Microsoft Sentinel, Defender XDR, OPNsense, WireGuard, CIS Benchmarks
**Infrastructure:** Proxmox, Docker, systemd, nginx, PostgreSQL, TimescaleDB, FastAPI
**Platforms:** Microsoft E5 Security Stack, Entra ID, Intune, Kraken API

## Education & Certifications

- **M.Eng. Applied Data Science** — Stevens Institute of Technology *(in progress)*
- **B.S. Computer Programming** — Southwestern College
- **Certificate in Cybersecurity** — City University
- **CompTIA Security+**

## What I'm Working On

- Completing Microsoft security operations training across 9 domains (Sentinel, Defender, Entra, Intune, Purview, Exchange, SharePoint, Teams, Copilot)
- Building [GhostWriter](https://github.com/ChrisHuber1) — an AI compliance document generator that produces full SOC 2 policy bundles
- Pursuing the Stevens MEng to formalize the bridge between cybersecurity and applied data science

---

*I build things that work. If it's in a repo, it runs on real infrastructure solving a real problem.*

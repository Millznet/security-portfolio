# Security Portfolio — Elliot Millet

I build defensive security tooling and run hands-on labs focused on **detection workflows, incident-ready documentation, and integrity-minded systems**.

This repository serves as the **public front door** for my work:

* Public repos and lab artifacts (repro steps, diagrams, writeups)
* Redacted snapshots of commercial implementations (kept private)

**LinkedIn:** [https://www.linkedin.com/in/elliotmillet-tech/](https://www.linkedin.com/in/elliotmillet-tech/)

---

## Highlights (Public)

### gpt_cli_memengine — Repo-Scale AI Workflow Tooling (Rust)

Local CLI for persistent AI memory and structured context injection across large projects.

* [https://github.com/Millznet/gpt_cli_memengine](https://github.com/Millznet/gpt_cli_memengine)

---

### ZK-ACK (Phase 0) — Public Proof Snapshot

Minimal, runnable proof-of-concept for verifiable "certified notices" over standard email workflows.

Demonstrates:

* Signed message generation

* Tamper detection

* Verification API

* [https://github.com/Millznet/zkack-demo-phase0](https://github.com/Millznet/zkack-demo-phase0)

---

### Value Refinery — Data + Automation Pipeline

Tooling for structured processing, transformation, and reporting pipelines.

* [https://github.com/Millznet/value_refinery](https://github.com/Millznet/value_refinery)

---

## SIEM Lab Portfolio (Wazuh) — SOC-Ready Artifacts

This section documents a job-focused lab environment built to generate **2–3 undeniable SOC-ready artifacts**:

* Deploy and operate a SIEM
* Enroll endpoints and validate telemetry ingestion
* Generate detections and perform basic triage
* Produce clean incident writeups (screenshots + evidence + timeline)

### Current Lab Build

* **SIEM Host:** HP Z420 (`z420-2`) — Ubuntu Server 24.04, Docker Compose, Wazuh single-node
* **Dashboard:** `https://192.168.1.227/`
* **Endpoint:** Fedora dev rig (Wazuh agent, name `fedora-devrig`)

### Planned Deliverables

* **Artifact A — Wazuh Deployment README** (architecture + repro + troubleshooting + validation screenshots)
* **Artifact B — Detection + Triage Mini‑Incident (IR‑001)** (1–2 page report with screenshots + timeline)
* **Artifact C — File Integrity Monitoring (FIM) Change Detection** (short writeup + screenshots)

> Goal: demonstrate day‑1 SOC workflow competence — not build a forever-production homelab.

---

## Private (Commercial) Work — High-Level Only

These repos remain private while iterating toward a paid service offering:

* **RobotSec** — endpoint telemetry + evidence-style reporting (EDR-lite / reporting wedge)
* **Aurora Suite** — fleet security concepts: trust, control plane, update/rollback, baseline drift, edge gateway

---

## Focus Areas

Blue Team • Detection Engineering • SIEM workflows • Linux • Rust/Python • Incident documentation • Integrity/Drift monitoring

---

## Contact

* LinkedIn: [https://www.linkedin.com/in/elliotmillet-tech/](https://www.linkedin.com/in/elliotmillet-tech/)
* GitHub: [https://github.com/Millznet](https://github.com/Millznet)

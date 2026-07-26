#Project 10 — Attacker and Defender
---

This repository contains my work for Project 10 in System Administration and Maintenance. The project simulates a multi‑stage attack against the ministry and the defensive workflow used to detect and triage it.

##Contents
---

**attack/scenario.txt**: Full attacker kill chain, including the auth.log intrusion and an indirect prompt injection (LLM01).

**attack/lure.txt**: Phishing lure generated in my local sandbox (Ollama + Llama 3), with prompt and plausibility note.

**defender/detect.py** : Extended detector with two new rules (impossible travel + bulk donor‑table read).

**defender/triage_with_ai.txt**: Local AI triage output and grading against deterministic rules.

**REPORT.docx**: Final reflection and honest AI usage statement.

**agent-log.txt**: Log of local sandbox model usage.

##Running the Detector
-

***python3 defender/detect.py code/auth.log***

##Summary
---

This project shows how an attacker chains multiple steps together and how rule‑based detection identifies the full intrusion. It also compares deterministic detection with AI‑assisted triage and highlights the risks of indirect prompt injection (LLM01) in RAG systems.

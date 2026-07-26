# Project 10 — Attacker and Defender

This repository contains my work for Project 10 in System Administration and Maintenance.  
The project simulates a realistic security incident and the corresponding defensive analysis.

## Contents

- **attack/scenario.txt** — Attacker kill chain describing reconnaissance, phishing, credential theft, privilege escalation, lateral movement, data harvesting, and exfiltration.
- **attack/lure.txt** — Phishing-style email used in the scenario.
- **defender/detect.py** — Rule-based detection script for suspicious authentication activity.
- **defender/triage_with_ai.txt** — AI-assisted triage summary and comparison with deterministic rules.
- **THREATMAP.txt** — Mapping attacker actions to defender signals.
- **REPORT.txt** — Final reflection on attacker behavior, detection accuracy, and AI limitations.
- **agent-log.txt** — Documentation of limited AI assistance used during the project.

## Running the Detector

From the project root:
python3 defender/detect.py code/auth.log


This prints all flagged events and a summary of findings.

## Summary

The project demonstrates how an attacker chains multiple steps together and how rule-based detection identifies suspicious behavior. It also evaluates the usefulness and limitations of AI-assisted triage compared to deterministic detection logic.



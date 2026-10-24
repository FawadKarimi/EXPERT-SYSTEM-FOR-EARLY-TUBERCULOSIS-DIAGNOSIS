# Expert System for Early Tuberculosis Diagnosis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

[![HTML5](https://img.shields.io/badge/UI-HTML%2FCSS%2FJS-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Prolog](https://img.shields.io/badge/Rules-Prolog-000000?style=flat-square)](TUBERCULOSIS.pl)
[![Education](https://img.shields.io/badge/Purpose-Educational%20Prototype-0369a1?style=flat-square)](#disclaimer)

An **educational expert-system** project for **early tuberculosis (TB) screening guidance**, combining a **Prolog rule base** with a polished **browser-based interface**. The GUI walks users through symptom and risk-factor questions and presents rule-derived conclusions with severity styling.

> **Not a medical device.** This project demonstrates **knowledge representation and rule-based inference** for learning purposes only. It does **not** replace laboratory testing, imaging, or clinician judgment.

## What's inside

| File | Role |
| --- | --- |
| `TUBERCULOSIS.pl` | Prolog knowledge base & inference rules |
| `tb_expert_gui.html` | Standalone web UI (open locally in a browser) |
| `EXPERT SYSTEM FOR EARLY TUBERCULOSIS DIAGNOSIS.pdf` | Written report / documentation |
| `banner.jpg` | UI branding asset |

## Run the web interface

No build step required:

```bash
git clone https://github.com/FawadKarimi/EXPERT-SYSTEM-FOR-EARLY-TUBERCULOSIS-DIAGNOSIS.git
cd EXPERT-SYSTEM-FOR-EARLY-TUBERCULOSIS-DIAGNOSIS
# macOS / Linux
xdg-open tb_expert_gui.html 2>/dev/null || open tb_expert_gui.html
```

Or drag **`tb_expert_gui.html`** into Chrome / Firefox / Edge.

The interface uses a medical-inspired design system (accessible contrast, severity colors, responsive layout) suitable for classroom demos.

## Prolog engine

To experiment with the rule base directly, use SWI-Prolog or GNU Prolog:

```bash
swipl TUBERCULOSIS.pl
```

Consult the PDF report for **predicate definitions**, example queries, and the clinical reasoning narrative used in the course project.

## Learning goals

- Encode **symptom → hypothesis** rules with uncertainty / severity bands  
- Separate **knowledge base** (`.pl`) from **presentation** (HTML UI)  
- Discuss **limitations** of rule-based triage vs. gold-standard TB diagnostics  

## Disclaimer

**For education only.** If you suspect TB or any serious illness, seek **qualified healthcare** immediately. Do not use this software for real patient triage.

## Author

**Mohammad Fawad Karimi**  
📧 [mfkarimi@mhs.usk.ac.id](mailto:mfkarimi@mhs.usk.ac.id) · 🌐 [Portfolio](https://fawadkarimi.github.io/)

# Sungil Hwang (황성일 · 黃聖壹)

**Radiologist · Professor**, Department of Radiology, Seoul National University Bundang Hospital (SNUBH) <br>
**Secretary General**, Korean Society of Radiology (KSR) <br>
**President**, SNUBH Vibe Lab for Established Clinicians

Building practical, physician-made tools at the intersection of **medical imaging, AI, and clinical workflow**.

🔗 ORCID: [0000-0001-7516-5369](https://orcid.org/0000-0001-7516-5369) · 🏥 Seoul National University Bundang Hospital, Seongnam, Korea

**Try them live:** [Abstract Searcher](https://abstract-searcher.vercel.app) · [Researcher KG](https://hwangsi.github.io/researcher-kg/) · [Cancer Registry Dashboard](https://hwangsi.github.io/CRO_lecture/)

---

## 🩻 Radiology & Imaging Tools

| Repo | Stack | What it does |
|------|-------|--------------|
| [**dicom-viewer**](https://github.com/hwangsi/dicom-viewer) | Python · PyQt6 · pydicom | Desktop DICOM viewer for reading and lecture prep — multi-panel layouts, window width/level (WW/WL) control, DICOM tag overlay, screenshot/clipboard copy, and a series sidebar with fast header-only loading. |
| [**PIRADSreport**](https://github.com/hwangsi/PIRADSreport) | Single-file HTML | **PI-RADS v2.1** structured reporting for prostate MRI — 38-sector map (base/mid/apex SVG panels, zone color coding), real-time volume & PSAD from the ellipsoid formula, automatic index-lesion selection, and one-click report output in hospital format. No server, no install. |
| [**ProstateMRICalculator**](https://github.com/hwangsi/ProstateMRICalculator) | Kotlin · ML Kit | Android app that estimates prostate volume from MRI screenshots — OCR reads the measurements and the ellipsoid formula computes volume (mL). |
| [**adrenalMRCalc**](https://github.com/hwangsi/adrenalMRCalc) | HTML | Adrenal mass washout calculator — absolute & relative washout for characterizing adrenal lesions. |
| [**PACSFollowup**](https://github.com/hwangsi/PACSFollowup) | Kotlin · ML Kit | Tracks follow-up imaging patients — OCR (Korean + English), speech dictation, and Google Sheets sync, tuned for urogenital imaging terms. |

## 🤖 Research & Workflow Automation

| Repo | Stack | What it does |
|------|-------|--------------|
| [**Abstract-searchme**](https://github.com/hwangsi/Abstract-searchme) | Python · PySide6 · Web | Conference program searcher — find your own sessions in a program-book PDF by name or affiliation, then export to `.ics` or get web-push reminders before each session. Dedicated KCR / ICR / GBCC parsers with an AI-assisted fallback; desktop GUI, CLI, and a hosted version at [abstract-searcher.vercel.app](https://abstract-searcher.vercel.app). |
| [**researcher-kg**](https://github.com/hwangsi/researcher-kg) | HTML · D3 · Three.js | Visualizes one researcher's publication career from **OpenAlex / ORCID / PubMed** — bubble and 3D timelines (year × journal IF × citations), D3 force-directed co-author network, topic streamgraph, and JCR impact-factor table. Handles author disambiguation and multi-ID merging. No build step, no backend, no API keys. [**Live**](https://hwangsi.github.io/researcher-kg/) |
| [**hospital-agent**](https://github.com/hwangsi/hospital-agent) | Python · FastAPI | Prototype appointment agent across Korea's five major hospitals — per-hospital crawlers plus HIRA open data, PubMed (H-index), KCI, and Naver News integrations, with KCD code mapping. |
| [**KSRSapprover**](https://github.com/hwangsi/KSRSapprover) | Python · FastAPI | Automates KSR administrative approval workflows — Gmail API intake with Telegram bot notifications. |
| [**email-agent**](https://github.com/hwangsi/email-agent) | Python · Claude API | Email management agent running as a macOS LaunchAgent — twice-daily Gmail fetch, Claude-based classification, and push notifications to iPhone via ntfy. |

## 🏥 Society & Public Health

| Repo | Stack | What it does |
|------|-------|--------------|
| [**ksr_repeat_imaging**](https://github.com/hwangsi/ksr_repeat_imaging) | HTML · CSS · JS | Public-facing site for the Korean Society of Radiology's campaign against **duplicate and repeat imaging** — 2025 statistics, research history, reason codes, a downloadable resource library, and policy proposals. Build-free static site, edited directly on GitHub and auto-deployed. |
| [**CRO_lecture**](https://github.com/hwangsi/CRO_lecture) | HTML · Chart.js | Offline dashboard visualizing Korea's national cancer registry (KOSIS) — KPI cards, Top-15 incidence ranking, 1999–2023 trends, sex breakdown, and CSV export, styled in a BMW M design system. [**Live**](https://hwangsi.github.io/CRO_lecture/) |

---

> ⚙️ Forked repositories and organization projects are intentionally excluded — these are my own projects.

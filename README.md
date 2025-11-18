# Project 11 of 21 — Framework Mapping
## Operation Control Mirror — NIST CSF 2.0 Edition

Lab project mapping SOC detections in Splunk to **NIST CSF 2.0** and **MITRE ATT&CK** for Roe’s Rec Systems.

> “Every control framework is a mirror — not to see compliance, but to reflect how strong your detections truly are.”

---

## 🎯 Mission Objective

Take a set of real(istic) SOC detections and:

- Map each one to:
  - **NIST CSF 2.0 Function → Category → Subcategory**
  - **MITRE ATT&CK Tactic/Technique**
- Capture everything in a **single mapping sheet**.
- Write an analyst-style walkthrough explaining how the sheet was filled out.

This project shows recruiters:
- I understand frameworks (NIST CSF, MITRE).
- I can connect **SIEM detections** to **governance & risk** language.
- I can document work like an analyst, not just run queries.

---

## 🧪 Lab Environment

- **SIEM:** Splunk Enterprise
- **Data Sources:** Windows Event Logs, Sysmon, AD / Identity logs
- **Frameworks:** 
  - NIST CSF 2.0
  - MITRE ATT&CK (Enterprise)

---

## 📁 Repo Structure

Planned structure for this repo:

- `docs/`
  - `Project11_Operation_Control_Mirror_NIST_CSF_Case_Study.md`  
  - `Project11_Operation_Control_Mirror_NIST_CSF_Case_Study.pdf`
- `mapping/`
  - `nist_csf_mapping_sheet.xlsx`  
  - `nist_csf_mapping_sheet.csv`
- `detections/`
  - `splunk_detections_spl.txt` (all SPL searches used)
- `screenshots/`
  - `splunk_group/` – screenshots for the **Splunk columns** (Detection_Name, SPL_Search, Index, Data_Source)
  - `nist_csf_group/` – screenshots for the **NIST CSF columns** (Function, Category, Subcategory_ID, Subcategory_Name)
  - `mitre_group/` – screenshots for the **MITRE columns** (MITRE_Tactic, MITRE_Technique, Coverage_Level)

You don’t need all of these on day one — you can upload them as you go.

---

## 🧠 Analyst Mindset (How I Filled the Sheet)

In the write-up (see `docs/`):

- I started with the **Splunk group** of columns:
  - `Detection_Name`, `SPL_Search`, `Index`, `Data_Source`
- Then mapped each row into the **NIST CSF group**:
  - `Function`, `Category`, `Subcategory_ID`, `Subcategory_Name`
- Finally, I aligned each detection with the **MITRE group**:
  - `MITRE_Tactic`, `MITRE_Technique`, `Coverage_Level`

This repo gives the screenshots and mapping sheet that back up that story.

---

## ✅ Deliverables in This Project

- [ ] Completed NIST CSF 2.0 mapping sheet (`mapping/`)
- [ ] Splunk detections and SPL (`detections/`)
- [ ] Screenshots for Splunk / NIST / MITRE groups (`screenshots/`)
- [ ] Case-study style write-up for recruiters and hiring managers (`docs/`)

Status: **Completed** (update date when everything is uploaded).

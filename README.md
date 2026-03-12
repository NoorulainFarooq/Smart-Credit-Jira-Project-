# 🏧 Smart Credit Kiosk — Jira Project Management

> **Final Year Project (FYP)** | Agile Scrum | Jira Software  
> Project Key: `SCRUM` | Board: My Scrum Space

---

## 📌 Project Overview

The **Smart Credit Kiosk** is a Final Year Project that combines hardware biometrics, a bilingual UI, and an ML-based credit scoring system. This repository documents how the project is managed using **Jira Software** with Agile Scrum methodology.

Jira acts as the central hub — breaking down complex features into Epics, User Stories, and Sub-tasks, assigning them to team members, and tracking real-time progress toward FYP deadlines.

---

## 🗂️ Project Structure — Epics

The project is divided into **3 main Epics**:

| Epic | Key | Description |
|------|-----|-------------|
| 🔧 Hardware & Biometrics | `SCRUM-1` | R307 Fingerprint Scanner, Thermal Printer, physical kiosk setup |
| 🖥️ Bilingual UI | `SCRUM-5` | Urdu & English React interface, Financial Questionnaire, Credit Score Screen |
| 🤖 AI & Data | `SCRUM-9` | ML Model Development, Credit Score Logic, Prediction Mapping |

---

## 📋 Backlog — User Stories

| ID | Story | Epic | Priority | Status |
|----|-------|------|----------|--------|
| SCRUM-2 | Implement R307 Fingerprint Scanner Driver and Connectivity | Hardware | High | In Progress |
| SCRUM-4 | Configure Thermal Printer for PDF Receipt Output | Hardware | Medium | To Do |
| SCRUM-7 | Build Dynamic 12-Question Financial Questionnaire (React) | Bilingual UI | High | To Do |
| SCRUM-8 | Develop Credit Score Breakdown Screen with Explainable AI | Bilingual UI | High | To Do |
| SCRUM-11 | Implement Logic for Mapping ML Predictions to 300–850 Score | AI & Data | Critical | To Do |
| SCRUM-12 | ML Accuracy Testing & Validation | AI & Data | High | To Do |

---

## 🏃 Sprint Overview

### Sprint 1 — `std_32581` (Active)
**Goal:** Get core ML model and fingerprint integration moving

| Assignee | Tasks | Status |
|----------|-------|--------|
| NP | SCRUM-11 — ML Prediction Mapping (due Mar 1, 2026) | To Do |

### Backlog Sprint — `std_32677`
| Task | Status |
|------|--------|
| SCRUM-2 — Fingerprint Scanner Driver | In Progress |

---

## 📅 Timeline

| Epic | January | February |
|------|---------|----------|
| Hardware & Biometrics | SCRUM Sprint 1 ✅ | — |
| Bilingual UI | — | Active 🟡 |
| AI & Data | Planned | Planned |

> Timeline view available at the Jira board link below.

---

## 👥 Team

| Member | Role |
|--------|------|
| Noorulain Farooq | Project Lead / Jira Admin |
| Team Member S | Developer |
| Team Member S | Developer |
| Team Member S | QA / Testing |

---

## 🔗 Jira Board Link

🔗 [View Live Jira Board](https://noorulainfarooq06.atlassian.net/jira/software/projects/SCRUM/boards/1/timeline)

> Access requires an invitation to **My Scrum Space**. Contact the project lead to request access.

---

## ⚙️ How We Use Jira

### Board Views
- **Board View** — Kanban-style columns: `To Do` → `In Progress` → `Done`
- **Backlog View** — Prioritized list of all upcoming stories per epic
- **Timeline View** — Gantt-style view showing epic durations across Jan–Feb
- **Group: Assignee** — Filter board by team member to monitor individual workloads

### Workflow
```
Create Epic → Break into User Stories → Add Sub-tasks
     → Assign to Team Member → Move into Sprint
          → To Do → In Progress → In Review → Done
```

### Priority Levels Used
| Priority | When Used |
|----------|-----------|
| 🔴 Critical | Blockers — must be done before anything else |
| 🟠 High | Core features required for FYP submission |
| 🟡 Medium | Important but not blocking other tasks |
| 🟢 Low | Nice-to-have or post-submission improvements |

---

## 📊 Progress Tracking

- **Sprint Burndown** — tracked per sprint to monitor velocity
- **Group: Assignee** view used in standups to see who is blocked
- Stories marked **Done** only after all sub-tasks are verified
- Critical path item: **SCRUM-11** (ML Prediction Mapping) must complete before credit score UI can be finalized

---

## 📝 Notes

- Project board shared via Jira invitation email (see screenshot in project docs)
- All sprint dates align with FYP submission milestones
- ML model accuracy (SCRUM-12) is a dependency for SCRUM-8 (Credit Score Screen)

---

*Managed with ❤️ using Jira Software — Agile Scrum*

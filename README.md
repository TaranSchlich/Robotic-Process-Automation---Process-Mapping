# Robotic Process Automation – Process Mining

**Course:** GB 745 – Robotic Process Automation & Process Mining | UW–Madison, School of Business  
**Assignment:** Process Mapping – Customer Onboarding Analysis

---

## Overview

Analyzed the new customer onboarding process for **CloudDraft**, a fictional SaaS project-management company experiencing high 30-day churn. Using multi-source process discovery (support logs, Zoom transcripts, email records, Slack exports, and customer feedback), constructed a **swim lane process map** in Lucidchart and produced a stakeholder-ready presentation identifying bottlenecks, pain points, and competitive gaps.

---

## Process Map

The swim lane map covers four actor lanes across the full onboarding journey:

| Lane | Actor |
|---|---|
| 1 | Customer Admin (New User) |
| 2 | CloudDraft Success / Onboarding |
| 3 | CloudDraft Support |
| 4 | Customer IT (incl. Salesforce Admin) |

**Key process stages:**
1. Email verification
2. CSV data import (Standard: self-serve ≤60 rows; Enterprise: script-assisted)
3. Slack integration (token/IT approval path)
4. Salesforce OAuth connection (OAuth + write-access authorization)
5. Integration confirmation & end state

---

## Process Goals

- Reduce 30-day churn by improving onboarding clarity and reducing friction
- Ensure users successfully verify email, invite their team, import data, and connect integrations
- Provide differentiated onboarding paths for Standard vs. Enterprise customers

---

## Pain Points Identified

| # | Pain Point | Source |
|---|---|---|
| 1 | 42% drop-off at team invitation step due to Slack export friction | Slack Export |
| 2 | Hidden "Skip for now" link causing silent abandonment | UX observation |
| 3 | CSV importer crashes on files exceeding 100 rows | Support Chat Log |
| 4 | Salesforce OAuth requires IT involvement, causing multi-day delays | Zoom Transcript |
| 5 | Blank workspace overwhelms Standard-tier users at first login | Zoom Transcript, Customer Survey |

---

## Competitive Differences

| Gap | Competitor Approach |
|---|---|
| No starter templates | Basecamp and similar tools pre-populate workspaces |
| CSV row limit | Competitors handle large imports without manual intervention |
| Hidden skip option | Competitors surface optional steps more prominently |
| Integration IT bottleneck | Competitors streamline OAuth without admin involvement |

---

## Recommendations

1. Increase visibility of "Skip for now" to reduce abandonment
2. Fix CSV uploader row limit or auto-detect file size and redirect to assisted import
3. Pre-configure starter templates for all subscription tiers
4. Add Salesforce OAuth pre-check to surface IT requirements before the user attempts connection

---

## Deliverables

| File | Description |
|---|---|
| `GB745_Process_Map_Schlichtmann.pdf` | Swim lane process map (Lucidchart export) |
| `GB745_Onboarding_Process_Map_Presentation_Schlichtmann.pdf` | Stakeholder presentation (goals, map, pain points, industry comparison) |
| `process-files/` | Source materials used for process discovery |

### Source Materials

| File | Type |
|---|---|
| `Email - New User Signup.pdf` | Welcome email flow |
| `Email - Slack Integration.pdf` | Integration prompt email |
| `Slack Export.docx` | Slack workspace export data |
| `Support Chat Log.docx` | Customer support interaction log |
| `Zoom Transcript - Onboarding Kickoff.docx` | Enterprise kickoff call transcript |
| `Customer Feedback Survey.docx` | Post-onboarding survey responses |
| `Handwritten Note.png` | Analyst field notes |

---

## Tools & Skills

`Lucidchart` &nbsp;`Swim Lane Process Mapping` &nbsp;`Process Mining` &nbsp;`Business Process Analysis` &nbsp;`SaaS Onboarding` &nbsp;`Stakeholder Communication` &nbsp;`Root Cause Analysis`

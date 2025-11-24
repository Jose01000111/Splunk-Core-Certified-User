# 🔍 Splunk Core Certified User – Study & Labbing Repo

Welcome to my **Splunk Core Certified User Study Repository**.  
This repo holds **my personal notes, summaries, and lab references** for every Splunk exam objective.  
Everything here is structured, concise, and focused on the exact skills tested on the exam.

**My study advice (to myself):**
- Learn by *doing* — search, refine, visualize, repeat.
- Keep searches simple before making them complex.
- Remember Splunk is workflows: search → transform → report → dashboard.
- Stay consistent and practice using *real data* when possible.

---

# 📚 Exam Objectives Overview  
Each row includes:  
**Notes → Description → Labbing (if applicable)**  
**All links are placeholders and will point to the correct GitHub repos once created.**

---

## **1.0 Splunk Basics (5%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**Splunk Components**](#splunk-components) | Indexers, search heads, forwarders, deployment server. | — |
| [**Uses of Splunk**](#uses-of-splunk) | Logs, metrics, security, monitoring, dashboards. | — |
| [**Splunk Apps**](#splunk-apps) | Packaged knowledge objects (searches, dashboards, inputs). | — |
| [**User Settings & Navigation**](#user-settings--navigation) | Time range picker, search bar, apps menu, jobs. | — |

---

## **2.0 Basic Searching (22%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**Run Basic Searches**](#run-basic-searches) | Keywords, field=value, boolean logic. | Lab |
| [**Set Time Range**](#set-time-range) | Presets, real-time, custom ranges. | Lab |
| [**Identify Search Results**](#identify-search-results) | Events, fields, patterns, metadata. | Lab |
| [**Refine Searches**](#refine-searches) | OR, NOT, wildcards, field filtering. | Lab |
| [**Use the Timeline**](#use-the-timeline) | Event peaks, correlations. | — |
| [**Work With Events**](#work-with-events) | Expand, collapse, field discovery. | Lab |
| [**Control Search Job**](#control-search-job) | Pause, stop, inspect. | — |
| [**Save Search Results**](#save-search-results) | Save as: search, report, dashboard panel. | Lab |

---

## **3.0 Using Fields in Searches (1%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**Understand Fields**](#understand-fields) | Indexed vs extracted fields. | — |
| [**Use Fields in Searches**](#use-fields-in-searches) | field=value, field!=value. | Lab |
| [**Fields Sidebar**](#fields-sidebar) | Auto-discovered fields. | — |

---

## **4.0 Search Language Fundamentals (20%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**Basic Search Commands**](#basic-search-commands) | table, rename, fields, dedup, sort. | Lab |
| [**Search Pipeline**](#search-pipeline) | term → command → output. | Lab |
| [**Specify Indexes**](#specify-indexes) | `index=main`, `index=*`. | — |
| [**General Search Practices**](#general-search-practices) | Fast, smart, verbose modes. | Lab |

---

## **5.0 Basic Transforming Commands (15%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**top Command**](#top-command) | Most frequent values. | Lab |
| [**rare Command**](#rare-command) | Least frequent values. | Lab |
| [**stats Command**](#stats-command) | count, sum, avg, values. | Lab |

---

## **6.0 Reports & Dashboards (12%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**Save Search as Report**](#save-search-as-report) | Convert a search → report. | Lab |
| [**Edit Reports**](#edit-reports) | Formatting, time range, permissions. | Lab |
| [**Statistical Reports**](#statistical-reports) | Tables via transforming commands. | Lab |
| [**Charts & Visualizations**](#charts--visualizations) | Line, bar, pie, area visualizations. | Lab |
| [**Create a Dashboard**](#create-a-dashboard) | Panels, layouts, inputs/forms. | Lab |
| [**Add Report to Dashboard**](#add-report-to-dashboard) | Linking saved reports. | Lab |
| [**Edit Dashboards**](#edit-dashboards) | Modify visualizations and inputs. | Lab |

---

## **7.0 Lookups (6%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**Describe Lookups**](#describe-lookups) | CSV/file-based enrichments. | — |
| [**Examine a Lookup File**](#examine-a-lookup-file) | Field structure: key → values. | Lab |
| [**Create Lookup + Definition**](#create-lookup--definition) | Add file → create definition. | Lab |
| [**Configure Automatic Lookup**](#configure-automatic-lookup) | Auto-enrichment on search. | Lab |
| [**Use Lookups in Search**](#use-lookups-in-search) | `lookup`, `inputlookup`. | Lab |

---

## **8.0 Scheduled Reports & Alerts (5%)**

| Objective | Description | Labbing |
|----------|-------------|---------|
| [**Scheduled Reports**](#scheduled-reports) | Reports that run automatically. | Lab |
| [**Configure Scheduled Reports**](#configure-scheduled-reports) | Cron, time, permissions. | Lab |
| [**Describe Alerts**](#describe-alerts) | Threshold-based firing. | — |
| [**Create Alerts**](#create-alerts) | Scheduled or real-time. | Lab |
| [**View Fired Alerts**](#view-fired-alerts) | Alert logs and GUI history. | — |

---

---

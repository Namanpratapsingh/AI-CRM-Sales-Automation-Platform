# n8n Workflow JSON Files

This folder contains the exported n8n workflow JSON files for the **AI CRM & Sales Automation Platform**.

These JSON files contain the workflow configurations, nodes, connections, expressions, and automation logic used to implement the project's CRM and sales automation pipeline.

## Workflows

### 01 — Lead Registration & Collection

Collects new lead information, prepares the submitted data, generates a unique Lead ID, stores the lead in the CRM, and performs the initial lead-processing actions.

**File:**
`01 - Lead Registration & Collection.json`

---

### 02 — AI Lead Scoring

Uses AI to analyse the lead information and generate an AI-based lead score and lead category.

The qualification result is used by the downstream sales automation workflows.

**File:**
`02 - AI Lead Scoring.json`

---

### 03 — Automated Lead Follow-Up

Handles automated follow-up actions for leads based on their current CRM state and configured follow-up conditions.

**File:**
`03 - Automated Lead Follow-Up.json`

---

### 04 — Lead Activity Monitoring

Monitors lead activity and checks whether leads require further attention or follow-up based on the information stored in the CRM.

**File:**
`04 - Lead Activity Monitoring.json`

---

### 05 — Lead Status Management

Manages the lead's sales status and routes the lead according to its current qualification and sales state.

**File:**
`05 - Lead Status Management.json`

---

### 06 — Sales Performance Report

Generates a weekly sales performance report using the CRM data and sends the report to the sales department.

**File:**
`06 - Sales Performance Report.json`

---

## Workflow Pipeline

The overall lead-management process is:

```text
Lead Registration
       ↓
AI Lead Scoring
       ↓
Automated Lead Follow-Up
       ↓
Lead Activity Monitoring
       ↓
Lead Status Management
       ↓
Weekly Sales Performance Report

# AI CRM & Sales Automation Platform

An AI-powered CRM and sales automation platform built using n8n, Google Sheets, Gmail, and AI-based lead scoring and automation.

## Project Overview

The platform automates the complete lead management lifecycle, from lead registration and AI-based scoring to follow-ups, activity monitoring, status management, and sales performance reporting.

## Key Features

- Lead registration and data collection
- Automated lead ID generation
- AI-based lead scoring
- Lead categorization into Cold, Warm, and Hot
- Automated email follow-ups
- Lead activity monitoring
- Lead status management
- Sales performance reporting
- Google Sheets-based CRM database
- Gmail integration
- Scheduled automation
- Master/sub-workflow demonstration

## Workflow Architecture

The project consists of six major workflows:

### 01 — Lead Registration & Collection

Collects lead information through a form, prepares the submitted data, generates a unique Lead ID, stores the lead in Google Sheets, and sends a confirmation email.

### 02 — AI Lead Scoring

Analyzes lead information and assigns an AI score to determine the potential value of the lead.

### 03 — Automated Lead Follow-Up

Checks lead follow-up conditions and automatically sends follow-up emails when the configured conditions are satisfied.

### 04 — Lead Activity Monitoring

Monitors lead activity and identifies leads that require attention based on their activity and follow-up information.

### 05 — Lead Status Management

Updates and manages lead statuses based on their current sales stage and interaction history.

### 06 — Sales Performance Report

Generates a sales performance report from the CRM data and sends the report to the sales department.

## Technology Stack

- n8n
- Google Sheets
- Gmail
- AI / LLM
- Google Forms
- JavaScript expressions
- GitHub

## Repository Structure

```text
AI-CRM-Sales-Automation-Platform/
│
├── 01 - Lead Registration & Collection.json
├── 02 - AI Lead Scoring.json
├── 03 - Automated Lead Follow-Up.json
├── 04 - Lead Activity Monitoring.json
├── 05 - Lead Status Management.json
├── 06 - Sales Performance Report.json
│
├── screenshots/
│   ├── 01-lead-registration.png
│   ├── 02-ai-lead-scoring.png
│   ├── 03-automated-follow-up.png
│   ├── 04-lead-activity-monitoring.png
│   ├── 05-lead-status-management.png
│   ├── 06-sales-performance-report.png
│   ├── 07-master-workflow.png
│   ├── 08-crm-google-sheet.png
│   └── 09-email-output.png
│
├── architecture/
├── documentation/
└── README.md

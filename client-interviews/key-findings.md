# Consolidated Key Findings

**Date Compiled:** May 24, 2026
**Sources:** Client Interview #01, Client Interview #02, System Analysis, Client Request Email

## 1. Core Problem Statement
KTD Lanka's reliance on manual Microsoft Excel spreadsheets and paper-based invoicing results in duplicated data, delayed decision-making, and reactive stock management[cite: 2, 4]. A unified, automated system is required to replace these disconnected workflows.

## 2. Primary Functional Needs
Through our fact-finding sessions, the following advanced features were identified as necessary to solve the client's bottlenecks:
* **Automated Low-Stock Alerts:** The system must proactively notify inventory staff via Email and SMS when stock drops below thresholds to prevent lost sales[cite: 3].
* **AI OCR Invoice Extraction:** To eliminate manual data entry, the system must process uploaded invoice images using OCR to automatically update inventory levels.
* **Real-Time GPS Tracking:** Management requires visibility into field operations, necessitating native GPS route tracking for distributors on active deliveries.
* **Executive Dashboard:** Directors require an aggregated, remote dashboard for real-time performance oversight without needing to run manual reports[cite: 3].

## 3. Security & Access (RBAC)
Data must be strictly siloed based on user roles[cite: 3, 4]:
* **Directors:** Full reporting oversight, no direct daily data entry.
* **Managers/Accountants:** Access to financial tools, invoice generation, and distributor assignment.
* **Inventory Staff:** Restricted to stock level management and alerting modules.
* **Distributors:** Restricted to their specific delivery assignments and mobile uploads.

## 4. Infrastructure Imperatives
* **Cloud Disaster Recovery:** The system architecture must include automated database and document backups to a remote cloud server to ensure business continuity in the event of local hardware failure[cite: 3, 4].
uipath-google-sheets-automation
Automated data processing and consolidation in spreadsheets using UiPath Studio with automated email status reply.

# 📊 Automated Spreadsheet Processing & Email Notification Bot

## 📝 Project Overview
An end-to-end **UiPath RPA Solution** designed to automate daily spreadsheet data processing, consolidation, and communication workflows. 

The bot automatically scans input directories, processes multi-file spreadsheets, merges validated records into a master sheet, and triggers an automated email reply/status report to stakeholders upon completion—eliminating 100% of manual effort.

---

## 🔑 Key Features
* **Multi-File Data Consolidation:** Automatically loops through folders to merge dynamic Excel/Google Sheets data.
* **Spreadsheet Manipulation:** Executes `Read Range`, `Auto Fill Range`, and `Write Cell` operations with dynamic data validation.
* **Automated Email Integration:** Sends an automated email reply/notification (via SMTP / Outlook) with execution summary and generated report attachments.
* **Exception Handling:** Built-in validation checks to log errors and skip corrupt file formats without breaking the workflow.

---

## 🛠️ Tools & Technologies
* **RPA Platform:** UiPath Studio (v2024.10)
* **Data Sources:** Microsoft Excel (`.xlsx`), `.csv`, Spreadsheets
* **Integration Activities:** `Send SMTP Mail` / `Reply To Email`, `For Each File in Folder`, `Read/Write Range`

---

## 🚀 Workflow Execution Flow
1. **Trigger:** Bot scans designated input directory for raw spreadsheet files.
2. **Process:** Reads each spreadsheet, validates records, and consolidates data into a Master Spreadsheet.
3. **Archive:** Relocates processed files into an Archive folder for audit trail.
4. **Notify:** Triggers an automated email reply to the team/manager with the final status report attached.

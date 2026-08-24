uipath-google-sheets-automation
Automated data processing and consolidation in spreadsheets using UiPath Studio with automated email status reply.

# 📊 Excel Data Processing & Generative AI Mail Bot (UiPath Integration Service)

## 📝 Project Overview
An enterprise-grade **UiPath RPA Solution** integrated with **UiPath Integration Service** and **Generative AI (Gen AI)** to automate spreadsheet data processing, dynamic email reply generation, and automated reporting.

The bot utilizes built-in **Spreadsheet Functions** for data manipulation, leverages **UiPath Integration Service** to connect seamlessly with Generative AI services for intelligent context understanding, and automates end-to-end email communication.

---

## 🔑 Key Features
* **Advanced Spreadsheet Automation:** Uses native **Spreadsheet Functions**, `Read Range`, `Auto Fill Range`, and `Write Cell` to process and consolidate dynamic multi-file datasets.
* **UiPath Integration Service & GenAI:** Harnesses Integration Service connectors to trigger **Generative AI** activities for intelligent email context analysis, intent classification, and automated reply drafting.
* **Email Automation:** Leverages native Email Activities (`Reply to Email` / `Send Mail`) to deliver automated, context-aware email responses and status reports to stakeholders.

---

## 🛠️ Tools & Technologies
* **RPA Platform:** UiPath Studio
* **AI & Integration:** UiPath Integration Service, Generative AI (Gen AI) Connectors
* **Spreadsheet Automation:** Excel / Spreadsheet Activities & Native Formulas
* **Communication:** UiPath Mail & Email Activities (SMTP/Outlook/Integration Service)

---

## 🚀 Workflow Execution Flow
1. **Directory Monitoring:** Scans input source folders for incoming spreadsheets and email requests.
2. **Gen AI & Email Processing:** Uses Integration Service with Generative AI to interpret query details and draft context-specific email replies.
3. **Spreadsheet Manipulation:** Executes spreadsheet functions and range operations to validate and merge data into a master sheet.
4. **Notification & Archive:** Automatically sends email replies with output reports attached and moves processed files to archive folders.

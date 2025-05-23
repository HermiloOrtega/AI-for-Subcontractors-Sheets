# 🧾 Applying AI for Subcontractors Sheets

## 🧭 Overview
**Applying AI for Subcontractors Sheets** is a Microsoft Power Automate project that automates the processing of structured subcontractor documentation uploaded to SharePoint. Using a trained AI Builder model, the flow extracts key fields from each document and sends them to an Excel file. The extracted data is then visualized in a Power BI dashboard embedded within the **Quattrofy** platform.

---

## 💡 Idea & Concept
This project was developed to streamline and centralize subcontractor data collection. Manual tracking of vendor-provided services and associated costs was prone to delay and inconsistency. By using AI and automation, subcontractor data is captured in near real-time and made available for business reporting and decision-making.

---

## ✨ Features & Functionality
- **Automated Trigger** when a subcontractor sheet is uploaded to SharePoint
- **AI-Powered Extraction** using a trained model to detect:
  - Project name
  - Superintendent who received the sheet
  - Type of services performed
  - Associated costs and totals
  - Vendor/Subcontractor information
- **Excel Integration** to store extracted data
- **Power BI Dashboard** integration for:
  - Filtering by project, vendor, or superintendent
  - Viewing service and cost summaries
  - Identifying high-cost vendors over time

---

## ⚙️ Tech Stack

| Technology | Description |
|------------|-------------|
| ![Power Automate](https://img.shields.io/badge/Power%20Automate-0089D6?logo=Microsoft%20Power%20Automate&logoColor=white&style=for-the-badge) | Automates document processing |
| ![AI Builder](https://img.shields.io/badge/AI%20Builder-742774?logo=microsoft&logoColor=white&style=for-the-badge) | AI model for structured document recognition |
| ![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?logo=microsoft&logoColor=white&style=for-the-badge) | File upload and storage trigger |
| ![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white&style=for-the-badge) | Stores extracted records |
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black&style=for-the-badge) | Dashboard analytics and visualization |
| ![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white&style=for-the-badge) | Structured data in flow |
| ![Quattrofy](https://img.shields.io/badge/Quattrofy-App%20Integration-blue?style=for-the-badge) | Dashboard embedded in internal app |

---

## 🧑‍💻 My Role & Contributions
- Designed and trained the AI model to parse subcontractor document structure
- Developed Microsoft Flow for full automation of upload-to-dashboard pipeline
- Mapped and validated critical fields for each record
- Built Power BI dashboard and connected to Quattrofy
- Optimized for scalability across multiple project folders

---

## 📊 Results
- Eliminated manual data entry and centralized subcontractor records
- Enabled cost monitoring per vendor/service type in real-time
- Reduced processing time for subcontractor documentation by 90%
- Improved collaboration between site superintendents and finance

---

## 🔍 Related Projects
- [Applying AI for Equipment Logs](#)
- [Microsoft Flow PO Requests (AI)](#)
- [Quattrofy](#)

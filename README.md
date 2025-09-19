# Automated Employee Onboarding System  

## 📌 Project Overview  
This project automates the **employee onboarding process** using **UiPath**. It retrieves employee data from an external API, prioritizes records based on business rules, performs web automation for high-priority hires, generates QR codes for IT assets, and produces an automated onboarding report with email notifications.  

---

## 🚀 Features  

- **Data Retrieval & Prioritization**  
  - Fetch employee data via REST API.  
  - Prioritize employees based on salary: High, Normal, Low.  
  - Add employee records to a UiPath Orchestrator Queue.  

- **Web Automation & Data Entry**  
  - Process **High Priority** employees in [RPA Challenge](https://rpachallenge.com/).  
  - Extract first/last name, generate corporate email, and input employee details automatically.  

- **QR Code Generation & File Handling**  
  - Generate IT Asset QR codes containing employee ID & name.  
  - Save QR images in a structured **QRCodes/** folder.  

- **Reporting & Notification**  
  - Create Excel onboarding report with processed employees.  
  - Send email with summary, attach the report, and compress the **QRCodes/** folder.  

---

## 🛠️ Technologies Used  

- **UiPath Studio** (RPA Development)  
- **UiPath Orchestrator** (Queue Management)  
- **Excel Automation**  
- **Email Automation**  
- **Web Automation**

# [Solution Title]

**OPCODE IMPACT 2026 | Hackathon Submission**

**Team ID:** OPC020

## 1. Problem Statement
Medical records sit with hospitals and clinics. Patients can’t easily control who sees them, and shared copies (email, WhatsApp, PDFs) never expire.

## 2. Solution Title
A platform where the patient owns the records. A doctor or facility can view only the records the patient approves, only for a time limit the patient sets, with access ending automatically.

## 3. Solution Description
The problem: Your medical records sit in hospitals, and when you share them by email or WhatsApp, those copies stay with other people forever.
Our fix: You keep all your records in one safe place that belongs to you.
Sharing: When a doctor needs your records, you pick which ones they can see and for how long.

## 4. Architecture Diagram
![Architecture Diagram](docs/architecture.png)

-Patient Login: Patients sign in and access their medical dashboard.
-Upload Medical Records: Patients upload and manage their medical reports securely.
-Share Records: Patients select a doctor, choose the records to share, and set an access duration.
-Doctor Access: Doctors sign in and view only the records they are authorized to access.
-Consent Management: Patients can revoke access, and permissions automatically expire after the specified duration.
-Audit Logs: The system records who accessed the medical records and when, helping maintain transparency and accountability.

## 5. Technology Stack
- **Frontend:** Next.js, TypeScript, Tailwind CSS , nextIntl
- **Backend:** Node.js, Express
- **Database:** MongoDb
- **Other Technologies:** JWT login, encrypted file storage, Zod validation

## 6. Quick Start Guide
**Prerequisites:**
- Node.js 18.17 or newer
- npm (comes with Node.js)
- MySQL 8 (local install or a hosted MySQL database)
- Git
- A modern browser (Chrome, Edge or Firefox)
- A code editor, such as VS Code

**Installation & Execution:**
```bash
# Add commands to install dependencies
# and run your project here
```

## 7. Output Screenshots
![Output Screenshot](docs/output.png)

[Briefly describe the output.]

## 8. Future Scope
- Emergency access: A trusted person can open key records in an emergency.
- Hospital integration: Lab and hospital reports go into the vault automatically.

## 9. Team Contributions
| Member Name | Contribution |
|-------------|--------------|
| Shravani Bhosale | Planning, PRD, task split and final presentation |
| Karan Shelge | APIs, MySQL database, login, access rules and audit logs |
| Roshan Das | Login, dashboard, record upload and sharing |
| Tanmay Rokade | Test cases, bug reports and checking consent |

## 10. Tools Used
| Tool / Platform | Purpose / Why Used |
|-----------------|--------------------|
| VS Code | To run and view the code |
| GitHub | To work together and share code |
| Postman | To test our backend |
| MongoDB Compass | To check our database |
| Claude (AI) | Wrote the PRD and the project code (AI-generated), based on our idea and instructions |

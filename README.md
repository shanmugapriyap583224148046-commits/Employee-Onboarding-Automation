🚀 Employee Onboarding Automation (n8n)
📌 Project Overview

Employee Onboarding Automation is an end-to-end workflow built using n8n that automates the onboarding process when a new employee submits details through a Google Form.
The automation eliminates manual effort by validating data, notifying HR, and storing employee details automatically.

🎯 Objective

To design a no-code automation that:

Collects employee details from a Google Form

Sends structured email notifications to HR

Stores employee information in Google Sheets

Prevents duplicate executions and errors

⚙️ Workflow Architecture
Google Form Submission
        ↓
Google Sheets Trigger (New Row Added)
        ↓
Edit / Map Employee Fields
        ↓
Limit Items (Prevent Duplicate Processing)
        ↓
Wait (Rate-limit protection)
        ↓
Send Email Notification to HR
        ↓
Store Employee Details in Google Sheets

🧰 Tools & Technologies Used

n8n – Workflow automation platform

Google Forms – Employee data collection

Google Sheets – Data storage

Gmail API – Email notifications

HTML/CSS – Email template design

✨ Key Features

✅ Fully automated onboarding process

✅ Real-time trigger on new form submission

✅ Email-safe HTML template for HR notifications

✅ Duplicate execution prevention

✅ Gmail rate-limit handling using delay logic

✅ Clean and structured employee data storage

📝 Employee Details Captured

Employee Name

Email ID

Phone Number

Department

Job Role

Location

🔒 Best Practices Implemented

Trigger runs only on new submissions

Item limiting to avoid multiple executions

Delay node to prevent Gmail API rate-limit errors

Proper field mapping and validation

Email layout compatible with Gmail & Outlook

📈 Use Cases

HR onboarding automation

No-code workflow demonstrations

Academic mini-project / capstone project

Automation portfolio showcase

📌 How to Run the Workflow

Import the workflow into n8n

Connect Google Form, Google Sheets, and Gmail credentials

Activate the workflow

Submit a new Google Form response

HR receives an automated onboarding email

🧠 Learning Outcomes

Hands-on experience with no-code automation

Understanding event-based workflows

Working with Google APIs in n8n

Designing email-safe HTML templates

Implementing production-ready automation logic

📄 License

This project is for educational and demonstration purposes.

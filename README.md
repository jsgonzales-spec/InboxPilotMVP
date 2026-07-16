# 🚀 InboxPilot

### AI Email Operations Assistant

![Status](https://img.shields.io/badge/Status-MVP-blue)
![Built With](https://img.shields.io/badge/Built%20With-n8n-orange)
![Automation](https://img.shields.io/badge/Category-AI%20Automation-success)
![License](https://img.shields.io/badge/License-MIT-green)

InboxPilot is an AI-powered email operations workflow designed to help businesses automate repetitive inbox management.

Instead of manually reading, sorting, prioritizing, and responding to every email, InboxPilot analyzes incoming messages, categorizes them using AI, generates draft responses, routes inquiries to the appropriate department, and alerts the sales team whenever a high-priority opportunity is detected.

---

# 📌 Business Problem

Many small businesses lose valuable time every day manually managing their inboxes.

Typical workflow:

- Read every email manually
- Decide if it is important
- Identify which department should handle it
- Write repetitive replies
- Notify managers when urgent opportunities appear

As businesses grow, this process becomes slower, more expensive, and increases the risk of missing valuable customers.

---

# 💡 Solution

InboxPilot automates the entire email triage process by combining business workflow automation with AI-powered decision making.

The workflow:

- Organizes incoming emails
- Prevents duplicate processing
- Detects spam
- Categorizes inquiries
- Generates professional draft responses
- Routes requests to the correct department
- Identifies high-priority sales opportunities
- Triggers business alerts

---

# ⚙️ Features

### 📥 Email Intake

Standardizes incoming email data into a consistent structure before processing.

---

### 🔄 Duplicate Detection

Prevents emails from being processed multiple times.

---

### 🤖 AI Email Analysis

Automatically determines:

- Email Category
- Priority
- Urgency
- Summary
- Key Points
- Draft Reply

---

### ✅ AI Output Validation

Verifies that AI returned complete and usable information before continuing the workflow.

---

### 🚫 Spam Detection

Automatically filters spam emails from the workflow.

---

### 🏢 Department Routing

Routes emails into:

- Sales
- Support
- Billing
- Internal
- Other

---

### ✉️ Draft Response Generator

Prepares professional draft replies for human review before sending.

---

### 🚨 Priority Alert

Detects high-priority sales inquiries and triggers business alerts for immediate follow-up.

---

# 🏗 Workflow Architecture


Email
    │
    ▼
Normalize Email
    │
    ▼
Duplicate Check
    │
    ▼
Already Processed?
    │
    ▼
AI Analysis
    │
    ▼
Validate AI Output
    │
    ▼
Spam Check
    │
    ▼
Route by Category
    │
    ▼
Draft Response Generator
    │
    ▼
High Priority Sales?
    │
    ▼
Priority Alert




# 🛠 Tech Stack

- n8n
- JavaScript
- Workflow Automation
- AI Workflow Design
- Business Process Automation



# 📈 Business Benefits

InboxPilot helps businesses:

- Reduce repetitive administrative work
- Improve email response time
- Detect important sales opportunities faster
- Reduce the risk of missed customer inquiries
- Standardize email handling processes
- Improve operational efficiency



# 📷 Screenshots

## Workflow

<img width="1672" height="907" alt="image" src="https://github.com/user-attachments/assets/ba3c54fd-aa19-4d34-a822-93944b79b125" />


## Sample Output

[
  {
    "message_id": "msg_001",
    "thread_id": "thread_001",
    "sender": "client@example.com",
    "subject": "Need Website Quote",
    "body": "Hello, I'd like a quote for a website redesign.",
    "received_at": "2026-07-12T10:00:00Z",
    "has_attachments": false,
    "already_processed": false,
    "category": "Sales",
    "priority": "High",
    "urgency": true,
    "summary": "Client is requesting a website redesign quote.",
    "keyPoints": [
      "Needs redesign",
      "Budget requested",
      "Wants a meeting"
    ],
    "draftReply": "Hi John,\n\nThank you for reaching out. We'd be happy to discuss your website redesign...",
    "aiSucceeded": true,
    "draftCreated": true,
    "workflowStatus": "Completed",
    "alertTriggered": true,
    "alertRecipient": "Sales Manager",
    "alertPriority": "High",
    "alertMessage": "High-priority sales inquiry detected. Immediate follow-up recommended."
  }
]




# 👩‍💻 Author

**Juliane S. Gonzales**

Bachelor of Science in Information Technology (Cybersecurity)

Far Eastern University Institute of Technology

GitHub:
https://github.com/jsgonzales-spec

LinkedIn:
https://www.linkedin.com/in/juliane-gonzales-410480403



# ⭐ Repository Goal

InboxPilot was built as part of my AI Automation Portfolio to demonstrate practical workflow automation for real business operations.

Future projects will focus on solving repetitive business tasks commonly found in Virtual Assistant, Operations, and Administrative Support roles.

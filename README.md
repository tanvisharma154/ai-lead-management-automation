# AI Lead Management Automation 🚀

An AI-powered lead management workflow built using **n8n** that automates lead capture, qualification, approval, and follow-up communication.

## 📌 Project Overview

Managing leads manually can be time-consuming. This project uses AI and workflow automation to simplify the process by analyzing incoming leads, assigning scores, and preparing personalized follow-up emails.

It also includes a human approval step before sending emails to customers.

## ✨ Key Features

- **Automated Lead Capture:** Collects lead information through an online form.
- **AI Lead Scoring:** Assigns a score from 0–100 to each lead.
- **Lead Classification:** Categorizes leads as Hot, Warm, or Cold.
- **AI-Generated Summary:** Creates a short summary of each lead.
- **Email Validation:** Checks whether the lead has a valid email address.
- **Human Approval:** Sends an approval request to the owner through Gmail.
- **Automated Follow-up:** Sends personalized emails only after approval.
- **Lead Status Tracking:** Tracks leads as Sent, Rejected, or Needs Contact.

## ⚙️ Workflow

1. A user submits the lead form.
2. AI analyzes the lead and generates a score, category, summary, and follow-up draft.
3. Lead information is saved in an n8n Data Table.
4. The workflow checks whether the email address is valid.
5. The owner receives an approval request through Gmail.
6. If approved, the follow-up email is sent to the customer.
7. If rejected, the lead status is updated.
8. If the email is invalid, the owner receives a notification to update the contact details.

## 🛠️ Tech Stack

- n8n – Workflow Automation
- AI / OpenAI – Lead Analysis and Scoring
- Gmail – Approval Requests and Email Notifications
- n8n Forms – Lead Data Collection
- n8n Data Tables – Lead Information Storage

## 📂 Repository Structure

```text
ai-lead-management-automation/
│
├── AI Lead Management.json
└── README.md
```

## 🚀 Setup Instructions

1. Download or clone this repository.
2. Open your n8n instance.
3. Import `AI Lead Management.json` into n8n.
4. Configure your AI model credentials.
5. Connect your Gmail account.
6. Create or select an n8n Data Table named `Leads`.
7. Replace the `YOUR_DATA_TABLE_ID` placeholder with your actual Data Table ID.
8. Update the owner email address in the relevant nodes.
9. Test the workflow using sample lead submissions.
10. Activate the workflow after successful testing.



## 🎯 Learning Outcomes

Through this project, I explored:

- Building multi-step automation workflows.
- Integrating AI into business processes.
- Implementing conditional logic.
- Working with human-in-the-loop approval systems.
- Automating email communication.
- Managing workflow execution and lead statuses.

## 👩‍💻 Author

**Tanvi Sharma**

GitHub: [@tanvisharma154](https://github.com/tanvisharma154)

---

⭐ If you find this project useful, feel free to star the repository!

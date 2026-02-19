# 🚀 AI-Powered Feedback Automation Workflow  
### Built with n8n + Google Gemini

---

## 📌 Overview

This project demonstrates an intelligent automation workflow built using **n8n** and **Google Gemini AI**.

The system automatically processes form submissions, performs AI-powered sentiment analysis, and routes feedback based on emotional classification — including a human-in-the-loop escalation for negative responses.

This workflow is designed for marketing agencies, SaaS companies, and businesses that want structured, intelligent feedback handling.

---

## ⚙️ How the Workflow Works

### 1️⃣ Form Submission (Trigger)
A user submits a feedback form.

### 2️⃣ Data Logging
The submission is automatically stored in **Google Sheets**.

### 3️⃣ AI Sentiment Analysis
Google Gemini analyzes the message and classifies it as:
- ✅ Positive  
- ➖ Neutral  
- 🚨 Negative  

### 4️⃣ Intelligent Routing Logic

| Sentiment  | Action Taken |
|------------|--------------|
| Positive   | Logged + Email Notification |
| Neutral    | Logged for Review |
| Negative   | Logged + Email Alert + Slack Escalation |

---

## 🧠 Human-in-the-Loop Design

Instead of auto-responding to negative feedback, the system escalates critical responses to a human.

This ensures:
- Sensitive issues are handled properly
- No inappropriate automated replies
- Better customer experience management

Automation supports decisions — it doesn’t replace judgment.

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation engine  
- **Google Gemini API** – AI sentiment classification  
- **Google Sheets** – Structured logging  
- **Gmail** – Email notifications  
- **Slack** – Escalation alerts  

---

## 📊 Use Cases

- Marketing agency client feedback tracking  
- SaaS support form processing  
- Lead quality monitoring  
- Customer satisfaction analysis  

---

## 🔧 Setup Instructions

1. Import the provided JSON file into n8n.
2. Configure credentials:
   - Google Gemini API
   - Google Sheets
   - Gmail
   - Slack
3. Activate the workflow.
4. Connect your form trigger (Webhook or Form node).
5. Test with sample data.

---

## 🎯 Key Features

- Automated data collection
- AI-powered classification
- Conditional routing logic
- Multi-channel notifications
- Escalation-based workflow design
- Scalable structure for agency use

---

## 📸 Workflow Architecture

<img width="1204" height="400" alt="image" src="https://github.com/user-attachments/assets/f91069d2-00e3-40f0-8f1a-91c7838e3496" />


---

## 📬 Future Improvements

- Auto-reply generation for positive responses  
- CRM integration (HubSpot, ClickUp, etc.)  
- Analytics dashboard  
- Multi-client scaling structure  

---

## 📢 Author

Built by Abdus Samad Kandhro

If you're interested in automation solutions for marketing agencies or feedback systems, feel free to connect.

---

#Automation #n8n #AI #WorkflowAutomation #MarketingAutomation

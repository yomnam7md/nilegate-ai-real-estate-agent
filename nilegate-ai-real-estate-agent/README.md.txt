# 🏠 Real Estate AI Automation

An AI-powered real estate automation workflow built with **n8n** to handle property inquiries through Telegram, provide relevant property information, collect customer details, and store leads automatically in Google Sheets.

## 🚀 Project Overview

This project demonstrates how AI and workflow automation can be used to streamline the initial stage of a real estate sales process.

Instead of manually handling every incoming inquiry, the workflow:

* Receives messages from customers through Telegram.
* Uses an AI model to understand and respond to customer inquiries.
* Provides property information based on the available data.
* Collects important customer information.
* Stores qualified leads automatically in Google Sheets.

---

## 🔄 Workflow

The automation is built using **n8n** and connects Telegram, an AI model, and Google Sheets.

### Workflow Architecture

**Telegram → AI Processing → Lead Information → Google Sheets**

![Real Estate Workflow](screenshots/workflow-1.png)

![Real Estate Workflow Details](screenshots/workflow-2.png)

---

## 💬 Telegram Chat

Customers can interact with the real estate assistant directly through Telegram.

The assistant can answer property-related questions and guide the customer through the inquiry process.

### Example Conversation

![Telegram Chat](screenshots/telegram-1.png)

![Telegram Chat](screenshots/telegram-2.png)

---

## 📊 Lead Management

Customer information collected during the conversation is automatically stored in Google Sheets.

This provides a simple lead-management system that can be used by a sales team to follow up with potential customers.

![Google Sheets](screenshots/sheets-1.png)

![Google Sheets](screenshots/sheets-2.png)

---

## 🧩 Technologies Used

* **n8n** — Workflow automation
* **Telegram Bot API** — Customer communication
* **AI / LLM** — Natural-language understanding and responses
* **Google Sheets** — Lead storage and management

---

## ⚙️ Key Automation Features

### 1. Customer Communication

Customers can start a conversation through Telegram without requiring manual intervention.

### 2. AI-Powered Responses

The AI assistant processes customer messages and generates appropriate responses based on the real estate information provided to it.

### 3. Lead Collection

The workflow collects relevant customer information during the conversation.

### 4. Automatic Data Storage

Collected lead information is automatically added to Google Sheets.

### 5. End-to-End Automation

The workflow connects the customer interaction, AI processing, and lead storage into one automated process.

---

## 🎯 Business Use Case

This workflow can be adapted for real estate companies that receive a large number of inquiries through messaging platforms.

Potential applications include:

* Property inquiries
* Lead qualification
* Customer information collection
* Property recommendations
* Initial sales conversations
* Automated lead management

---

## 📁 Project Structure

```text
real-estate-ai-automation/
│
├── screenshots/
│   ├── RealEstateWorkflow.png
│   ├── FileIngestionWorkflow.png
│   ├── telegrambotconv1.png
│   ├── telegrambotconv2.png
│   ├── PropertiesInfo.png
│   └── leads.png
│
├── workflow/
│   └── real-estate-workflow.json
│
└── README.md
```

---

## 🔐 Security & Privacy

The workflow export included in this repository has been cleaned of sensitive information.

API keys, credentials, tokens, personal information, and other private data should **never** be included in the repository.

Credentials must be configured separately when importing the workflow into n8n.

---

## 📌 What I Learned

Through this project, I practiced:

* Building multi-step workflows with n8n
* Integrating Telegram with n8n
* Connecting AI models to automation workflows
* Designing AI prompts for customer interactions
* Extracting and handling structured lead information
* Integrating Google Sheets with n8n
* Building an end-to-end AI automation workflow
* Preparing automation projects for deployment and portfolio presentation

---

## 🔮 Possible Improvements

Future versions could include:

* CRM integration
* WhatsApp integration
* Property database integration
* Automated lead scoring
* Follow-up messages
* Appointment scheduling
* Voice-message processing
* Human-agent handoff
* Dashboard for tracking leads

---

## 👩‍💻 Author

**Yomna Mohamed Ra'fat**

Fresh graduate specializing in Bioinformatics, currently building practical projects in **AI Automation, n8n, and software development**.

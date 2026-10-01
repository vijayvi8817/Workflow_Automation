# Awesome n8n Automation Templates

> A curated collection of reusable n8n workflow templates for email automation, AI assistants, WhatsApp, Telegram, HR/recruitment, sales enablement, social media, and multi-channel messaging. Review, configure, and test each workflow before production use.

## 📚 Template Categories

- 📧 Email & Inbox Automation
- 🤖 Telegram & AI Assistants
- 💬 WhatsApp & Multi-Channel Messaging
- 👥 HR & Recruitment
- 📈 Sales & Meeting Intelligence
- 📱 Social Media & Content Automation

---

## How can I automate Email with n8n?

Explore **7 email automation templates** covering AI-generated replies, inbox summaries, email categorization, RAG-powered email assistance, Fastmail automation, and daily Telegram notifications.

| Title | Description | Department | Link |
|---|---|---|---|
| Compose Reply Draft in Gmail with OpenAI Assistant | Monitors Gmail threads with a trigger label, sends the latest email content to an OpenAI Assistant, generates a reply draft, converts it to HTML, and inserts the draft back into the original Gmail thread. | Support / Productivity | Link to Template |
| Create Email Responses with Fastmail and OpenAI | Automates email reply drafting for Fastmail by monitoring incoming messages through IMAP/JMAP, processing the email content with OpenAI, and preparing an AI-generated response. | Support / Productivity | Link to Template |
| Daily AI Digest of Unread Emails to Telegram | Runs every weekday morning, collects unread Gmail messages from the previous day, summarizes them with AI, orders them by urgency, and sends the digest to Telegram. | Productivity / Ops | Link to Template |
| Daily IMAP Email Summary to Telegram with Local Ollama | Retrieves email through IMAP on a schedule, processes message content locally, and sends an AI-generated daily email summary to Telegram using a local Ollama model. | Productivity / Ops | Link to Template |
| Effortless Email Management with AI | Processes incoming email, converts it to Markdown, summarizes it, retrieves company knowledge from a Qdrant vector store, generates a response with RAG, and supports human review before sending. | Support / Knowledge Management | Link to Template |
| Email Summary Agent | Runs daily, retrieves recent emails, extracts useful sender/recipient/CC/content information, summarizes the messages, and sends a formatted HTML report to configured recipients. | Productivity / Ops | Link to Template |
| Auto Categorise Outlook Emails with AI | Monitors Outlook emails, sanitizes message content, uses an AI agent to classify messages, converts the result to structured JSON, applies categories, moves messages to folders, and handles read-state logic. | Operations / Productivity | Link to Template |

---

## What are the best n8n templates for Telegram and AI assistants?

Browse **4 Telegram automation templates** for conversational AI, image generation, command-based bots, and conversation memory.

| Title | Description | Department | Link |
|---|---|---|---|
| Telegram AI Chatbot | A Telegram AI bot supporting normal conversations plus command-based functionality such as `/start` and `/image`, with routing for unsupported commands. | Support / Marketing | Link to Template |
| AI Image Creation with OpenAI and Telegram | Receives Telegram messages, sends prompts to OpenAI for image generation, processes the resulting data, and returns generated images to the Telegram user. | Marketing / Creative | Link to Template |
| Telegram AI Support Bot with Conversation Memory | A lightweight Telegram support assistant using an OpenAI chat model and per-user conversation memory to maintain context across messages. | Customer Support | Link to Template |
| Internship Informer | Processes internship/job information received through Telegram, uses AI to extract structured opportunities and application links, and supports downstream filtering and notification workflows. | HR / Career Ops | Link to Template |

---

## How can I automate WhatsApp and multi-channel messaging with n8n?

Explore **3 messaging templates** for WhatsApp AI sales support and unified WhatsApp, Instagram, and Facebook Messenger communication.

| Title | Description | Department | Link |
|---|---|---|---|
| Building Your First WhatsApp Chatbot | Builds a WhatsApp sales chatbot backed by a product-brochure vector store so an AI agent can answer customer questions using product information. | Sales / Customer Support | Link to Template |
| Receive and Send Messages Across WhatsApp, Instagram and Facebook Messenger with Fiwano | Provides a unified receive → logic → send workflow for WhatsApp, Instagram DMs, and Facebook Messenger using normalized Fiwano message data. | Customer Support / Messaging | Link to Template |
| Automate Sales Meeting Prep with AI & Apify — Sent to WhatsApp | Finds upcoming meetings, extracts attendee details, gathers recent email and LinkedIn activity, summarizes the research with AI, and sends a pre-meeting briefing through WhatsApp. | Sales | Link to Template |

---

## What n8n templates are available for HR and recruitment?

Browse **3 HR automation templates** for CV screening, applicant evaluation, and AI-assisted recruitment workflows.

| Title | Description | Department | Link |
|---|---|---|---|
| CV Screening with OpenAI | Downloads a CV, extracts its PDF content, combines it with a job description, sends the information to OpenAI for structured candidate analysis, and can store the results for further processing. | HR / Recruitment | Link to Template |
| HR Job Posting and Evaluation with AI | Collects applicant details through an n8n form, evaluates CVs against a job description with AI, updates Airtable with scores and reasons, generates screening questions, personalizes communication, and supports interview scheduling. | HR / Recruitment | Link to Template |
| Internship Informer | Extracts internship opportunities from Telegram content, separates multiple roles, identifies genuine application links, and structures opportunities for eligibility filtering and notifications. | HR / Career Ops | Link to Template |

---

## How can I automate sales and meeting preparation with n8n?

Use AI and external data sources to prepare sales teams before meetings.

| Title | Description | Department | Link |
|---|---|---|---|
| Automate Sales Meeting Prep with AI & Apify — Sent to WhatsApp | Periodically checks upcoming meetings, researches attendees through email and LinkedIn data, summarizes relevant correspondence and activity, and sends an information-dense pre-meeting notification to WhatsApp. | Sales | Link to Template |

---

## What n8n templates are available for social media and content automation?

Explore **3 social media automation templates** for AI content generation, dynamic X/Twitter banners, and automated YouTube promotion.

| Title | Description | Department | Link |
|---|---|---|---|
| AI Social Media Content Generator with Ollama | Generates platform-specific content for Twitter/X, LinkedIn, Reddit, and Instagram using a local Ollama model, with configurable topic, brand voice, and target audience. | Marketing / Content | Link to Template |
| Create Dynamic Twitter Profile Banner | Retrieves follower/profile data and images, processes them with image manipulation nodes, and combines the assets into a dynamically generated Twitter/X profile banner. | Marketing / Creative | Link to Template |
| Post New YouTube Videos to X | Detects new YouTube videos, uses ChatGPT to generate a short promotional post, and automatically publishes the generated post to X/Twitter. | Marketing / Social Media | Link to Template |

---

## 🔧 Technology Coverage

These workflows demonstrate integrations and building blocks including:

- **AI / LLM:** OpenAI, Ollama, AI Agents, structured AI output
- **Messaging:** Telegram, WhatsApp, Instagram, Facebook Messenger, Fiwano
- **Email:** Gmail, IMAP, Fastmail/JMAP, Microsoft Outlook
- **Knowledge & RAG:** Qdrant, embeddings, vector stores, retrieval-augmented generation
- **HR:** CV/PDF extraction, applicant evaluation, Airtable, forms
- **Sales:** Google Calendar, Gmail, LinkedIn research, Apify, WhatsApp
- **Social:** X/Twitter, YouTube, LinkedIn, Reddit, Instagram
- **Content processing:** Markdown conversion, PDF extraction, JSON transformation, image processing
- **Automation:** Schedule triggers, webhooks, conditional routing, sub-workflows, memory, HTTP APIs

---

## ⚙️ Before You Use These Templates

1. Import the workflow JSON into your n8n instance.
2. Review all credentials and replace example credentials with your own.
3. Check API keys, OAuth connections, webhook URLs, and environment-specific settings.
4. Review AI prompts and model selections before running in production.
5. Test each workflow manually with sample data.
6. Activate scheduled/webhook workflows only after confirming the complete flow.
7. For workflows using external services such as Apify, Qdrant, Fastmail, Fiwano, Ollama, or messaging APIs, configure the required service before activation.
8. Remove or replace any creator-specific links, credentials, IDs, or example data.

> **Important:** Some templates require additional setup such as API credentials, OAuth permissions, public webhook access, local Ollama, vector databases, or third-party services.

---

## 📊 Template Overview

| Category | Templates |
|---|---:|
| Email & Inbox Automation | 7 |
| Telegram & AI Assistants | 4 |
| WhatsApp & Multi-Channel Messaging | 3 |
| HR & Recruitment | 3 |
| Sales & Meeting Intelligence | 1 |
| Social Media & Content | 3 |
| **Unique workflows** | **19** |

---

## 🚀 Automate any workflow with n8n

These templates are intended as starting points for building production-ready automations. Customize the triggers, AI models, prompts, integrations, routing logic, and outputs for your own use case.

**Import → Configure → Test → Automate**

---

## 📁 Included Workflows

```text
email/
├── Compose reply draft in Gmail with OpenAI Assistant
├── Create e-mail responses with Fastmail and OpenAI
├── Daily AI digest of unread emails to Telegram
├── Daily Email Notification
├── Effortless Email Management with AI
├── Email Summary Agent
└── Auto Categorise Outlook Emails with AI

telegram/
├── Telegram AI Chatbot
├── Image Creation with OpenAI and Telegram
├── Telegram AI Support Bot with Conversation Memory
└── Internship Informer

messaging/
├── Receive and Send Messages Across WhatsApp, Instagram and Facebook Messenger with Fiwano
├── Automate Sales Meeting Prep with AI & Apify Sent To WhatsApp
└── Building Your First WhatsApp Chatbot

hr/
├── CV Screening with OpenAI
├── HR Job Posting and Evaluation with AI
└── Internship Informer

social/
├── AI Social Media Content Generator with Ollama
├── Create dynamic Twitter profile banner
└── Post New YouTube Videos to X
```

### License

Add the license that applies to your repository and verify the licensing terms of any third-party n8n templates before redistribution.

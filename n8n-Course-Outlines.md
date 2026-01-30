# **Practical Automation & AI Workflows Using n8n**

# Course Duration: **15 Hours**

### A practical introduction — building begins immediately

# Course Format:

### **Project-Based Learning (Approximately 85% Practical)**

# Course Introduction

This course is designed to provide learners with a practical and structured introduction to automation and AI-powered workflows using **n8n**. The focus is on _building real systems from the very first session_, ensuring that learners understand automation by applying concepts directly rather than studying them in isolation.
Participants will progress from basic automation workflows to intelligent AI-assisted systems, gaining hands-on experience with triggers, core nodes, APIs, Webhooks, and AI agents. By the end of the course, learners will be able to design, implement, and deploy complete automation solutions independently.

# Teaching Methodology: Learning Through Building

This course adopts a **learning-by-doing** approach, where concepts are introduced only when required by a practical task.

- Emphasis on real execution rather than theory
- Continuous hands-on workflow building
- Concepts introduced inside real use cases
- Gradual increase in complexity
- Strong focus on understanding data flow and logic

# Course Structure Overview

| Phase     | Focus                              | Duration     |
| --------- | ---------------------------------- | ------------ |
| Phase 1   | Foundations Through Practice       | 2 Hours      |
| Phase 2   | Core Automation Skills             | 6 Hours      |
| Phase 3   | Data, APIs & Intelligent Logic     | 4 Hours      |
| Phase 4   | AI Automation & Advanced Workflows | 3 Hours      |
| **Total** |                                    | **15 Hours** |

# Phase 1: Foundations Through Practice (2 Hours)

**A practical introduction — building begins immediately**

## Session 1: Automation Basics & n8n Environment Setup

### Session Objective

Introduce automation concepts and the n8n platform while building a simple workflow from the first hour.

### Practical Activity

Create a basic scheduled workflow that formats data and sends a notification with gmail.

### Topics Covered

- Introduction to automation and AI-assisted workflows
- Overview of automation tools (n8n, Zapier, Make)
- n8n platform overview
- Installation options:
  - n8n Cloud
  - Self-hosted n8n using Docker
  - VPS deployment using EasyPanel
- Workflow structure and execution
- Manual Trigger and Schedule Trigger
- Introduction to version control concepts (GitHub overview for non-technical users)

# Phase 2: Core Automation Skills (6 Hours)

## **Building confidence with essential automation patterns**

### **Project 1: Automated Task Reminder System**

#### **Duration:** 3 Hours

#### **Goal:** Create a reliable system that automatically tracks tasks, identifies upcoming deadlines, and sends notifications.

**Detailed Breakdown:**

- **Data Source:** Use a Google Sheets or Airtable base containing tasks, due dates, and assignees.
- **Triggers:** Schedule Trigger to run daily or hourly.
- **Core Nodes Used:**
  - **Google Sheets / Airtable node** to fetch task data.
  - **Date & Time node** to compare due dates with current date.
  - **Filter node** to identify tasks due within a set timeframe (e.g., next 24 hours).
  - **Code node (optional)** for custom date logic or formatting.
  - **Email node (Gmail/Outlook)** or **Messaging node (Telegram/Slack)** to send reminders.
- **Real-World Use Case:**  
  Can be adapted for project management, personal to-do lists, team task tracking, or event reminders.

### **Project 2: Simple Data Cleaning & Reporting Workflow**

#### **Duration:** 3 Hours

#### **Goal:** Automate the process of cleaning, organizing, and summarizing structured data for reporting.

**Detailed Breakdown:**

- **Data Source:** CSV file or Google Sheets with raw, unstructured data (e.g., sales records, survey responses).
- **Triggers:** Manual trigger or schedule for regular reports.
- **Core Nodes Used:**
  - **Spreadsheet node** to import data.
  - **Filter node** to remove incomplete or irrelevant entries.
  - **Aggregate node** to summarize data (e.g., sum, average, count).
  - **Table node** to reformat cleaned data.
  - **Google Sheets / Notion node** to export cleaned data or generate reports.
  - **Email node** to send the report automatically.
- **Real-World Use Case:**  
  Monthly sales reports, customer feedback analysis, inventory tracking, or data migration prep.

# Phase 3: Data, APIs & Intelligent Logic (4 Hours)

## **Moving from automation to smart decision-making**

### **Project 3: Text Classification & Alert Workflow**

#### **Duration:** 4 Hours

#### **Goal:** Use AI to classify text inputs and trigger alerts based on content.

**Detailed Breakdown:**

- **Data Source:** form submission, or email intake.
- **Triggers:** Email trigger for real-time processing.
- **Core Nodes Used:**
  - **Gmail node** to receive text input.
  - **AI node (OpenAI, Hugging Face, or local model)** to classify text (e.g., sentiment, topic, urgency).
  - **Switch node** to route based on classification.
  - **Code node** for custom logic or scoring. (Optional)
  - **Notification node (Slack, Email, SMS)** to alert relevant teams.
  - **Google Sheets node** to log classified entries.
- **Real-World Use Case:**  
  Customer support ticket triage, social media monitoring, feedback categorization, or spam detection.

# Phase 4: AI Automation & Advanced Workflows (3 Hours)

## **Designing intelligent and interactive systems**

### **Project 4: AI-Powered Calendar & Gmail Assistant**

#### **Duration:** 3 Hours

#### **Goal:** Build an intelligent assistant that manages calendar events and emails via natural language commands through a chat interface.

**Detailed Breakdown:**

- **Data Source:** User commands from **Telegram, Slack, or Discord**.
- **Triggers:** Webhook from messaging platform.
- **Core Nodes Used:**
  - **Telegram/Slack/Discord node** to receive user messages.
  - **AI node (OpenAI GPT, Claude, or local LLM)** to interpret user intent and extract structured data.
  - **Google Calendar node** to create, update, list, or delete events.
  - **Gmail node** to send emails, search inbox, or draft replies.
  - **Function node** to format dates, parse commands.
  - **Condition/Switch node** to route requests (e.g., calendar vs. email tasks).
  - **Same messaging node** to reply to user with confirmation or results.
  - **Google Sheets/Notion node** (optional) for logging interactions.

**Real-World Use Case:**  
Personal productivity assistant, team scheduling coordinator, email triage bot, or virtual office assistant.

# Course Completion & Outcomes

By the end of this course, participants will be able to:

- Understand automation and AI workflow design
- Build reliable automation workflows using n8n
- Work confidently with triggers, core nodes, and data flow
- Integrate APIs and Webhooks
- Design simple AI-powered workflows
- Apply automation concepts to real-world scenarios

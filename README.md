# Practical Automation & AI Workflows Using n8n

![Course Banner](docs/course%20image.jpeg)

> **IEEE HU SIGHT Course** | By Qata Mohammad Ismail

A hands-on, project-based course designed to take you from automation fundamentals to building intelligent AI-powered workflows using **n8n**.

---

## Course Overview

| Detail       | Information                            |
| ------------ | -------------------------------------- |
| **Duration** | 20 Hours Total                         |
| **Sessions** | 4 Sessions (5 Hours Each)              |
| **Format**   | ~85% Practical, Project-Based Learning |
| **Level**    | Beginner to Advanced                   |

This course focuses on **building real systems from the very first session**. Concepts are introduced only when required by a practical task, ensuring that learners understand automation by applying concepts directly.

---

## What You'll Learn

- Understand automation and AI workflow design
- Build reliable automation workflows using n8n
- Work confidently with triggers, core nodes, and data flow
- Master JSON data handling and JavaScript expressions
- Integrate APIs and Webhooks
- Design AI-powered workflows with LLMs and agents
- Build RAG systems and MCP integrations
- Apply automation concepts to real-world scenarios

---

## Course Structure

### Session 1: Foundations of Automation, n8n, and APIs (5 Hours)

**Goal:** Build a strong mental model of automation, understand how n8n works, and master API fundamentals.

**Topics Covered:**

- AI and Automation Introduction
- Automation Tools Overview (n8n vs Zapier vs Make)
- n8n Installation & Environment Setup
  - n8n Cloud
  - Self-hosted via Docker
  - VPS deployment using EasyPanel
- Version Control Introduction (GitHub for non-technical users)
- Core n8n Concepts (Workflows, Nodes, Execution Flow)
- JSON and Data Flow in n8n
- Essential Triggers (Manual, Schedule, Gmail, Google Sheets, Form Submission)
- Basic Core Nodes (Set, If, Switch, Filter, Merge, Wait, Loop Over Items)
- Introduction to APIs (REST, HTTP Request Node)

**Workflows:**

- `Core n8n Concepts.json`
- `Essential Triggers.json`
- `Fundamental Core Nodes.json`
- `JSON and Data Flow in n8n.json`
- `APIs Deep Dive.json`
- `Basic Projects.json`

---

### Session 2: Core Automation Skills & Business Workflows (5 Hours)

**Goal:** Build confidence by creating useful, reliable automation for real businesses.

**Topics Covered:**

- OCR Automation Project
- n8n Expressions (JavaScript Expressions)
- Code Node Basics
- Error Handling in n8n
- Introduction to Webhooks
- Webhook Node and Respond to Webhook
- Credentials Setup (Google, Telegram)
- WhatsApp Integration Overview
- Evolution API for Free WhatsApp Automation

**Workflows:**

- `Project-1-OCR.json`
- `JavaScript in n8n.json`
- `Error Handling & Debugging.json`
- `Introduction to webhooks.json`
- `Setup Google Credentials.json`
- `WhatsApp nightmare.json`
- `Evolution API.json`
- `Project 2 Student Performance Tracker & Automated Feedback System.json`

---

### Session 3: AI Integration & Intelligent Workflows (5 Hours)

**Goal:** Make students comfortable with AI-powered automation and prompt engineering.

**Topics Covered:**

- AI Core Nodes Introduction
  - Basic LLM Chain
  - Sentiment Analysis
  - Summarization Chain
  - Information Extractor
  - Text Classifier
- AI Agent Fundamentals
- Introduction to Prompt Engineering
- Simple AI Agent Example (Email & Calendar Organizer)

**Workflows:**

- `AI Core Nodes Introduction.json`
- `AI Agent Fundamentals.json`
- `Introduction To Prompt Engineering.json`
- `simple agent example.json`
- `project-1 -Automated-resume-scoring.json`

---

### Session 4: Advanced AI, RAG & MCP Systems (5 Hours)

**Goal:** Move from automation to intelligent systems.

**Topics Covered:**

- Agentic Framework Concepts
- Advanced AI Tools in n8n
  - HTTP Tool
  - Call Workflow Tool
  - Code Tool
  - Structured Output Parser
- RAG Systems (Retrieval-Augmented Generation)
  - RAG Fundamentals
  - Building Your First RAG System
  - Advanced RAG Techniques
- Model Context Protocol (MCP)
  - MCP Server and Client
  - Building MCP Systems
- Advanced AI-Powered Business Projects

**Workflows:**

- `Agentic Framework Concepts.json`
- `Introduction to Model Context Protocol.json`
- `Introduction to Retrieval-Augmented Generation.json`

---

## Repository Structure

```
IEEE-HU-SIGHT-n8n-Course/
├── README.md
├── docs/
│   ├── n8n-Course-Outlines.md
│   ├── plan.txt
│   └── struct.txt
├── SessionOne/
│   ├── APIs/
│   │   ├── Curls.txt
│   │   ├── main.py
│   │   └── README.md
│   └── Workflows/
│       ├── APIs Deep Dive.json
│       ├── Basic Projects.json
│       ├── Core n8n Concepts.json
│       ├── Essential Triggers.json
│       ├── Fundamental Core Nodes.json
│       └── JSON and Data Flow in n8n.json
├── SessionTwo/
│   ├── Error Handling & Debugging.json
│   ├── Evolution API.json
│   ├── Introduction to webhooks.json
│   ├── JavaScript in n8n.json
│   ├── Project-1-OCR.json
│   ├── Project 2 Student Performance Tracker...json
│   ├── Setup Google Credentials.json
│   └── WhatsApp nightmare.json
├── SessionThree/
│   ├── frontend/
│   │   └── index.html
│   └── Workflows/
│       ├── AI Agent Fundamentals.json
│       ├── AI Core Nodes Introduction.json
│       ├── Introduction To Prompt Engineering.json
│       ├── project-1 -Automated-resume-scoring.json
│       └── simple agent example.json
└── SessionFour/
    ├── docs/
    │   └── MCP.md
    ├── frontend/
    │   ├── index.html
    │   └── static/
    └── Workflows/
        ├── Agentic Framework Concepts.json
        ├── Introduction to Model Context Protocol.json
        └── Introduction to Retrieval-Augmented Generation.json
```

---

## Prerequisites

- Basic computer literacy
- No prior programming experience required
- Willingness to learn by doing

---

## Installation Options Covered

1. **n8n Cloud** - Managed solution, quick start
2. **Docker Self-Hosted** - Full control, local development
3. **VPS with EasyPanel** - Production deployment

---

## Teaching Methodology

This course adopts a **learning-by-doing** approach:

- Emphasis on real execution rather than theory
- Continuous hands-on workflow building
- Concepts introduced inside real use cases
- Gradual increase in complexity
- Strong focus on understanding data flow and logic

---

## Projects Included

| Session   | Project                                      |
| --------- | -------------------------------------------- |
| Session 1 | Basic Automation Projects                    |
| Session 2 | OCR Automation & Student Performance Tracker |
| Session 3 | Automated Resume Scoring with AI             |
| Session 4 | Advanced AI-Powered Business Systems         |

---

## How to Use This Repository

1. Clone the repository
2. Import the `.json` workflow files into your n8n instance
3. Follow along with each session's materials
4. Practice by modifying and extending the workflows

---

## Resources

- [n8n Documentation](https://docs.n8n.io/)
- [n8n Community](https://community.n8n.io/)
- [n8n Cloud](https://n8n.io/cloud/)

---

## License

This course material is provided for educational purposes by IEEE HU SIGHT.

---

**Happy Automating!**

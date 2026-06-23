# 🩺 Physio AI Agent
### Microsoft Azure Frontier Girls Program 2025

AI agent developed during the **Azure Frontier Girls Program by Microsoft**, using **Azure AI Foundry** to simulate an intelligent physiotherapy triage assistant. The agent analyzes patient complaints, recommends appropriate specialist referrals, and automates email notifications for appointment scheduling.

---

## 📌 Project Overview

This project demonstrates the development and configuration of an AI agent in Azure AI Foundry, including:

- AI model deployment
- Agent creation and prompt engineering
- Knowledge base integration
- Testing with patient scenarios
- Tool and action configuration
- Email automation for specialist scheduling

---

## 🚀 Technologies Used

- Microsoft Azure AI Foundry
- Azure AI Agents
- Prompt Engineering
- Knowledge Base
- Actions & Tools
- Email Automation
- Generative AI

---

## 🏗️ Development Process

### 1. Environment Setup

- Created a Resource Group
- Created a Project and Hub in Azure AI Foundry
- Selected and deployed the AI model

### 2. Agent Creation

- Defined the agent instructions
- Added descriptions and behavioral guidelines
- Configured restrictions on topics and responses

### 3. Knowledge Integration

A knowledge file was uploaded so the agent could understand:

- Patient information
- Referral criteria for different physiotherapy specialties
- Contextual information to support decision-making

### 4. Testing and Prompt Engineering

Several tests were performed:

- Using only patient symptoms
- Comparing prompt information versus uploaded documents
- Evaluating the use of Tools and Knowledge sources
- Refining instructions to improve response quality

### 5. Action Configuration

An action was added to enable automatic email generation containing:

- Patient name
- Recommended specialty
- Scheduling information

Initially, the email failed because the sender address had not been provided in the prompt. After adjusting the input, the email was successfully sent.

---

## ⚙️ Agent Workflow

```text
Patient Complaint
        ↓
AI Agent Analysis
        ↓
Knowledge Base Consultation
        ↓
Specialty Recommendation
        ↓
Email Generation
        ↓
Appointment Request
```

---

## 🧠 Main Features

- ✔️ Analyze patient complaints
- ✔️ Use external knowledge files
- ✔️ Apply prompt engineering techniques
- ✔️ Recommend appropriate specialties
- ✔️ Prevent undesired content through instructions
- ✔️ Automate email generation
- ✔️ Test and debug agent behavior

---

## 📂 Architecture

```text
Azure AI Foundry
│
├── Model Deployment
├── AI Agent
│     ├── Instructions
│     ├── Description
│     ├── Tools
│     ├── Knowledge Base
│     └── Actions
│
└── Email Automation
```

---

## 📸 Project Stages

- Resource Group creation
- Project and Hub setup
- Model deployment
- Agent configuration
- Prompt engineering
- Knowledge upload
- Action creation
- Agent testing and debugging
- Email automation

---

## 🎓 About the Program

This project was developed as part of the **Azure Frontier Girls Program**, an initiative supported by Microsoft focused on empowering women in AI and cloud technologies through hands-on challenges and real-world applications.

---

## 📈 Learning Outcomes

Through this project, I gained practical experience with:

- ✔️ Azure AI Foundry
- ✔️ AI Agents
- ✔️ Prompt Engineering
- ✔️ Retrieval-Augmented Generation (RAG)
- ✔️ Knowledge integration
- ✔️ Agent Actions and Tools
- ✔️ Debugging and testing AI systems
- ✔️ Workflow automation

---

## 📄 License

This project was developed for educational purposes as part of the Microsoft Azure Frontier Girls Program.

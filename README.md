### OtariGuard FinOps
### Privacy-First AI Security Gateway for Intelligent Request Inspection, Threat Detection & Secure AI Model Routing

<p align="center">
  <strong>Securing AI interactions through intelligent inspection, privacy-first processing, and transparent model routing.</strong>
</p>

---

## 🌐 Overview

**OtariGuard FinOps** is a privacy-first AI Security Gateway designed to make AI interactions safer, more transparent, and cost-efficient.

As AI adoption increases, applications face growing risks from malicious prompts, sensitive data exposure, unauthorized requests, and inefficient AI model usage.

OtariGuard addresses these challenges through an intelligent security layer that inspects incoming requests, identifies potential threats, sanitizes suspicious inputs, and enables secure AI model routing.

Inspired by the principles of trusted and decentralized AI, the platform combines local AI processing, intelligent agents, Model Context Protocol (MCP), and real-time monitoring to create a transparent AI security ecosystem.

## 🎯 Problem Statement

AI-powered applications are increasingly vulnerable to:

- Prompt injection and malicious instructions.
- Sensitive information leakage.
- Untrusted external inputs.
- Uncontrolled AI model usage and costs.
- Lack of visibility into AI request processing.
- Insufficient monitoring of security-related events.

Traditional AI integrations often lack a dedicated security and transparency layer between users and AI models.

**OtariGuard introduces this missing layer.**

## 💡 Key Features

### 1. Intelligent Threat Detection
- Inspects incoming AI requests.
- Identifies potentially malicious prompts.
- Separates legitimate requests from suspicious inputs.
- Supports security-oriented request analysis.

### 2. Privacy-First Request Processing
- Provides a security layer for inspecting and sanitizing requests.
- Helps prevent sensitive information from being unnecessarily exposed.
- Supports local AI processing workflows.

### 3. Intelligent AI Model Routing
- Enables intelligent model selection based on request requirements.
- Supports cost-conscious AI processing.
- Records model selection and routing decisions.

### 4. Real-Time Transparency Dashboard
The dashboard provides visibility into the gateway's internal operations through:

- **Raw Ingest Logs:** Displays incoming requests before processing.
- **Sanitized Egress Logs:** Shows processed requests after security inspection.
- **System Event Journal:** Records security checks, routing decisions, and cache-related events.
- **Security Alerts:** Highlights potentially malicious prompts.
- **Hardware Status Footer:** Displays system resource information, including CPU, RAM, and disk I/O.

### 5. Agent-Based Architecture
- Integrates AI agents into the security workflow.
- Uses MCP-based components for structured tool communication.
- Supports modular and extensible processing components.

## 🏗️ System Architecture

OtariGuard follows a modular architecture consisting of:

1. **Request Ingestion Layer:** Receives incoming AI requests.
2. **Security Inspection Layer:** Analyses requests for suspicious patterns and potential threats.
3. **Sanitization Layer:** Processes requests before secure forwarding.
4. **Agent & MCP Layer:** Supports intelligent agent workflows and tool communication.
5. **AI Model Routing Layer:** Handles model selection and routing decisions.
6. **Monitoring & Transparency Layer:** Provides logs, system events, and operational visibility.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| Programming Language | Python |
| AI Integration | Local AI / AI Agents |
| Agent Communication | Model Context Protocol (MCP) |
| Backend Components | Python-based services |
| Version Control | Git & GitHub |

## 📂 Project Structure

```text
OtariGuard-FinOps/
│
├── any-agent/
├── encoderfile/
├── mcp_log_reader/
├── mcpd/
├── otari/
├── transparency_layer/
│
├── genetic_budget_engine.py
├── mock_log_generator.py
├── run_agent.py
├── server_telemetry.py
├── socket_bridge.py
├── test_mcp_locally.py
├── test_socket_conn.py
│
├── .gitignore
└── README.md
```

*Note: The structure above highlights the main folders and files identified in the project repository. Additional files and components may be present.*

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Node.js and npm
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/sanikapensalwar-hue/OtariGuard-FinOps.git
```

### 2. Navigate to the Project

```bash
cd OtariGuard-FinOps
```

### 3. Set Up the Frontend

```bash
cd transparency_layer
npm install
npm run dev
```

Open the local URL displayed in your terminal to access the dashboard.

### 4. Backend Setup

The Python-based backend and agent components have their own dependencies and execution entry points. Refer to their respective configuration files and source code for the required setup and execution commands.

*Add the verified backend startup command and dependency installation instructions here before publishing the final version.*

## 🔍 Security & Privacy

Security is central to the design of OtariGuard.

The project emphasizes:

- Request-level security inspection.
- Privacy-conscious processing.
- Separation of incoming and sanitized outgoing logs.
- Monitoring of security events.
- Local AI and modular agent workflows.

**Important:** This project is a security-oriented prototype. Its detection capabilities should be tested and independently validated before production deployment.

## 🚀 Future Scope

- Advanced prompt injection detection.
- More sophisticated AI threat classification.
- Expanded MCP tool integrations.
- Improved adaptive model routing.
- Detailed cost analytics and optimization.
- Enhanced real-time security monitoring.
- Scalable deployment across distributed AI environments.

## 👥 Team & Contributions

**Project:** OtariGuard FinOps  
**Event:** Hackathon

The project brings together AI security, intelligent agents, privacy-first processing, and transparent monitoring.

**My Contribution: Frontend Development & Transparency Dashboard**

- Developed the frontend using React, Vite, and Tailwind CSS.
- Implemented the transparency dashboard.
- Created separate Raw Ingest Logs and Sanitized Egress Logs panels.
- Added security alerts for suspicious prompts.
- Developed the System Event Journal to display processing and routing events.
- Added a Hardware Status Footer for system resource monitoring.

## System Architecture
  <img width="1316" height="843" alt="image" src="https://github.com/user-attachments/assets/f22b2bae-984e-4744-ab20-b6fb78853dcc" />


## 📌 Project Vision

Our vision is to make AI systems more trustworthy by introducing a transparent, privacy-first security layer between users and AI models.

**OtariGuard — Making AI interactions safer, smarter, and more transparent.**

---

⭐ If you find this project interesting, consider giving this repository a star!

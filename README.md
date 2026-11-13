# Multilingual Helpdesk Model Router Based on Cost, Latency and Privacy

## Project Information

**Project Title:** Multilingual Helpdesk Model Router Based on Cost, Latency and Privacy

**Branch:** CSE

**Academic Year:** 2026–2027

**Team ID:** To be updated

**Supervisor:** V. Anuraghavi

## Team Members

| S.No | Name | Student ID |
|---|---|---|
| 1 | T. Hasini | 2520030102 |
| 2 | U. Sri Laxmi | 2520030272 |
| 3 | Shankar | 2520030062 |

---

## Abstract

The Multilingual Helpdesk Model Router is an intelligent system designed to handle user queries in multiple languages by selecting the most suitable AI language model based on cost, response latency, and privacy requirements.

The system analyzes incoming user queries and routes them to an appropriate language model according to predefined decision criteria. It aims to reduce API usage costs, improve response speed, and protect sensitive user information.

The system supports multilingual communication, allowing users to interact with the helpdesk in their preferred language. It also monitors model performance, response time, and token usage to make efficient routing decisions.

This project provides a cost-effective, efficient, and privacy-aware AI-powered helpdesk solution for real-world customer support applications.

---

## Problem Statement

Traditional helpdesk systems often depend on a single AI model for processing all user queries. This can result in increased operational costs, higher response times, and potential privacy concerns.

There is a need for an intelligent routing mechanism that selects AI models dynamically based on query complexity, cost, latency, and privacy requirements while supporting multiple languages.

---

## Objectives

- Develop a multilingual AI-powered helpdesk system.
- Route user queries to suitable AI models.
- Minimize API and model execution costs.
- Reduce response latency.
- Protect sensitive user information.
- Monitor token usage and model performance.
- Provide an efficient and user-friendly chatbot interface.

---

## Key Features

1. **Multilingual Support:** Accepts and processes queries in multiple languages.
2. **Cost-Based Routing:** Selects models based on estimated processing cost.
3. **Latency-Based Routing:** Prioritizes models based on response time.
4. **Privacy-Aware Routing:** Identifies sensitive queries and applies suitable privacy rules.
5. **Intelligent Model Selection:** Dynamically selects an appropriate AI model.
6. **Performance Monitoring:** Tracks token usage, response time, and model selection.
7. **Chat Interface:** Allows users to interact with the helpdesk easily.

---

## Technologies Used

| Component | Technology |
|---|---|
| Programming Language | Python |
| Frontend | Streamlit |
| Backend | Python |
| Database | MongoDB |
| AI/LLM Integration | Ollama / OpenAI API |
| Model Routing | Rule-Based Routing |
| Development Environment | Visual Studio Code |
| Version Control | Git and GitHub |

*Technologies may be updated as the project develops.*

---

## System Workflow

1. User enters a query in their preferred language.
2. The system receives and analyzes the query.
3. The query is evaluated based on cost, latency, and privacy requirements.
4. The routing mechanism selects a suitable AI model.
5. The selected model generates a response.
6. The response is displayed to the user.
7. Model usage, token count, and response time are recorded for performance monitoring.

---

## Project Folder Structure

```text
Multilingual-Helpdesk-Model-Router/
│
├── src/
│   ├── app.py
│   ├── router.py
│   ├── model_handler.py
│   ├── language_handler.py
│   └── privacy_handler.py
│
├── docs/
│   ├── project_proposal.pdf
│   └── system_architecture.pdf
│
├── data/
│   └── README.md
│
├── results/
│   └── README.md
│
├── reports/
│   └── README.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

### 2. Navigate to the Project Directory

```bash
cd Multilingual-Helpdesk-Model-Router
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Virtual Environment

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure Environment Variables

Create a `.env` file for API credentials and configuration.

Never upload API keys, passwords, or confidential information to GitHub.

---

## Execution Instructions

Run the application using:

```bash
streamlit run src/app.py
```

Open the local URL displayed in the terminal to access the chatbot interface.

---

## Expected Results

- Users can communicate with the chatbot in multiple languages.
- The system selects suitable AI models based on routing criteria.
- API usage costs are monitored and optimized.
- Response latency is measured and compared.
- Privacy-sensitive queries are handled according to configured privacy policies.
- Performance information is stored for analysis.

---

## Project Phase Status

**Current Status:** Initial Development Phase

| Phase | Description | Status |
|---|---|---|
| Phase 1 | Problem Identification and Project Planning | In Progress |
| Phase 2 | System Design and Architecture | Pending |
| Phase 3 | Model Integration and Development | Pending |
| Phase 4 | Testing and Performance Evaluation | Pending |
| Phase 5 | Final Implementation and Documentation | Pending |

---

## GitHub Contribution Guidelines

- Every team member must contribute using their individual GitHub account.
- Each team must make at least one meaningful commit every week.
- All major phase deliverables must be tagged.
- Suggested tags: `review-1`, `review-2`, and `final`.
- The repository must be accessible to the supervisor and Course Coordinator.
- API keys, passwords, and confidential information must never be uploaded.

---

## Future Enhancements

- Add support for more regional and international languages.
- Implement advanced AI-based routing strategies.
- Introduce real-time cost and latency dashboards.
- Improve privacy protection through data masking.
- Integrate additional open-source and commercial language models.
- Deploy the system to a cloud platform.

---

## Supervisor

**K. Anuraghavi**

## Team

**Multilingual Helpdesk Model Router Development Team**

**Academic Year: 2026–2027**

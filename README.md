# Multi Model AI Sales Agent

An intelligent, multi-model AI Sales Agent that automates lead generation, tool research, and cold outreach using state-of-the-art AI APIs and SMTP communication. This project leverages Gemini, DeepSeek, Groq, and OpenAI SDK Agents to create a highly efficient and modular sales assistant powered by traceable decision-making.

## 🚀 Features
Multi-Model Reasoning: Combines responses from Gemini, DeepSeek, and Groq APIs to analyze developer tools, optimize messages, and suggest high-conversion strategies.

OpenAI SDK Agents Integration: Utilizes OpenAI's SDK agents with built-in tracing and reasoning pathways for transparent, interpretable AI decisions.

SMTP-Based Cold Emailing: Uses Python's smtplib and SendGrid-compatible setup for sending cold emails directly to prospective clients.

Tool Research: AI-powered investigation of emerging developer tools, libraries, and platforms tailored for specific client needs.

Lead Interaction: Drafts personalized messages, follow-ups, and replies intelligently using context-aware AI reasoning.

Trace Logs: Auto-generated traces from OpenAI SDK agents for debugging, audit, or transparency in communication.


## 🧩 Tech Stack
| Tech            | Purpose                                 |
| --------------- | --------------------------------------- |
| Gemini API      | General-purpose large language model    |
| DeepSeek API    | Developer-tool-focused code reasoning   |
| Groq API        | High-performance token generation       |
| OpenAI SDK      | Agent-based orchestration + tracing     |
| SMTP (SendGrid) | Cold email sending via SMTP protocol    |
| Python          | Core implementation in Jupyter Notebook |

## 📁 File Structure
Multi_Model_AI_Sales_Agent/  
│  
├── *Multi_Model_AI_Sales_Agent.ipynb*        # Main notebook containing logic and implementation  
├── *requirements.txt*                      # Python dependencies  
├── *.env*                                  # Environment variables (API keys, email credentials)  
├── *README.md*                             # Project overview (this file)  


## ⚙️ Setup Instructions

1. Clone the repository:
```
git clone https://github.com/danish0511/Multi-Model-AI-Sales-Agent.git
cd Multi-Model-AI-Sales-Agent
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Set up your environment:
Create a .env file in the root directory with the following keys:
```
OPENAI_API_KEY=
GEMINI_API_KEY=
GROQ_API_KEY=
DEEPSEEK_API_KEY=
EMAIL_APP_PASSWORD=
SENDGRID_API_KEY= # optional
```

## 🧠 How It Works
1. User Prompt → Triggers multi-agent AI response.

2. Agents → Each model (Gemini, DeepSeek, Groq) is queried for perspectives.

3. OpenAI Agent SDK → Orchestrates final decision and explanation with tracing.

4. Email Drafting → Message is composed based on AI consensus.

5. SMTP Mailer → Sends email to the provided address.

## 📊 Example Use Cases
* Developer tools market research

* Automated B2B outreach

* Technical sales engagement

* Startup outreach and networking

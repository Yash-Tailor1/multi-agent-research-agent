# 🔬 Multi-Agent Research System

### An AI-Powered Research Assistant Using Multi-Agent Architecture

Multi-Agent Research System is an AI-powered application designed to automate research by coordinating multiple specialized AI agents. It combines large language models and research tools to process queries, gather information, and generate structured research results.

The project explores how multi-agent workflows can improve research automation, task coordination, and AI-assisted information gathering.

## 🌐 Live Demo

**Try the application here:** [Multi-Agent Research System](https://multi-agent-research-system-jbgpuq7j5urqvpobxnp7ua.streamlit.app/)

Explore the deployed application to experience the AI-powered research workflow and live agent status updates.

## ✨ Features

- **Multi-Agent Architecture** — Organizes research tasks through specialized AI agents.
- **Automated Research Workflow** — Processes user queries through a coordinated research pipeline.
- **Live Agent Status** — Displays agent progress to provide visibility into the research process.
- **LLM Integration** — Uses Groq-powered language models for AI-driven processing.
- **Token Usage Optimization** — Implements optimizations to reduce unnecessary LLM token consumption.
- **Research Tools** — Integrates tools that support the research workflow.
- **Research History** — Includes a history module for managing research-related records.
- **Modular Python Codebase** — Separates agents, tools, pipeline logic, application handling, and history management.

## 🏗️ Project Architecture

The application is organized into modular components, each responsible for a specific part of the research workflow.

```text
multi-agent-research-system/
│
├── agents.py         # AI agent definitions and behavior
├── app.py            # Application entry point and interface
├── pipeline.py       # Research workflow orchestration
├── tools.py          # Research tools and utilities
├── history.py        # Research history management
├── requirements.txt  # Python dependencies
├── .gitignore        # Git ignore rules
└── README.md         # Project documentation
```

### Research Workflow

1. **User Query** — The user submits a research question or topic.
2. **Task Processing** — The application processes the request and initiates the research workflow.
3. **Agent Execution** — Specialized agents perform their assigned tasks.
4. **Research Coordination** — The pipeline coordinates the different stages of the workflow.
5. **Result Generation** — The system produces research output based on the processing performed.
6. **History Management** — Research-related history is handled by the history module.

## 🛠️ Technology Stack

- **Python** — Core application development
- **Groq API** — LLM inference
- **Multi-Agent Systems** — Coordinated AI task execution
- **LLM Tools** — Tool-assisted research workflows
- **Git & GitHub** — Version control and project management

## 🚀 Getting Started

### Prerequisites

Before running the application, ensure you have:

- Python installed
- Git installed
- A Groq API key
- Access to any additional APIs required by your configured research tools

### 1. Clone the Repository

```bash
git clone https://github.com/Yash-Tailor1/multi-agent-research-system.git
cd multi-agent-research-system
```

### 2. Create a Virtual Environment

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root and add your Groq API key.

```env
GROQ_API_KEY=your_groq_api_key_here
```

Replace the placeholder with your actual API key. Never commit your `.env` file or expose API credentials in your source code.

If your implementation uses additional API keys, configure those according to the requirements in `tools.py` and the application code.

### 5. Run the Application

```bash
python app.py
```

Follow the application's interface and prompts to start a research task.

> **Note:** The exact startup command and required environment variables depend on the implementation in `app.py` and `requirements.txt`.

## 📂 Core Modules

| File | Responsibility |
|---|---|
| `agents.py` | Defines the AI agents and their behavior. |
| `app.py` | Provides the application entry point and user interaction. |
| `pipeline.py` | Coordinates the research workflow and agent execution. |
| `tools.py` | Contains tools and utilities used during research. |
| `history.py` | Handles research history functionality. |
| `requirements.txt` | Lists the project's Python dependencies. |

## 🎯 Project Goals

The project focuses on exploring practical applications of agentic AI, including:

- Automating multi-step research tasks.
- Coordinating specialized AI agents.
- Improving visibility into agent execution.
- Optimizing LLM token consumption.
- Building modular and maintainable AI applications.

## 🔮 Future Enhancements

Potential improvements include:

- Streaming research results as they are generated.
- More detailed agent execution logs and observability.
- Research citations and source verification.
- Persistent research history and session management.
- Configurable models and LLM providers.
- Improved error handling, retries, and evaluation.
- Exporting research reports to Markdown or PDF.

## 🔐 Security

- Store API keys in environment variables.
- Keep `.env` files out of version control.
- Avoid logging API credentials or other sensitive information.
- Apply appropriate rate limits and error handling when calling external APIs.

## 👨‍💻 Author

**Yash Tailor**

AI Engineer | Agentic AI | LLM Applications

GitHub: [@Yash-Tailor1](https://github.com/Yash-Tailor1)

## 📄 License

No license has been specified yet. If you intend to make this project available for reuse, consider adding an appropriate open-source license.

---

*Built to explore multi-agent AI systems, automated research workflows, and efficient LLM-powered applications.*

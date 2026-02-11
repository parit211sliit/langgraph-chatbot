🚀 LangGraph Chatbot – Agentic AI Workflow System
📌 Overview

This project demonstrates how to build Agentic AI systems using LangGraph.
It covers graph-based LLM workflows, tool-calling agents, memory integration, tracing, and Human-in-the-Loop (HITL) mechanisms.

The repository is structured as a step-by-step progression from basic graph workflows to advanced AI agent architecture.

This project showcases practical implementation of modern LLM orchestration techniques used in production AI systems.

🧠 Key Features

✅ Graph-based LLM workflow design

✅ Conditional routing logic

✅ Chatbot built using LangGraph

✅ Tool-calling agent architecture

✅ Memory-enabled AI interactions

✅ LangSmith tracing & monitoring

✅ Human-in-the-Loop (HITL) validation

✅ Modular and extensible design

| File                           | Description                   |
| ------------------------------ | ----------------------------- |
| `1_simple_graph.ipynb`         | Basic LangGraph workflow      |
| `2_graph_with_condition.ipynb` | Conditional graph routing     |
| `3_chatbot.ipynb`              | LangGraph-based chatbot       |
| `4_tool_call.ipynb`            | Tool integration with LLM     |
| `5_tool_call_agent.ipynb`      | Tool-calling agent system     |
| `6_memory.ipynb`               | Memory-enabled chatbot        |
| `7_langsmith_tracing.ipynb`    | Observability using LangSmith |
| `HITL.py`                      | Human-in-the-Loop system      |
| `main.py`                      | Application entry point       |
| `pyproject.toml`               | Dependency configuration      |

🏗️ Architecture Overview

The system follows an Agentic Workflow Model:

User Input
→ Graph Router
→ LLM Node
→ Tool Execution (if required)
→ Memory Update
→ Human Validation (optional)
→ Final Response

This architecture ensures structured reasoning, traceability, and scalable AI system design.

🛠️ Tech Stack

Python

LangGraph

LangChain

OpenAI API

LangSmith

Jupyter Notebook

📊 Learning Outcomes

Through this project, you will understand:

How to design graph-based AI workflows

How to build tool-aware LLM agents

How to integrate memory into AI systems

How to implement observability with LangSmith

How to add Human-in-the-Loop validation

How modern Agentic AI systems are structured

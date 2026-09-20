# 🤖 Agents Playground

A hands-on playground for learning and experimenting with **LLM agents, agentic workflows, ReAct, and multi-agent systems** using different frameworks.

The repository contains practical examples developed while exploring how modern AI agents are designed, orchestrated, and implemented with Python.

## 📚 Contents

The repository currently includes examples covering different approaches to building AI agents:

### 🔹 LangChain Agent

`Agent_LangChain.ipynb`

Introduction to building an agent with **LangChain**, including:

* LLM-based agents
* Tools
* Agent execution
* Tool calling
* Agent interaction with external capabilities

### 🔹 ReAct Agent

`Agent_ReAct.ipynb`

Implementation and exploration of the **ReAct (Reasoning + Acting)** paradigm.

The notebook demonstrates how an agent can:

1. Analyze a task
2. Decide which action to take
3. Use a tool
4. Observe the result
5. Continue reasoning based on the observation
6. Produce a final answer

### 🔹 Multi-Agent Systems with CrewAI

`MultiAgents_CrewAI.ipynb`

Introduction to **multi-agent architectures** using CrewAI.

The example explores how multiple specialized agents can collaborate through:

* Agents with different roles
* Tasks
* Agent delegation
* Sequential workflows
* Multi-agent orchestration

## 🧠 Concepts Explored

This playground is focused on understanding the concepts behind agentic AI systems rather than simply using a framework.

Some of the main topics explored are:

* **LLMs and tool calling**
* **AI Agents**
* **ReAct**
* **Reasoning and Acting**
* **Agent memory and state**
* **Tool use**
* **Agent orchestration**
* **Multi-agent systems**
* **Agent specialization**
* **Sequential and hierarchical workflows**
* **Framework comparison**

## 🛠️ Frameworks

The examples currently explore:

| Framework                               | Focus                                |
| --------------------------------------- | ------------------------------------ |
| [LangChain](https://www.langchain.com/) | Building LLM applications and agents |
| [CrewAI](https://www.crewai.com/)       | Multi-agent orchestration            |
| ReAct                                   | Reasoning + Acting agent pattern     |

The goal is to experiment with different abstractions and understand the trade-offs between frameworks and architectural approaches.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/data-datum/agents_playground.git
cd agents_playground
```

Install the required dependencies according to the notebooks you want to run.

The notebooks can be opened with **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.

```bash
jupyter notebook
```

## 🔑 Environment Variables

Some examples require API access to an LLM provider.

Create a `.env` file and add the required credentials, for example:

```env
OPENROUTER_API_KEY=your_api_key
```

> Never commit API keys or other secrets to the repository.

## 🎯 Purpose

This repository is part of an ongoing exploration of **Generative AI and Agentic AI**, with a particular focus on understanding how LLMs evolve from simple chat interfaces into systems capable of:

**Reasoning → Planning → Using Tools → Observing Results → Taking Further Actions**

The playground is intentionally experimental and educational. Examples may evolve as new agent frameworks, models, and orchestration patterns are explored.

## 🗺️ Roadmap

Possible future experiments include:

* [ ] LangGraph agents
* [ ] Supervisor-based multi-agent architectures
* [ ] Agent state and persistence
* [ ] Memory systems
* [ ] Structured outputs
* [ ] MCP (Model Context Protocol)
* [ ] Agent evaluation
* [ ] Human-in-the-loop workflows
* [ ] Parallel agent execution
* [ ] Different LLMs and model routing
* [ ] Comparison of agent frameworks
* [ ] Production-oriented agent architectures

## 📖 Learning Approach

The repository follows a progression from simpler to more complex architectures:

```text
LLM
 │
 ▼
LLM + Tools
 │
 ▼
Agent
 │
 ▼
ReAct Agent
 │
 ▼
Multi-Agent System
 │
 ▼
Agent Orchestration
 │
 ▼
Advanced Agentic Systems
```

Each notebook is intended to be both an experiment and a learning resource.

## 📄 License

This project is licensed under the MIT License.


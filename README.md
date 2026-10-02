# 🤖 Agents Playground

A hands-on repository exploring **LLM agents, tool integration, multi-agent systems, and agent orchestration** using Python and different frameworks.

The goal of this project is to understand how agentic systems work under the hood, experiment with different architectural patterns, and explore the trade-offs between frameworks and implementation approaches.

Rather than focusing on a single framework, this playground follows a progressive, practical approach — from building basic LLM agents to exploring multi-agent architectures, tool interoperability, and more advanced agentic workflows.

## 📚 Notebooks

The repository is organized into Jupyter notebooks, each exploring a specific concept or architectural approach.

| Notebook                                                   | Description                                                                                                                              | Key concepts                                                         |
| ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [Agent_LangChain.ipynb](Agent_LangChain.ipynb)             | Introduction to building LLM agents with LangChain. Explores how language models interact with tools and execute actions.                | LLM agents, tool calling, agent execution                            |
| [Agent_ReAct.ipynb](Agent_ReAct.ipynb)                     | Implements the ReAct (Reasoning + Acting) paradigm, illustrating the iterative interaction between reasoning, actions, and observations. | ReAct, reasoning and acting, agent loops                             |
| [MultiAgents_CrewAI.ipynb](MultiAgents_CrewAI.ipynb)       | Explores multi-agent systems with CrewAI, using specialized agents that collaborate to complete tasks.                                   | Agent roles, tasks, delegation, sequential workflows                 |
| [MultiAgents_LangGraph.ipynb](MultiAgents_LangGraph.ipynb) | Experiments with multi-agent orchestration and graph-based workflows using LangGraph.                                                    | Graph-based orchestration, routing, state, agent coordination        |
| [Tools_MCP.ipynb](Tools_MCP.ipynb)                         | Explores tool integration and the Model Context Protocol (MCP), including how agents can discover and use external capabilities.         | Custom tools, MCP, client-server architecture, tool interoperability |

## 🧠 Concepts Explored

This repository investigates several fundamental building blocks of agentic AI systems:

* **LLM Agents:** Connecting language models with tools and execution loops.
* **ReAct:** Combining reasoning and acting through iterative interaction.
* **Tool Calling:** Enabling LLMs to interact with external functions and services.
* **Model Context Protocol (MCP):** Exploring a standardized way to expose and consume tools and other contextual capabilities.
* **Multi-Agent Systems:** Designing systems where specialized agents collaborate on complex tasks.
* **Agent Orchestration:** Coordinating agents, managing execution flows, and exploring graph-based architectures.
* **State and Memory:** Understanding how agentic applications maintain context and manage information across interactions.
* **Framework Comparison:** Exploring different abstractions and architectural trade-offs across agent frameworks.

## 🛠️ Frameworks and Technologies

| Framework / Technology | Focus                                                              |
| ---------------------- | ------------------------------------------------------------------ |
| **LangChain**          | Building LLM applications, agents, and tool integrations           |
| **CrewAI**             | Multi-agent collaboration and task orchestration                   |
| **LangGraph**          | Stateful, graph-based agent workflows and orchestration            |
| **MCP**                | Standardized communication between applications and external tools |
| **Python**             | Implementation and experimentation                                 |
| **Jupyter Notebooks**  | Interactive learning and prototyping                               |

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/data-datum/agents_playground.git
cd agents_playground
```

### Set up the environment

Create a virtual environment and install the dependencies required by the notebook you want to run.

```bash
python -m venv .venv
```

Activate the environment:

```bash
# Linux / macOS
source .venv/bin/activate

# Windows
.venv\Scripts\activate
```

Install the relevant packages according to each notebook's requirements.

### Configure API keys

Some notebooks require access to an LLM provider.

Create a `.env` file in the project directory and add the credentials required by your chosen provider.

```env
OPENROUTER_API_KEY=your_api_key
```

Never commit API keys or other sensitive credentials to the repository.

### Run the notebooks

Open the notebooks using Jupyter Notebook, JupyterLab, or Google Colab.

```bash
jupyter notebook
```

Each notebook is designed to be explored independently, although following the suggested learning progression can provide a more structured understanding of agentic systems.

## 🗺️ Learning Path

The notebooks explore different levels of abstraction and complexity in agentic systems.

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
ReAct
 │
 ▼
Tool Integration and MCP
 │
 ▼
Multi-Agent Systems
 │
 ▼
Agent Orchestration
 │
 ▼
Advanced Agentic Workflows
```

This progression is conceptual rather than strictly linear. Tool integration, orchestration, and multi-agent architectures can be combined in different ways depending on the application.

## 🔬 Project Scope

This is an ongoing educational and experimental project focused on understanding the principles behind agentic AI.

The notebooks prioritize hands-on implementation and conceptual exploration over production-ready solutions.

The main objectives are to:

* Understand the internal mechanisms behind LLM-based agents.
* Explore how agents interact with tools and external systems.
* Compare different approaches to multi-agent collaboration and orchestration.
* Experiment with emerging protocols and frameworks.
* Build a foundation for more advanced applications involving retrieval, memory, evaluation, and autonomous workflows.

## 🛣️ Roadmap

Future experiments may include:

* [ ] RAG-based agents
* [ ] Agent memory and persistent state
* [ ] Supervisor-based multi-agent architectures
* [ ] Structured outputs and constrained generation
* [ ] Agent evaluation and observability
* [ ] Human-in-the-loop workflows
* [ ] Parallel execution and advanced routing
* [ ] Model selection and routing strategies
* [ ] Production-oriented agent architectures

## 📄 License

This project is licensed under the MIT License.


## 📄 License

This project is licensed under the MIT License.


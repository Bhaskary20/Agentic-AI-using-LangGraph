# Agentic AI using LangGraph

Explore a collection of Jupyter Notebooks demonstrating how to leverage **LangGraph** to build agentic AI workflows—with rich examples like conditional logic, parallel execution, prompt chaining, iterative reasoning, and integrations with language models.

---

##  Repository Contents

| Filename                         | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| `1_bmi_workflow.ipynb`           | BMI calculator workflow—showcases decision-making based on health metrics. |
| `2_llm_workflow.ipynb`           | LLM-driven single-step workflow using LangGraph.                           |
| `3_prompt_chaining.ipynb`        | Demonstrates chaining prompts across connected graph nodes.                |
| `4_parallel_workflow.ipynb`      | Executes multiple branches in parallel.                                    |
| `5_parallel_workflow_llm.ipynb`  | Parallel execution with LLM components in each branch.                     |
| `6_conditional_workflow.ipynb`   | Graph-based conditional branching logic.                                   |
| `7_conditional_workflow_llm.ipynb` | Conditional branching enriched with LLM outputs.                          |
| `8_iterative_workflows.ipynb`    | Illustrates feedback loops and iterative behavior using LangGraph.         |

---

##  What is LangGraph?

**LangGraph** is a graph-based orchestration framework built on **LangChain**, designed to manage structured and stateful AI agent workflows. It enables developers to:

- Connect **nodes** (tasks, LLM calls, computations) using **edges**.
- Maintain and update **state** across workflow steps.
- Create branching logic, loops, human-in-the-loop checkpoints, and streaming workflows.  
:contentReference[oaicite:0]{index=0}

LangGraph extends LangChain by offering a low-level, graph-centric engine that boosts modularity and control in building agentic systems.  
:contentReference[oaicite:1]{index=1}

---

##  Why This Repository Matters

This repo serves as a hands-on playground for learning and experimenting with LangGraph through Jupyter notebooks. Use cases covered include:

- **BMI Workflow**: Demonstrates decision branching based on computed values.
- **Prompt Chaining**: Builds sequential logic using agent prompts.
- **Parallel Workflows**: Splits tasks into concurrent branches.
- **Conditional Logic**: Executes tasks based on dynamic state evaluation.
- **Iterative Workflows**: Implements feedback loops and revisits tasks as needed.
- **LLM Enhancements**: Shows how to layer LLM-driven logic into conditional and parallel structures.

---

##  Prerequisites

Before running the notebooks, ensure you have:

- Python 3.8+ installed
- Jupyter notebook environment (e.g., Jupyter Lab, Jupyter Notebook)
- Installed dependencies—such as:
  ```bash
  pip install langgraph langchain

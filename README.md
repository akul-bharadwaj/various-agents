# Various Agents

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![OpenAI API](https://img.shields.io/badge/OpenAI-API-412991)](https://developers.openai.com/)
[![LangChain](https://img.shields.io/badge/LangChain-Agentic_AI-1C3C3C)](https://www.langchain.com/)
[![LangGraph](https://img.shields.io/badge/LangGraph-Stateful_Workflows-1C3C3C)](https://www.langchain.com/langgraph)
[![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)

A collection of **10 hands-on Jupyter/Google Colab notebooks** exploring agentic AI patterns with Python, the OpenAI API, LangChain, and LangGraph as part of EPGP - Applied AI and Agentic AI from IIITB & UpGrad.

The repository moves from basic agent loops and tool calling to stateful graphs, reflection, self-consistency, multi-agent orchestration, schema validation, ReAct execution, and multimodal insurance workflows.

## What this repository covers

- Agent loops: observe, reason, act, update, and repeat
- State persistence and transition logging
- Tool calling and dynamic tool selection
- Pydantic input/output schema validation
- Termination conditions and infinite-loop prevention
- Self-consistency, majority voting, and reflection
- ReAct-style Thought–Action–Observation execution
- Multi-agent orchestration with LangGraph
- CSV/data-analysis agents
- Multimodal insurance-claim processing
- Failure demonstrations and safety safeguards

## Standalone Agent Examples

| Notebook | What it demonstrates | Main stack | Run |
|---|---|---|---|
| [CSV Agent](https://github.com/akul-bharadwaj/various-agents/blob/main/CSV_Agent.ipynb) | Natural-language analysis of sales data through a LangChain CSV/Python agent. | LangChain, OpenAI, pandas | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/CSV_Agent.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Tool Calling Agent](https://github.com/akul-bharadwaj/various-agents/blob/main/Tool_Agent.ipynb) | Dynamic orchestration of employee-performance, salary-gap, and improvement-plan tools. | LangChain, OpenAI, custom tools | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Tool_Agent.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Motor Insurance Claim Processing — Multimodal](https://github.com/akul-bharadwaj/various-agents/blob/main/Motor_Insurance_Claim_Processing_with_Multi_Agents_%28Multimodal%29.ipynb) | A multi-agent claim workflow that evaluates policy, incident, and inspection information before producing a decision. | OpenAI, multimodal AI | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Motor_Insurance_Claim_Processing_with_Multi_Agents_%28Multimodal%29.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Insurance Claim Processing — Multi-Agent](https://github.com/akul-bharadwaj/various-agents/blob/main/Insurance_Claim_Processing_Multi_Agents_with_LangGraph.ipynb) | A multimodal extension of insurance-claim processing using vehicle-damage evidence and specialised agents. | LangGraph, OpenAI, multi-agent workflow | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Insurance_Claim_Processing_Multi_Agents_with_LangGraph.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

## Agentic Systems Case Studies

| Notebook | What it demonstrates | Main stack | Run |
|---|---|---|---|
| [Case Study 1 — Basic Agentic System](https://github.com/akul-bharadwaj/various-agents/blob/main/Case_Study_1_Basic_Agentic_System_Fintech_Loan_Advisor.ipynb) | Framework-free Observe–Reason–Act–Update loop for a mock fintech loan advisor. | OpenAI API, Python | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Case_Study_1_Basic_Agentic_System_Fintech_Loan_Advisor.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Case Study 2 — State Management](https://github.com/akul-bharadwaj/various-agents/blob/main/Case_Study_2_Wealth_Management_State_Agent.ipynb) | Persistent agent state, transition logging, resumability, and a stateless failure demonstration. | OpenAI API, Python, Pydantic | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Case_Study_2_Wealth_Management_State_Agent.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Case Study 3 — Termination and Loop Prevention](https://github.com/akul-bharadwaj/various-agents/blob/main/Case_Study_3_LangGraph_Trading_Agent_Termination.ipynb) | Cyclic trading workflow with confidence, iteration, no-progress, API-error, and recursion safeguards. | LangGraph, LangChain OpenAI | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Case_Study_3_LangGraph_Trading_Agent_Termination.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Case Study 4 — Self-Consistency and Reflection](https://github.com/akul-bharadwaj/various-agents/blob/main/Case_Study_4_LangGraph_Healthcare_Self_Consistency_Reflection.ipynb) | Three independent diagnostic candidates, majority voting, bounded reflection, and stability tracking. | LangGraph, OpenAI, Pydantic | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Case_Study_4_LangGraph_Healthcare_Self_Consistency_Reflection.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Case Study 5 — Tool Integration and Validation](https://github.com/akul-bharadwaj/various-agents/blob/main/Case_Study_5_LangChain_Banking_Tools_Schema_Validation.ipynb) | Dynamic banking-tool selection with strict input/output schemas and structured failure handling. | LangChain, OpenAI, Pydantic | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Case_Study_5_LangChain_Banking_Tools_Schema_Validation.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| [Case Study 6 — ReAct Agent](https://github.com/akul-bharadwaj/various-agents/blob/main/Case_Study_6_LangChain_ReAct_Financial_Assistant.ipynb) | Manual Thought–Action–Observation loop with financial tools and a long-planning limitation demo. | LangChain, OpenAI, Pydantic | <a href="https://colab.research.google.com/github/akul-bharadwaj/various-agents/blob/main/Case_Study_6_LangChain_ReAct_Financial_Assistant.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

## Learning progression

The six case studies form a progressive sequence:

```text
Basic agent loop
      ↓
Persistent state
      ↓
Termination and loop safety
      ↓
Self-consistency and reflection
      ↓
Validated tool integration
      ↓
ReAct reasoning and action
```

The additional notebooks extend these ideas into CSV analytics, multi-tool orchestration, multi-agent insurance processing, and multimodal claim assessment.

## Repository structure

```text
various-agents/
├── CSV_Agent.ipynb
├── Tool_Agent.ipynb
├── Insurance_Claim_Processing_Multi_Agents_with_LangGraph.ipynb
├── Motor_Insurance_Claim_Processing_with_Multi_Agents_(Multimodal).ipynb
├── Case_Study_1_Basic_Agentic_System_Fintech_Loan_Advisor.ipynb
├── Case_Study_2_Wealth_Management_State_Agent.ipynb
├── Case_Study_3_LangGraph_Trading_Agent_Termination.ipynb
├── Case_Study_4_LangGraph_Healthcare_Self_Consistency_Reflection.ipynb
├── Case_Study_5_LangChain_Banking_Tools_Schema_Validation.ipynb
├── Case_Study_6_LangChain_ReAct_Financial_Assistant.ipynb
└── README.md
```

## Getting started

### Recommended: Google Colab

Use the **Open in Colab** badge beside any notebook.

1. Open the notebook in Colab.
2. Run the dependency-installation cell.
3. Enter your OpenAI API key when prompted.
4. Run the remaining cells in sequence.

Each notebook is designed to be reasonably self-contained.

> Use a **fresh Colab runtime for each notebook**. Some notebooks intentionally use different LangChain/LangGraph versions or dependencies, and running them all in one environment may produce version conflicts.

### Local setup

```bash
git clone https://github.com/akul-bharadwaj/various-agents.git
cd various-agents

python -m venv .venv
source .venv/bin/activate       # macOS/Linux
# .venv\Scripts\activate      # Windows

pip install jupyterlab
jupyter lab
```

Install the packages listed in the selected notebook before running it.

## API-key setup

The notebooks request the key through `getpass`:

```python
import os
from getpass import getpass

os.environ["OPENAI_API_KEY"] = getpass(
    "Enter OpenAI API key: "
)
```

Do not hard-code API keys in notebooks, commit them to GitHub, or include them in cell outputs.

## Important security note

`CSV_Agent.ipynb` uses a Python-execution-capable CSV agent. Such agents can execute generated Python code.

- Use only trusted CSV files.
- Review generated operations.
- Run the notebook in an isolated environment.
- Do not expose sensitive local files or credentials.

## Design principles demonstrated

### Explicit state

Agent state is represented using dictionaries, dataclasses, or typed graph state rather than relying on the model to remember information implicitly.

### Deterministic safeguards

Consequential calculations, validation rules, iteration budgets, and stop conditions are implemented in Python whenever possible.

### Structured tool boundaries

Pydantic schemas validate model-generated tool arguments and tool outputs before results are returned to the agent.

### Traceability

The notebooks expose action logs, state transitions, tool observations, termination reasons, and comparison tables to make agent behaviour inspectable.

### Bounded autonomy

Loops use safeguards such as maximum iterations, maximum reflection rounds, duplicate-call prevention, recursion limits, and error budgets.

## Educational and domain disclaimers

These notebooks are software-engineering demonstrations using fictional or mock data.

- Financial and banking outputs are not financial advice, lending decisions, or eligibility assessments.
- Healthcare outputs are not diagnoses or treatment recommendations.
- Insurance outputs are not real claim decisions.
- Market data and expected-return ranges are illustrative rather than forecasts.
- Production systems require domain validation, security, privacy controls, monitoring, and qualified human oversight.

## Notes

- Model availability, pricing, and API behaviour may change over time.
- A notebook may require small updates when upstream libraries introduce breaking changes.
- The notebooks prioritise clarity and learning over production deployment.
- OpenAI API usage may incur charges.

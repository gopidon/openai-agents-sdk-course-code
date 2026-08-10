# OpenAI Agents SDK — Course Notebooks

This repository contains the notebooks for the Udemy course:
**"OpenAI Agents SDK: Build Multi-Agent AI Systems in Python"**

---

## How to Use

Each notebook is self-contained. Click the **Open in Colab** button for the
lecture you are working on. No local setup required.

Some lectures include both a **Starter** and a **Solution** notebook — start
with the Starter version and code along with the lecture, then compare
against the Solution if you get stuck.

> 📌 Lectures not listed in the tables below are concept-only (slides, no
> notebook). The numbering gaps you see are intentional, not missing files.

---

## Section 01 — Introduction & Setup

*Lectures 1.1–1.4 are concept-only (slides, no notebook). Lecture 1.8
is an orientation lecture with no notebook of its own — it walks through
the notebooks already listed below.*

| Lecture | Notebook |
|---|---|
| 1.5 — Environment Setup: Python, API Key, pip install openai-agents | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-01-introduction-and-setup/1.5-environment-setup.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 1.6 — Your First Agent: Hello World in 10 Lines — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-01-introduction-and-setup/1.6-first-agent-hello-world-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 1.6 — Your First Agent: Hello World in 10 Lines — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-01-introduction-and-setup/1.6-first-agent-hello-world-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 1.7 — Reading a RunResult: final_output, last_agent, usage | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-01-introduction-and-setup/1.7-reading-a-runresult.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

**Companion guide:** [Getting Your OpenAI API Key and Setting Up Billing](section-01-introduction-and-setup/1.5-api-key-and-billing-setup-guide.md) — a step-by-step walkthrough for Lecture 1.5, including the account setup, key generation, and the two-step billing process most people miss.

---

## Section 02 — Agent Configuration & Behaviour

| Lecture | Notebook |
|---|---|
| 2.1 — Agent Anatomy: Name, Instructions, Model, Tools, Handoffs, Guardrails — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.1-agent-anatomy-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.1 — Agent Anatomy: Name, Instructions, Model, Tools, Handoffs, Guardrails — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.1-agent-anatomy-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.2 — ModelSettings: temperature, top_p, tool_choice, max_tokens | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.2-model-settings.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.3 — Writing Effective System Instructions — Dos and Don'ts | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.3-writing-effective-instructions.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.4 — Dynamic Instructions: Injecting Runtime Context via a Callback — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.4-dynamic-instructions-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.4 — Dynamic Instructions: Injecting Runtime Context via a Callback — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.4-dynamic-instructions-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.5 — Structured Outputs with Pydantic Models and TypedDict — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.5-structured-outputs-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.5 — Structured Outputs with Pydantic Models and TypedDict — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.5-structured-outputs-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.6 — Cloning Agents with .clone() for Persona Variants | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.6-cloning-agents.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.7 — Forcing and Controlling Tool Choice | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.7-forcing-tool-choice.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 2.8 — Tool Use Behaviour: run_llm_again vs stop_on_first_tool | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-02-agent-configuration-and-behaviour/2.8-tool-use-behaviour.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

---

## Section 03 — Tools

| Lecture | Notebook |
|---|---|
| 3.1 — Function Tools: the @function_tool Decorator | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.1-function-tool-decorator.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.2 — Type Annotations and Automatic JSON Schema Generation | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.2-type-annotations-json-schema.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.3 — Hosted Tools: WebSearchTool, FileSearchTool, CodeInterpreterTool — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.3-hosted-tools-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.3 — Hosted Tools: WebSearchTool, FileSearchTool, CodeInterpreterTool — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.3-hosted-tools-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.4 — Agents as Tools: Agent.as_tool() and Manager-Style Orchestration — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.4-agents-as-tools-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.4 — Agents as Tools: Agent.as_tool() and Manager-Style Orchestration — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.4-agents-as-tools-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.5 — Tool Context: Accessing Run State Inside a Tool — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.5-tool-context-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.5 — Tool Context: Accessing Run State Inside a Tool — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.5-tool-context-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.6 — Tool Output Types: Returning Images, Files, and Structured Data | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.6-tool-output-types.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.7 — Parallel Tool Calls and Tool Execution Order | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.7-parallel-tool-calls.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 3.8 — Error Handling Inside Tools | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-03-tools/3.8-error-handling-in-tools.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

---

## Section 04 — Running Agents, Results & Streaming

| Lecture | Notebook |
|---|---|
| 4.1 — RunResult in Depth: new_items, input_items, usage, last_agent | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-04-running-agents-and-streaming/4.1-runresult-in-depth.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 4.2 — Streaming Events in Real Time with async for | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-04-running-agents-and-streaming/4.2-streaming-events.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 4.3 — Streaming Raw Text Deltas vs Structured Run Item Events | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-04-running-agents-and-streaming/4.3-raw-deltas-vs-run-item-events.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 4.4 — RunConfig: max_turns, Model Overrides, workflow_name | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-04-running-agents-and-streaming/4.4-runconfig.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 4.5 — Context Management: RunContextWrapper and Dependency Injection | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-04-running-agents-and-streaming/4.5-context-management.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 4.6 — Handling Exceptions: MaxTurnsExceeded, Guardrail Tripwires | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-04-running-agents-and-streaming/4.6-handling-exceptions.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 4.7 — Token Cost Tracking and Usage Metadata | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-04-running-agents-and-streaming/4.7-token-cost-tracking.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

---

## Section 05 — Multi-Agent Orchestration & Guardrails

*Lectures 5.1 and 5.4 are concept-only (slides, no notebook).*

| Lecture | Notebook |
|---|---|
| 5.2 — Handoffs: Conversation Delegation to Specialist Agents — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.2-handoffs-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.2 — Handoffs: Conversation Delegation to Specialist Agents — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.2-handoffs-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.3 — Handoff Input Filters: Controlling What the Next Agent Sees | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.3-handoff-input-filters.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.5 — Building a Triage Agent with Multiple Handoff Targets — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.5-building-a-triage-agent-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.5 — Building a Triage Agent with Multiple Handoff Targets — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.5-building-a-triage-agent-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.6 — Deterministic Pipelines: Chaining Agents in Code | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.6-deterministic-pipelines.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.7 — Parallelisation with asyncio.gather | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.7-parallelisation-asyncio-gather.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.8 — Input Guardrails: Validating User Messages Before the Run | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.8-input-guardrails.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.9 — Output Guardrails: Validating Agent Responses Before Delivery | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.9-output-guardrails.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 5.10 — Guardrail Tripwires and Execution Modes (Blocking vs Parallel) | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-05-multi-agent-orchestration-and-guardrails/5.10-guardrail-tripwires-execution-modes.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

---

## Section 06 — Tracing, Observability & Capstone

*Lecture 6.1 is concept-only (slides, no notebook).*

| Lecture | Notebook |
|---|---|
| 6.2 — Viewing Traces in the OpenAI Dashboard | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-06-tracing-observability-and-capstone/6.2-viewing-traces-in-dashboard.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 6.3 — The trace() Context Manager for Custom Workflow Names — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-06-tracing-observability-and-capstone/6.3-trace-context-manager-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 6.3 — The trace() Context Manager for Custom Workflow Names — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-06-tracing-observability-and-capstone/6.3-trace-context-manager-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 6.4 — Lifecycle Hooks: RunHooks and AgentHooks for Logging | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-06-tracing-observability-and-capstone/6.4-lifecycle-hooks.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 6.5 — Agent Visualisation Tool for Debugging Multi-Agent Graphs | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-06-tracing-observability-and-capstone/6.5-agent-visualisation-tool.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 6.6 — CAPSTONE: Multi-Agent Research Assistant — **Starter** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-06-tracing-observability-and-capstone/6.6-capstone-STARTER.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| 6.6 — CAPSTONE: Multi-Agent Research Assistant — **Solution** | <a href="https://colab.research.google.com/github/gopidon/openai-agents-sdk-course-code/blob/main/section-06-tracing-observability-and-capstone/6.6-capstone-SOLUTION.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

---

## Requirements

- A Google account — for Google Colab
- An OpenAI API key — get yours at https://platform.openai.com
- No local setup required — everything runs in the cloud

See the [API key and billing setup guide](section-01-introduction-and-setup/1.5-api-key-and-billing-setup-guide.md) if this is your first time creating one.

---

## API Key Setup

Each notebook reads your API key from Colab Secrets:

1. Open the notebook in Colab
2. Click the 🔑 key icon in the left sidebar
3. Add a secret named `OPENAI_API_KEY`
4. Paste your OpenAI API key as the value
5. Run the notebook from the top

---

## Model

All notebooks use `gpt-5.4-mini` by default — declared once as a `MODEL_NAME`
variable near the top of each notebook, and reused everywhere a model string
is needed. You can change this by updating the `MODEL_NAME` variable at the
top of any notebook.

For the latest available models visit:
https://platform.openai.com/docs/models

---

## SDK Version

Every notebook pins the `openai-agents` package to a specific version for
reproducibility, with a comment explaining how to switch to the latest
release instead if you prefer. See the install cell at the top of each
notebook for the exact pinned version used.

---

## Course Link

Enroll in the course on Udemy: [OpenAI Agents SDK: Build Multi-Agent AI Systems in Python](link)

---

## License

The notebooks in this repository are for educational purposes and intended
for use by enrolled students of the course.

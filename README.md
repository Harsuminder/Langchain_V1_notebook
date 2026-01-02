# LangChain V1 — Learning Notebooks

This repository contains a structured set of personal learning notebooks created while working through the LangChain V1 API and its core components. The goal of this repository is to build a solid conceptual and practical understanding of how LangChain works under the hood including LLM integration, streaming, tools, message handling, structured outputs, and agent middleware.

It is an exploratory, educational workspace where each notebook focuses on one specific concept with minimal examples and detailed observations.

## What this repository is

- A hands-on learning log for LangChain V1
- A reference for core LangChain abstractions and patterns
- A collection of small, focused experiments
- A place to understand how agent frameworks manage control flow, state, and tool usage

## Notebook overview

| Notebook | Description |
|----------|-------------|
| `1_langchain_intro.ipynb` | Introduction to LangChain concepts and core abstractions |
| `2_LLM_integration.ipynb` | Integrating LLMs into LangChain workflows |
| `3_Streaming_and_Batching.ipynb` | Handling streaming responses and batching requests |
| `4_Tools.ipynb` | Tool calling and tool execution within agents |
| `5_Messages.ipynb` | Message formats, prompting strategies, and history management |
| `6_Structured_Outputs_in_Langchain.ipynb` | Enforcing structured outputs from LLMs |
| `7_Middleware_in_langchain_agents.ipynb` | Middleware and customization of agent execution |

Each notebook includes:
- Markdown explanations of the concept
- Small code examples
- Notes and observations from experimentation

## Why I built this

I created this repository to:

- Move beyond surface-level tutorials and understand LangChain’s internal mechanics
- Build intuition for how agents manage tools, messages, and control flow
- Prepare for building more complex agentic workflows using LangGraph and related frameworks
- Maintain a searchable, reproducible reference for future projects

## Setup

Install dependencies using:

```bash
pip install -r requirements.txt

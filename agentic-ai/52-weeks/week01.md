# Week 1

This opening lecture sets the tone for your year-long transformation into a builder of production-grade Agentic AI systems.<br/>
We clarify what “agentic” means in practice—LLM-driven agents equipped with memory, tools, and planning that can reason, retrieve knowledge, and take actions to achieve business outcomes.<br/>
You’ll get a transparent walkthrough of the program structure: weekly sprints, hands-on labs, framework comparisons (LangChain, LangGraph, LlamaIndex, CrewAI, AutoGPT), and an end-to-end capstone deployed on cloud platforms like AWS, Azure, or GCP.<br/>
We’ll articulate the competencies you’ll develop:
- prompt engineering;
- RAG;
- vector databases (FAISS, Pinecone, Chroma);
- observability;
- guardrails;
- governance;
- AgentOps.

You’ll see how each module ladders up to build robust, safe, and cost-optimized AI agents ready for enterprise integration with APIs, databases, ERP/CRM systems, and workflow tools like n8n or Zapier.<br/>
We’ll also set clear expectations for deliverables:
- GitHub-ready projects;
- demo videos;
- documentation suitable for portfolio and hiring panels. 

By the end, you’ll understand why demand is surging for professionals who can connect LLMs with tools, design memory and retrieval, and ensure safety and governance—and how this program gives you the repeatable patterns to ship value, not just prototypes.<br/>
Keywords you’ll encounter and apply throughout the course include:
- Agentic AI;
- LLM agents;
- RAG;
- vector search;
- prompt engineering;
- LangChain;
- LangGraph;
- lamaIndex;
- CrewAI;
- AutoGPT;
- guardrails;
- AgentOps;
- Kubernetes;
- serverless deployment.

You’ll leave with a clear roadmap, a checklist for your environment setup, and an understanding of how we’ll measure your growth via benchmarks, UX evaluations, and ROI impact.<br/>
This is your launchpad for a 52-week applied mastery of Agentic AI.

Keywords:
- Agentic AI;
- LLM agents;
- RAG;
- vector databases;
- prompt engineering;
- LangChain;
- LangGraph;
- LlamaIndex;
- CrewAI;
- AutoGPT;
- guardrails;
- AgentOps;
- Kubernetes;
- serverless.

## Day 1: What is Agentic AI? Evolution from AI → Generative AI → Agents

In this lecture, we trace the trajectory from rule-based AI to machine learning, onward to deep learning and Generative AI, culminating in Agentic AI.<br/>
You’ll learn what makes an agent more than a chatbot:<br/>
- the fusion of LLM reasoning;
- tool use;
- memory;
- planning;
- autonomous task execution.

We compare eras:
- expert systems with brittle rules;
- ML models that predict but don’t act;
- Generative AI that creates but remains passive;
- agents that can perceive context, retrieve knowledge, decide, and do. 

We’ll detail where agents shine:
- workflow automation;
- data analysis;
- research assistance;
- sales ops;
- customer support;
- DevOps;
- security

and where they must be constrained with:
- guardrails;
- policy enforcement;
- human-in-the-loop oversight. 

You’ll analyze the enabling stack:
- __foundation models__ for language and multimodality;
- __embeddings__ for semantic search;
- __vector databases__ for long-term memory;
- __frameworks__ such as LangChain, LangGraph, LlamaIndex, and CrewAI for orchestration. 

We cover real-world pitfalls:
- prompt injection;
- hallucinations;
- data leakage;
- cost blowouts

and mitigation patterns likeL
- RAG;
- retrieval filters;
- least-privilege tools;
- observability;
- rate limiting.

By the end, you’ll be able to articulate a crisp definition of Agentic AI, map its business impact, and identify the capabilities your first agent should include.<br/>
You’ll also receive a quick rubric to decide when a simple LLM suffices and when you need a full agent with planning, tools, and memory.

Keywords:
- Agentic AI;
- Generative AI;
- LLM;
- embeddings;
- vector database;
- RAG;
- LangChain;
- LangGraph;
- LlamaIndex;
- CrewAI;
- guardrails;
- human-in-the-loop;
- prompt injection.

![alt text](images/week01/day01/01-evolution.png)

![alt text](images/week01/day01/02-leap.png)

![alt text](images/week01/day01/03-four-pillars.png)

![alt text](images/week01/day01/04-transformation.png)

## Day 2: Anatomy of an AI Agent (LLM, memory, tools, goals)

Here we open up the black box and label every moving part.<br/> 
An effective AI agent starts with an LLM as the reasoning core, but its power comes from connected capabilities:
- memory (short-term context windows, long-term vector stores and episodic logs);
- tools (functions, APIs, code execution, retrieval);
- goals (structured tasks, constraints, and success metrics).

We’ll walk through a canonical architecture: user intent → planner → tool selection → execution → memory updates → reflection → next step.<br/>
You’ll learn how embeddings make past knowledge findable and how RAG grounds responses in trusted data.<br/>
We’ll cover prompt templates, system instructions, and state stores for reliable behavior across steps.<br/>
You’ll also examine safety layers—from content policies to schema validation to policy-as-code—and observability:
- traces;
- logs;
- metrics;
- cost dashboards. 
By the end, you’ll be able to diagram an agent, justify each component, and reason about trade-offs like planning depth vs latency, context size vs cost, and tool breadth vs safety.<br/>
We’ll provide a checklist to define goals, inputs, outputs, and acceptance tests, ensuring your agents deliver measurable value.

Keywords:
- AI agent architecture;
- LLM;
- memory;
- embeddings;
- RAG,;
- tools;
- goal-oriented planning;
- observability;
- guardrails;
- tracing;
- cost optimization.

![alt text](images/week01/day02/01-ai-agent.png)

![alt text](images/week01/day02/02-llm.png)

![alt text](images/week01/day02/03-memory.png)

![alt text](images/week01/day02/04-tools.png)

![alt text](images/week01/day02/05-goals.png)

## Day 3: Setting up your Agentic AI development environment

This is your hands-on setup guide for a smooth build experience.<br/> 
We’ll standardize on a Python-first stack (with room for JavaScript/TypeScript if needed), install core libraries (LangChain, LangGraph, LlamaIndex, FastAPI/Express, FAISS, Pinecone clients), configure API keys for OpenAI/Anthropic/Hugging Face, and spin up virtual environments and .env management for clean isolation.<br/>
You’ll provision a vector database (local FAISS to start, optional Pinecone for scale), create a project scaffold with src/tests/config folders, add logging and tracing hooks, and wire a minimal RAG pipeline to validate dependencies.<br/>
We’ll set linting, formatting, and pre-commit to keep repos tidy; configure Docker to containerize your agents; and show a local compose file for LLM endpoints, vector stores, and a lightweight observability stack.<br/>
You’ll also create a template .ipynb for rapid prototyping and a CLI entrypoint for scripted runs.<br/>
Security basics:
- secret management;
- least privilege;
- rate limiting

are included from day one.<br/>
You’ll also create a template .ipynb for rapid pro
By the end, you’ll have a working dev environment with reproducible builds and the baseline agent skeleton you’ll extend throughout the program.

Keywords: 
- Agentic AI dev environment;
- Python;
- LangChain;
- LangGraph;
- LlamaIndex;
- FAISS;
- Pinecone;
- Docker;
- RAG, ;
- observability;
- API keys;
- .env.

### Core Tools to Install
These foundational tools form the backbone of your agentic AI development workspace.

#### 1 Python 3.10+
The core programming language for agentic AI development, with version 3.10+ offering critical features like pattern matching and improved type hinting that modern frameworks utilize.

#### 2 Jupyter & VS Code
Jupyter for interactive experimentation and visualization; VS Code for production-grade development with extensions for AI workflows

#### 3 Git & GitHub
Essential for version control, tracking changes, and collaborating with peers on complex agent architectures

#### 4 Conda or venv
Environment management to isolate dependencies for different projects and prevent conflicts between packages

### Essential Libraries

#### LangChain / LangGraph
Frameworks for composing LLMs into reasoning chains and complex agent workflows with memory and tool use

#### LlamaIndex
Powerful data framework for connecting custom data to LLMs and building knowledge-intensive applications

#### FAISS / Chroma
Vector databases for efficient similarity search, essential for agent memory and retrieval augmentation

#### OpenAI / HuggingFace
API integrations for accessing state-of-the-art language models and embedding services

### Cloud & API Keys

#### Essential Accounts
- OpenAI Platform: GPT-4, GPT-3.5, and embedding models;
- Anthropic Claude: Alternative LLM with strong reasoning;
- Hugging Face Hub - Open source models and datasets.

#### Security Best Practices
- Store API keys in .env files (never commit to Git);
- Use environment variables via dotenv package;
- Implement usage monitoring to avoid unexpected costs;
- Set up spending limits in provider dashboards.

### Testing Your Setup
Before proceeding to labs, verify your environment with this simple test that
confirms your tools, libraries, and API connections are working properly:
```
# Hello Agent Test
import os
from dotenv import load_dotenv
from langchain.llms import OpenAI
from langchain.agents import initialize_agent, Tool
from langchain.chains import LLMChain

# Load environment variables
load_dotenv()

# Initialize LLM
llm = OpenAI(temperature=0)

# Test simple completion
response = llm("You are an AI assistant. Say hello:")
print(f"Test result: {response}")
```
Run the Test Script<br/>
Execute the provided code to verify your LLM connection

Troubleshoot Issues<br/>
Debug any package import or API authentication errors

Document Your Setup<br/>
Create a requirements.txt file for reproducibility
# AI Engineer Interview Preparation Roadmap 🚀

**First review the material in the GEN-AI Folder than visit this material for futher knowledge and improvement upon the interview skills**

A curated collection of "hard mode" study materials for Senior AI Engineer interviews. This repository focuses on **RAG, Agents, LangGraph, Model Context Protocol (MCP), and LLM System Design**.

> **Note:** This collection emphasizes production-grade architecture, latency optimization, and system design patterns rather than basic definitions.

---

## 📚 Table of Contents
- [1. Agentic Architecture & Theory](#1-agentic-architecture--theory)
- [2. LangGraph & State Machines](#2-langgraph--state-machines)
- [3. Advanced RAG (Production Patterns)](#3-advanced-rag-production-patterns)
- [4. Model Context Protocol (MCP)](#4-model-context-protocol-mcp)
- [5. LLM System Design & Inference](#5-llm-system-design--inference)
- [6. Interview Question Banks](#6-interview-question-banks)

---

## 1. Agentic Architecture & Theory
*Foundational papers and blogs defining modern autonomous agents.*

* **[LLM Powered Autonomous Agents (Lilian Weng)](https://lilianweng.github.io/posts/2023-06-23-agent/)**
    * **Why read this:** The industry standard reference for agent definitions. Covers memory, planning (CoT vs. Tree of Thoughts), and tool use.
* **[Patterns for Building LLM Systems (Eugene Yan)](https://eugeneyan.com/writing/llm-patterns/)**
    * **Why read this:** High-density resource for design patterns like Caching, Guardrails, and Defensive UX.

## 2. LangGraph & State Machines
*Moving from linear chains (DAGs) to cyclic graphs for complex, stateful agents.*

* **[LangChain Academy: Intro to LangGraph](https://academy.langchain.com/courses/intro-to-langgraph)**
    * **Focus:** Official course. Study **Module 3** (Human-in-the-loop, Time Travel, Breakpoints).
* **[DeepLearning.AI: AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
    * **Focus:** Teaches building agents from "first principles" in pure Python before refactoring into LangGraph.
* **[LangGraph Documentation: Customer Support Bot](https://langchain-ai.github.io/langgraph/tutorials/customer-support/customer-support/)**
    * **Focus:** The "Take Home" task standard. Includes code for `StateGraph`, `checkpointers` (memory), and interrupt logic.

## 3. Advanced RAG (Production Patterns)
*Moving beyond "naive" RAG to hybrid search and re-ranking.*

* **[Advanced RAG Techniques (GitHub)](https://github.com/NirDiamant/RAG_Techniques)**
    * **Focus:** Code implementations for 30+ techniques including **Self-RAG**, **HyDE** (Hypothetical Document Embeddings), and **Reranking**.

## 4. Model Context Protocol (MCP)
*The new standard for connecting AI models to data and tools.*

* **[Model Context Protocol (Official Docs)](https://modelcontextprotocol.io/introduction)**
    * **Focus:** Understand the **Host-Client-Server** architecture and the security model (Resources vs. Tools).

## 5. LLM System Design & Inference
*Architecting for latency, throughput, and scale.*

### Core Design Guides
* **[Machine Learning System Design (Chip Huyen)](https://huyenchip.com/2022/01/02/real-time-machine-learning-challenges-and-solutions.html)**
    * **Focus:** Real-time vs. Batch serving, and the challenges of deploying ML in production.
* **[Machine Learning Design Docs (Eugene Yan)](https://github.com/eugeneyan/ml-design-docs)**
    * **Focus:** Real-world technical specs. Read the "LLM System Design" examples to see how they handle context windows and cost.
* **[GenAI System Design (ByteByteGo)](https://github.com/bytebytego/SystemDesign)**
    * **Focus:** Visual diagrams for high-level systems like "Design ChatGPT" or "Design a Vector DB".

### Inference Optimization (Critical for Senior Roles)
| Topic | Resource |
| :--- | :--- |
| **KV Caching** | [vLLM Blog: PagedAttention](https://blog.vllm.ai/2023/06/20/vllm.html) |
| **Continuous Batching** | [Anyscale: Continuous Batching for LLMs](https://www.anyscale.com/blog/continuous-batching-llm-inference) |
| **Speculative Decoding** | [HuggingFace: Assisted Generation](https://huggingface.co/blog/assisted-generation) |
| **Routing** | [RouteLLM (LMSYS)](https://lmsys.org/blog/2024-07-01-routellm/) |

## 6. Interview Question Banks
*Actual questions asked by hiring managers.*

* **[LLM Interview Questions (GitHub)](https://github.com/llmgenai/LLMInterviewQuestions)**
    * **Focus:** Deep technical questions on Vector DB internals, Hallucinations, and RLHF/DPO.
* **[Awesome Generative AI (GitHub)](https://github.com/filipecalegario/awesome-generative-ai)**
    * **Focus:** Mental models and historical context for generative architectures.
* **[Machine Learning Interviews (GitHub)](https://github.com/alirezadir/machine-learning-interviews)**
    * **Focus:** The "System Design Template" (7-step framework for answering design questions).

---
*Created for personal study and reference.*

# Video 1: Introduction to LangChain

**Core Concept:**
Large Language Models (LLMs) are powerful but isolated. They cannot access real-time data, personal documents, or perform actions. 
LangChain is a framework that solves this by allowing LLMs to interact with external data sources and APIs.

**Key Differences:**
*   **Standalone LLM App (e.g., ChatGPT):** Prompt goes in, text comes out.
*   **Enterprise LLM Pipeline (LangChain):** Prompt goes in -> searches database -> retrieves facts -> passes facts to LLM -> LLM generates grounded response.

**Benefits of LangChain:**
1. Abstraction (easy to switch between OpenAI, Gemini, HuggingFace).
2. Built-in tools for memory, data retrieval, and complex chaining.

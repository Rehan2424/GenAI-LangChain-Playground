# Video 2: LangChain Components

LangChain is built on modular components that can be chained together.

### 1. Models
The core processing engines. Divided into:
*   **LLMs:** Take a string, return a string.
*   **Chat Models:** Take a list of messages, return a message.
*   **Text Embedding Models:** Take text, return numerical arrays (embeddings).

### 2. Prompts
Templates to dynamically construct instructions for models, avoiding hard-coded f-strings.

### 3. Indexes (Retrieval)
Tools to structure documents so models can search them (Document Loaders, Text Splitters, Vector Stores).

### 4. Memory
Allows the LLM to remember previous turns in a conversation.

### 5. Chains
A sequence of calls (e.g., Prompt -> Model -> Output Parser).

### 6. Agents
LLMs that use external tools (like search engines or calculators) to figure out how to answer a prompt autonomously.

<img width="1090" height="593" alt="image" src="https://github.com/user-attachments/assets/bad3447a-b57d-4323-8d12-e526cba504a9" />

# LangChain 

**Source**: [IBM - What is LangChain?](https://www.ibm.com/think/topics/langchain)

LangChain is an open-source framework for building applications powered by Large Language Models (LLMs). It supports both Python and JavaScript and simplifies the development of AI applications such as chatbots, AI agents, summarization systems, and intelligent search tools.

LangChain acts as a bridge between LLMs, external data sources, APIs, and software tools, enabling developers to create modular and scalable AI applications.

---

## Core Concepts

### LLM Integration

LLMs are not standalone applications. They require:

- User interfaces
- External data sources
- Software/API integrations

LangChain provides a standardized interface for models such as:

- OpenAI GPT
- Anthropic Claude
- Meta LLaMA
- IBM Granite
- Google Flan-T5
- DeepSeek

This allows developers to switch between models with minimal code changes.

---

### Prompt Templates

LangChain provides the `PromptTemplate` class for reusable and structured prompts.

Features include:

- Dynamic input variables
- Few-shot prompting
- Reusable prompt structures
- Standardized formatting

This simplifies prompt engineering and improves consistency across applications.

---

### Chains

Chains are workflows that connect multiple components together.

#### Common Chain Types

- `LLMChain` → Combines a prompt with an LLM
- `SimpleSequentialChain` → Uses the output of one step as the input of the next

Chains allow developers to:

- Combine multiple prompts
- Use multiple models
- Integrate APIs and tools
- Build multi-step reasoning systems

---

## Working with External Data

### Document Loaders

LangChain supports importing data from many external sources, including:

- Google Drive
- Dropbox
- OneDrive
- YouTube
- Notion
- Airtable
- MongoDB
- Pandas
- Websites and URLs

---

### Vector Databases

LangChain supports vector embeddings and vector databases for semantic search.

Benefits include:

- Fast information retrieval
- Similarity search
- Metadata storage
- Scalable querying

LangChain integrates with:

- 25+ embedding methods
- 50+ vector stores

---

### Text Splitters

Large documents can be divided into smaller semantic chunks to:

- Improve retrieval speed
- Reduce computational cost
- Enhance context quality

---

### Retrieval-Augmented Generation (RAG)

LangChain supports RAG systems, where LLMs retrieve external knowledge before generating responses.

RAG enables:

- Access to internal/private documents
- Real-time information retrieval
- Improved factual accuracy

#### Agentic RAG

Advanced RAG systems can additionally:

- Perform calculations
- Write emails
- Analyze data
- Dynamically use tools

---

## Memory

By default, LLMs do not retain long-term memory.

LangChain adds memory systems that can:

- Store full conversations
- Keep summarized histories
- Retain recent interactions

This improves conversational continuity.

---

## Tools

LangChain tools allow AI agents to interact with external systems and services.

Examples include:

- Wolfram Alpha → Mathematics and computation
- Google Search → Real-time web search
- OpenWeatherMap → Weather information
- Wikipedia → Knowledge retrieval

Tools extend LLM capabilities beyond text generation.

---

## LangChain Agents

LangChain agents allow LLMs to:

- Make decisions
- Plan actions
- Use tools
- Execute workflows autonomously

Unlike traditional chatbots, agents can:

- Think step-by-step
- Adapt dynamically
- Perform multi-step reasoning

---

## LangGraph

LangGraph is a framework for building multi-agent AI systems.

Features include:

- Graph-based workflows
- Multi-agent collaboration
- Human-in-the-loop monitoring
- Tool orchestration
- Stateful AI systems

LangGraph also supports integrations through MCP (Model Context Protocol).

---

## LangSmith

LangSmith helps developers transition from prototypes to production-ready applications.

Capabilities include:

- Debugging
- Monitoring
- Evaluation
- Performance tracing
- Error tracking
- Cost optimization

It works with both LangChain and non-LangChain applications.

---

## Application

### Chatbots
LangChain helps build context-aware chatbots and integrate them with existing communication platforms and APIs.

### Summarization
LLMs can summarize various types of content, including:

- Academic articles
- Emails
- Reports
- Meeting transcripts

### Question Answering
LangChain enables LLMs to retrieve information from specialized knowledge bases and documents such as:

- Wolfram Alpha
- arXiv
- PubMed

This improves the accuracy and relevance of generated answers.

### Data Augmentation
LLMs can generate synthetic data that resembles real training data, helping improve machine learning models and datasets.

### Virtual Agents
LangChain Agents can autonomously:

- Plan actions
- Determine next steps
- Use tools and APIs
- Automate workflows with robotic process automation (RPA)
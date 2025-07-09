# 🔗 LangChain Academy Workshop

![LangChain Logo](https://python.langchain.com/img/langchain.svg)

## 🚀 Build Smart AI Applications with LangChain and LangGraph

Welcome to the **LangChain Academy Workshop**! This repository contains a comprehensive set of Jupyter notebooks that will guide you through building powerful, production-ready AI applications using LangChain and LangGraph frameworks.

## 🧠 What You'll Learn

This workshop takes you on a journey through the key components of building sophisticated AI systems:

### 01 - Basics
- **Chat models**: Working with Gemini 2.5 Flash/Pro models
- **Essential concepts**: Messages, prompts, and model parameters
- **Core interactions**: Invoking models and streaming responses

### 02 - Chain
- **Graph state management**: Using messages as state in graph nodes
- **Chat models in graphs**: Integrating LLM capabilities into workflows
- **Tool binding**: Adding external capabilities to your LLM
- **Tool execution**: Handling model-initiated tool calls in graph nodes

### 03 - Agent
- **ReAct architecture**: Building a reasoning + action agent pattern
- **Tool-augmented interactions**: Enabling LLMs to use external tools
- **Multi-step reasoning**: Creating agents that can solve complex tasks
- **Decision-making**: Implementing conditional logic in agent workflows

### 04 - Chatbot with Summarization
- **Memory management**: Creating chatbots with long-term memory
- **Message summarization**: Compressing conversation history
- **Thread management**: Handling multiple conversation threads
- **State persistence**: Maintaining conversation context across interactions

### 05 - RAG (Retrieval-Augmented Generation)
- **Document processing**: Loading, splitting, and storing text
- **Vector embeddings**: Creating searchable document representations
- **Semantic retrieval**: Finding relevant information for user queries
- **Context-aware generation**: Producing responses based on retrieved information

## 🛠️ Technologies Used

- **LangChain**: Framework for building LLM applications
- **LangGraph**: Tool for creating multi-step AI workflows
- **Google Generative AI**: Gemini models for natural language processing
- **Vector stores**: For semantic document retrieval
- **Jupyter notebooks**: Interactive learning environment

## 🏁 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/langchain_academy_workshop.git
   cd langchain_academy_workshop
   ```

2. Install the required dependencies:
   ```bash
   pip install -U langchain-google-genai langchain_core langchain_community langgraph langgraph-prebuilt langchain-text-splitters
   ```

3. Set up your Google AI API key:
   ```python
   import os
   os.environ["GOOGLE_API_KEY"] = "your-api-key-here"
   ```

4. Work through the notebooks in sequence:
   - `01_basics.ipynb`: Introduction to LangChain and chat models
   - `02_chain.ipynb`: Building your first LangChain graph
   - `03_agent.ipynb`: Creating a ReAct agent
   - `04_chatbot-summarization.ipynb`: Building a memory-efficient chatbot
   - `05_rag.ipynb`: Implementing retrieval-augmented generation

## 📚 Key Concepts

### Graph State and Control Flow
Learn how to manage the state of your AI applications through well-defined graph nodes and edges, enabling complex, multi-step reasoning processes.

### Tool Integration
Enhance your LLMs with the ability to use external tools, making them capable of performing actions beyond just generating text.

### Memory and Persistence
Implement sophisticated memory management techniques to create AI systems that maintain context across interactions.

### Retrieval and Generation
Build systems that can find relevant information from large document collections and generate accurate, contextual responses.

## 🌟 Why This Matters

As AI systems become more integrated into software applications, understanding how to build reliable, controllable, and effective AI components becomes essential. This workshop provides practical experience with the frameworks and patterns used in production AI systems today.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Acknowledgments

- The LangChain team for creating an amazing framework
- All workshop participants for their engagement and contributions

---

Happy building! If you have any questions or need help, feel free to open an issue in this repository.

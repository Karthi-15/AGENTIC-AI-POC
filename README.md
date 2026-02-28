Project Description
# Agentic AI POC using LangGraph

This repository contains a **learning-based Proof of Concept (POC)** built using **LangGraph** to understand how **agentic AI systems** can be created with state, tools, memory, and human control.

The project gradually evolves from simple workflows to more advanced **agent-style AI behavior**.

---

## What this POC demonstrates

- Graph-based AI workflows using **LangGraph**
- Passing and updating shared **state** across nodes
- Conditional routing between nodes
- Building a **stateful chatbot** using Google Gemini
- Tool calling for real-world actions (stock price example)
- Multi-step reasoning using an **agent loop**
- Conversation memory using checkpoints
- Observability using **LangSmith**
- Human-in-the-loop (HITL) approval for sensitive actions

---

## Key Concepts Covered

- **Simple Graphs**: Nodes and edges with shared state  
- **Conditional Graphs**: Routing based on runtime conditions  
- **Chatbot**: Multi-turn conversational agent  
- **Tool Calling**: LLM deciding when to call tools  
- **Agent Behavior**: Tool → LLM → Tool reasoning loop  
- **Memory**: Thread-based conversation context  
- **Tracing**: Monitoring calls and token usage  
- **Human-in-the-Loop**: Manual approval using interrupts  

---

## Tech Stack

- Python
- LangGraph
- LangChain
- Google Gemini API
- LangSmith
- Jupyter Notebook

---



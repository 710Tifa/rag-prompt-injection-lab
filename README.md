# RAG Prompt Injection Lab

## Overview

This project demonstrates an Indirect Prompt Injection attack against a Retrieval-Augmented Generation (RAG) pipeline using LangChain and a local Llama 3 model served with Ollama.

The objective is to demonstrate how an LLM can become a Confused Deputy by executing malicious instructions embedded inside retrieved documents instead of following the legitimate user request.

---

## Technologies

- Python
- LangChain
- LangChain Community
- Ollama
- Llama 3

---

## Attack Scenario

The RAG system retrieves information from an external document.

The retrieved document contains hidden malicious instructions.

Instead of answering the user's legitimate question, the model follows the injected instructions contained in the retrieved context.

---

## Expected Output

```
HACKED! CONFUSED DEPUTY ATTACK SUCCESSFUL.
```

---

## Learning Objectives

- Indirect Prompt Injection
- RAG Security
- Confused Deputy Problem
- Prompt Injection
- AI Security

---

## Disclaimer

This project was created for educational and security research purposes only.

# Policy Copilot: AI-Driven Bias Detection
**Status:** Alpha / Active Development

## Overview
Policy Copilot is a multi-agent system designed to automate the auditing of policy documents. By utilizing Retrieval-Augmented Generation (RAG) and chain-of-thought verification, it identifies potential political bias, logical inconsistencies, and unsupported claims in real-time.

## Key Features (In Development)
* **Auditable RAG:** Traces every generated claim back to a specific source paragraph in the policy text.
* **Bias Detection Engine:** Uses a "Critic Agent" to flag normative language or logical fallacies.
* **Vector Search:** Powered by Pinecone/FAISS for <200ms retrieval on 500+ page documents.

## Tech Stack
* **Core:** Python 3.10+, LangChain
* **LLMs:** OpenAI API (GPT-4o), Anthropic Claude
* **Database:** Pinecone (Vector DB)

## Roadmap
- [x] Initial Architecture Design
- [ ] RAG Pipeline Implementation
- [ ] Streamlit UI Dashboard
- [ ] Evaluation Harness (Golden Set Testing)

*Note: This repository is currently being populated with the local development codebase.*

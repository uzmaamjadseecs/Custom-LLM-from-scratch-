**Custom LLM From Scratch** 🧠

This repository documents the end-to-end implementation of a Large Language Model (LLM) built completely from scratch — without relying on high-level pretrained model libraries. The goal is to deeply understand and implement the core building blocks behind modern transformer-based language models.

**Tokenization**

The file Tokenization.ipynb contains the implementation for creating tokens from the Verdict Story dataset. This notebook walks through the full tokenization pipeline — from raw text processing to generating token IDs that are used as inputs to the LLM.

Tokenization is a critical step in building a language model, as neural networks operate on numerical representations rather than raw text.

**Tokenization Workflow**

Load raw text data (Verdict Story)
Split text into individual tokens
Build a vocabulary from unique tokens
Assign a unique ID to each token
Convert text into token IDs for model training

**Vocabulary Creation**

After tokenizing the text:
Unique tokens are extracted
A vocabulary dictionary is created
Each token is mapped to a unique integer ID

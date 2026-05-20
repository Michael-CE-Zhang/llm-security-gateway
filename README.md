# llm-security-gateway
LLM security gateway is a pre-filter for LLM-based conversational applications. It is a solution to detetect potentially malicious input, sesitive data, identify Prompt Injection, jailbreaking, personal data leakage (DLP/PII), and malicious URLs

## Features
LLM security gateway offers 4 layers of defense:
- Sesitve data detection: Use RAG+Embedding to save and detect sensitve data 
- LLM-based detection: Use a dedicated LLM to analyze incoming prompts and identify potential attacks.
- Model Armor：The official Model Armor SDK can identify Prompt Injection, jailbreaking, personal data leakage (DLP/PII), and malicious URLs.

## Architecture

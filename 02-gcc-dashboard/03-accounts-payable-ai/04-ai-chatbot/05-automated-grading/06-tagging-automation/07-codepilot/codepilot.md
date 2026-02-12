# Architecture - Codepilot
```mermaid
graph TD
A[Developer Prompt] --> B[LangChain Orchestrator]
B --> C[LLM Model]
C --> D[Generated Code]
D --> E[Test Suggestions]

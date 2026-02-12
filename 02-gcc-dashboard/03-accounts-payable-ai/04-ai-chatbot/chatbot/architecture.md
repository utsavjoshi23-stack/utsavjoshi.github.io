# Architecture Chatbot
```mermaid
graph TD
A[User Ticket] --> B[Rasa NLU]
B --> C[Intent Classification]
C --> D[API to Ticket System]
D --> E[Auto Resolution]

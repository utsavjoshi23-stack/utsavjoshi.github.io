```mermaid
graph TD
A[Invoice Upload] --> B[OCR Engine]
B --> C[Language Detection]
C --> D[NLP Extraction]
D --> E[Approval Routing]
E --> F[ERP System]

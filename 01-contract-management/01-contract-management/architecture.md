# System Architecture — Contract Lifecycle Automation

```mermaid
graph TD
A[Contract Request] --> B[Power Automate Intake]
B --> C{Country?}
C -->|US| D[US Workflow]
C -->|EU| E[EU Workflow]
C -->|APAC| F[APAC Workflow]

D --> G[SharePoint Storage]
E --> G
F --> G

G --> H[MS Copilot Summaries]
H --> I[Legal Review]
I --> J[Final Approval]

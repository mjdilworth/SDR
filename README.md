# SDR
SRE Decision Record
```mermaid
graph TD
  A[Identify Need for Decision] --> B[Create Branch and Draft ADR]
  B --> C[Push Branch and Open Pull Request]
  C --> D[Team Review and Discussion]
  D --> E{Consensus Achieved?}
  E -- Yes --> F[Update Status to 'Accepted']
  E -- No --> G[Revise ADR Based on Feedback]
  G --> C
  F --> H[Merge into Main]
  H --> I["Tag Release or Milestone (optional)"]
  I --> J[Implement Decision in Code]
  J --> K[Reference ADR in Commits/Tickets]
  K --> L[Periodic Review of ADRs]
  L --> M{Update or Supersede?}
  M -- Yes --> B
  M -- No --> N[Continue with Current Decision]


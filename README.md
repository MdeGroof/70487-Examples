```mermaid
  stateDiagram
  direction LR
  [*] --> Waiting
  Waiting --> Processing
  Proccessing --> Successful
  state Waiting {
    direction LR
    Incomplete --> Complete
  }
  Processing --> Failed
```

```mermaid
  stateDiagram
  direction LR
  [*] --> Waiting
  Waiting --> Processing
  Proccessing --> Successful
  state Incomplete {
    direction LR
    Incomplete --> Complete
  }
  Processing --> Failed
```

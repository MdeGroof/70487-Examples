```mermaid
  sequenceDiagram
  direction LR
  [*] --> Waiting
  Waiting --> Processing
  Proccessing --> Successful
  state Processing {
    direction LR
    Incomplete --> Complete
  }
  Processing --> Failed
```

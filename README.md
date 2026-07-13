# homelab

```mermaid
flowchart TD
    A[Perform Partner Validation] -->B("Create integrated\nuse-case blog")
    B --> C{"Is it a good AI\nquickstart candidate?"}
    B -.->|Link| F
    C -->|Yes| D[Create AI quickstart]
    B -.->|Link| D
    C -->|No| E[Stop]
    D --> F("Create demo\nor arcade")
```

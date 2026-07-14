# homelab

```mermaid
flowchart TD
    S@{ shape: circ, label: "Start" } -->A("Partner Validation or Certification")
    A -->B("Document an integrated business use-case ")
    B -->C{"Is use-case a good AI quickstart candidate?"}
    C -->|Yes| D["Create AI quickstart"]
    C -->|No| E("Create a use-case blog")
    E -.->|Link| H
    D -->F("OPTIONAL: Create demo or arcade")
    F -->H("Publish quickstart")
    H -->E
    E -->G@{ shape: dbl-circ, label: "Stop" }
```

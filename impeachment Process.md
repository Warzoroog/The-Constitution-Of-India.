```mermaid
flowchart TD
    A[Start] --> B{Impeachment Proposed on Discord}
    B --> C[Congress Debate (Discord)]
    C --> D{Congress Vote (Simple Majority)}
    D -- Passed --> E[Confirm In‑Game]
    D -- Failed --> G[End]
    E --> F[President Removed]
    F --> H[Vice‑President Acting]
    H --> I[Optional: New Election]
    A --> J[Resignation]
    J --> H
    A --> K{Emergency Removal on Discord}
    K --> L{Congress 3/4 Vote}
    L -- Yes --> H
    L -- No --> G
    H --> G[End]

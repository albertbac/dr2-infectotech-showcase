# Architecture

## High-level architecture
- Classification: CORE HEALTHCARE / CLINICAL AI
- Category: clinical-ai
- Confidence: LOW
- Exposure risk: MEDIUM

```mermaid
    flowchart LR
        A[Web interface]
    B[Controlled workflow layer]
    C[Structured persistence]
    D[Reporting surface]
    E[Review boundary]
        A --> B
    B --> C
    C --> D
    D --> E
```

## Public-safe component view
- Web interface
- Controlled workflow layer
- Structured persistence
- Reporting surface
- Review boundary

## Boundary notes
- This diagram is intentionally high level.
- No internal routes, private services, live storage names, or deployment details are published.
- The public-safe view is limited to product layers that can be discussed without weakening security.

# Strategic Intelligence System Architecture

```mermaid
flowchart TD
    A[Data Collection] -->|feeds into| B[Data Processing]
    B --> C[Data Storage]
    C --> D[Data Analysis]
    D -->|produces insights| E[Decision Support System]
    E --> F[Reporting]
    
    classDef darkTheme fill:#1b1b1b,stroke:#ffffff,stroke-width:2px;
    class A,B,C,D,E,F darkTheme;
    classDef nodeStyle fill:#0a74da,stroke:#ffffff,color:#ffffff;
    class A,B,C,D,E,F nodeStyle;
```

# Evaluating an OER

## How to evaluate

```mermaid
graph TD
    A[Identify Pedagogical Goals] --> B(Search for OER that meet these needs)
    B --> C{OER Found?}
    C -->|No| D[CREATE]
    C -->|Yes| E[Evaluate OER Quality]
    E --> F[Disciplinary/Course Relevance?]
    F -->|No| B
    F -->|Yes| G[Quality of Content?]
    G -->|No| B
    G -->|Yes| H[OER Requires Adaptation?]
    H -->|No| I[ADOPT]
    H -->|Yes| J[Editable File?]
    J -->|No| B
    J -->|Yes| K[License allows adaptation?]
    K -->|No| D
    K -->|Yes| L[ADAPT]
```mermaid

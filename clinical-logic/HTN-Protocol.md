# Hypertension Management Protocol

## Protocol I: Mild to Moderate
**Condition:** SBP 140–159 mmHg and/or DBP 90–99 mmHg

1. Start Amlodipine 2.5–5 mg once daily
2. Review after 1 month
3. If target not met (≤140/90 mmHg for most patients), increase Amlodipine to 10 mg
4. If still not met after 1 month, REFER

## Protocol II: Severe
**Condition:** SBP ≥160 mmHg and/or DBP ≥100 mmHg

```mermaid
flowchart TD;
    A[BP ≥160/100 mmHg] --> B{Is Patient Pregnant?};
    B -->|Yes| C[Refer to Specialist];
    B -->|No| D[Start Amlodipine 2.5-5 mg + Losartan 50 mg];
    D --> E[Review in 1 Month];
    E --> F{Target Met?};
    F -->|No| G[Increase Losartan to 100 mg];
    G --> H[Review in 1 Month];
    H --> I{Target Met?};
    I -->|No| J[Add HCTZ 12.5-25 mg + Refer];
    F -->|Yes| K[Continue & Follow-up];
    I -->|Yes| K;
```

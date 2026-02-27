# Step 3 – MVP Definition  
**AI RFP Estimation Intelligence Platform**

---

## 1. Core Hypothesis This MVP Tests

> Mid-sized IT services firms experience meaningful estimation variability and will pay for a structured system that improves consistency and auditability — even if AI is minimal.

More specifically:

1. Estimation variance across architects is measurable.
2. Organizations are willing to standardize decomposition logic.
3. Governance + consistency is a stronger entry hook than “AI automation”.
4. Buyers value structured risk visibility more than document summarization.
5. A semi-assisted system (not full AI automation) is sufficient to justify pilot pricing.

If this hypothesis fails, the product becomes a productivity enhancer, not a strategic platform.

---

## 2. Primary Target Customer Segment (Initial Narrow Focus)

### Narrow ICP (Do Not Expand Early)

**Company Type**
- Custom software development firms
- 300–1200 employees
- India / Southeast Asia / Eastern Europe
- Responding to 5–20 RFPs per month
- Margin pressure between 18–30%

**Internal Setup**
- Excel-based estimation sheets
- No formal risk scoring model
- No structured bid knowledge reuse
- No internal AI team

**Champion Persona**
- Head of Pre-Sales OR Senior Bid Manager
- Frustrated by inconsistency between architects
- Wants governance without replacing experts

Avoid:
- Tier-1 global system integrators
- Firms with advanced internal AI tooling
- Firms below 150 employees

---

## 3. Must-Have Features (Strictly Minimal)

The MVP is NOT an AI platform.  
It is a **Structured Estimation Governance Tool with Assisted Intelligence.**

### 3.1 RFP Upload & Structured Parsing (Basic)

- Upload PDF / DOCX
- Extract plain text
- Manual tagging interface:
  - Functional requirements
  - Non-functional requirements
  - Integrations
  - Assumptions

⚠ No advanced NLP required.
Use rule-based extraction + human review layer.

---

### 3.2 Structured Work Breakdown Builder

- Convert tagged requirements into:
  - Modules
  - Sub-components
  - Work packages

- Editable by architect
- Standardized taxonomy template

Goal:
Force structured thinking.

---

### 3.3 Effort Estimation Framework

- Configurable estimation model:
  - Effort per module
  - Complexity multiplier
  - Risk buffer %
  - Contingency %

- Version tracking of estimates
- Change log

No ML prediction engine required.

---

### 3.4 Risk Scoring Framework (Template-Based)

Predefined risk checklist:

| Risk Category | Score (1–5) | Notes |
|---------------|------------|-------|
| Scope clarity | | |
| Integration complexity | | |
| Third-party dependency | | |
| Timeline pressure | | |
| Domain unfamiliarity | | |

Auto-calculate:
- Overall risk index
- Suggested buffer range

Rule-based, not AI-inferred.

---

### 3.5 Estimation Audit Trail

- Who changed what
- Version comparison
- Assumption log
- Risk justification record

This is a major differentiator.

---

### 3.6 Scenario Comparison

Allow 2–3 pricing scenarios:

```mermaid
flowchart LR
    A[Base Estimate] --> B[Add 10% Risk Buffer]
    A --> C[High Confidence Scenario]
    A --> D[Aggressive Competitive Pricing]
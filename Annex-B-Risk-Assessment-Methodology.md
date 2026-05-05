# Annex B — Risk Assessment Methodology & Matrix  
### Veridian Resources (Fictional Case Study for Learning & Portfolio Demonstration Purposes Only)

This annex outlines the risk assessment methodology used to evaluate ISO 27001 control gaps.  
The approach reflects expert‑level alignment with **NIST SP 800‑30**, SOCI Act considerations, and mining‑sector operational risk.

---

# 1. Methodology Overview

Risk ratings were determined using:

- **Likelihood** — probability of exploitation  
- **Impact** — operational, financial, regulatory, and safety consequences  

**Risk Score = Likelihood × Impact**

This model ensures prioritisation reflects real‑world business impact, not technical severity alone.

---

# 2. Likelihood Criteria

| Rating | Description | Indicators |
|--------|-------------|------------|
| **Low (1)** | Unlikely | Strong controls, no incident history |
| **Medium (2)** | Possible | Some weaknesses, limited monitoring |
| **High (3)** | Likely | Known gaps, high exposure, no monitoring |

---

# 3. Impact Criteria

| Rating | Description | Business Impact |
|--------|-------------|-----------------|
| **Low (1)** | Minor | Minimal disruption; negligible financial/compliance effect |
| **Medium (2)** | Moderate | Noticeable disruption; moderate financial loss |
| **High (3)** | Severe | Production halt; major loss; regulatory breach |

---

# 4. Risk Matrix

| Impact ↓ / Likelihood → | Low (1) | Medium (2) | High (3) |
|--------------------------|---------|------------|-----------|
| **Low (1)** | Low | Low | Medium |
| **Medium (2)** | Low | Medium | High |
| **High (3)** | Medium | High | Critical |

---

# 5. Risk Level Definitions

| Risk Level | Description | Required Action |
|------------|-------------|-----------------|
| **Low** | Acceptable | Monitor periodically |
| **Medium** | Moderate | Plan remediation |
| **High** | Significant | Prioritised remediation |
| **Critical** | Severe | Immediate action |

---

# 6. Application to Key Findings

| Finding | Likelihood | Impact | Risk Level | Expert Justification |
|---------|------------|--------|------------|-----------------------|
| Weak access control | High | High | **Critical** | 40% over‑provisioned accounts |
| No incident response | High | High | **Critical** | No capability to respond to OT/IT incidents |
| Asset management gaps | Medium | High | **High** | No visibility of systems/assets |
| Supplier security gaps | Medium | Medium | **Medium** | Unmanaged third‑party access |
| Lack of ISMS governance | High | High | **Critical** | No oversight or accountability |

---

# 7. Prioritisation Logic

Risks were prioritised based on:

1. Impact to mining operations  
2. Safety implications (OT systems)  
3. Regulatory exposure (SOCI Act, Privacy Act)  
4. Ease of exploitation  

**Expert Insight:**  
The highest risks were systemic governance failures, not isolated technical issues.


# 🛡️ Global Sentinel — Multi-Tiered AML/CFT Risk & Intelligence Framework

> **Production-Grade AML/CFT Risk Orchestration Engine** | **Risk-Based Approach (RBA)** | **FATF 40 Recommendations Compliant** | **Explainable AI (XAI)**

---

## 📋 Table of Contents

| Section | Description |
|---------|-------------|
| [Executive Summary](#-executive-summary) | System overview and enterprise capabilities |
| [Core Capabilities](#-core-capabilities--risk-framework) | Five-pillar risk framework architecture |
| [Regulatory Alignment](#-regulatory-alignment--governance) | FATF, Wolfsberg, Basel, and supervisory mapping |
| [Intelligence Pillars](#-intelligence-pillars) | Jurisdictional, Product, and Customer risk modules |
| [Scoring Methodology](#-scoring-methodology) | Weighted aggregation and hard override logic |
| [Project Layout](#-project-layout) | Repository structure and file organization |
| [Quick Start](#-quick-start) | Installation and execution guide |
| [License & Disclaimer](#-license--disclaimer) | Terms of use and regulatory notice |

---

## 🚀 Executive Summary

**Global Sentinel** is a production-grade, modular **AML/CFT risk orchestration engine** engineered to automate the identification, quantification, and classification of financial crime threats. By fusing international regulatory indices with institutional behavioral telemetry, the framework delivers **explainable, deterministic risk scoring** across three core domains:

| Domain | Scope | Output |
|--------|-------|--------|
| **Customer (KYC/KYB)** | Identity, PEP, UBO structures | Risk Rating + EDD Triggers |
| **Product** | Service exploitability assessment | Residual Product Risk Score |
| **Jurisdictional (Country)** | Geography risk normalization | Inherent Geography Risk (IGR) |

Built to bridge the gap between **raw data engineering** and **regulatory intelligence**, Global Sentinel transforms disparate data points into actionable compliance insights. This ensures a robust **Risk-Based Approach (RBA)** that is fully aligned with the expectations of global standard-setters and supervisory authorities.

---

### **System Architecture Overview**

Global Sentinel operates as a **high-throughput multi-stage pipeline** designed to ingest and harmonize heterogeneous **CSV and JSON data feeds**. The system normalizes raw regulatory inputs into structured risk matrices, executing a sophisticated **Weighted Scoring Engine** that evaluates risk across **six distinct pillars** of financial crime vulnerability.

Unlike *"black-box"* solutions, Global Sentinel prioritizes **explainability** — ensuring that every risk rating is backed by a transparent audit trail of specific risk factors and mitigating controls.

---

### **Enterprise-Scale Resilience**

The framework is architected for **high-cardinality datasets**, providing the computational power required for complex entity resolution and periodic portfolio reviews.

| Metric | Volume | Completion Time |
|--------|--------|-----------------|
| **Unique Customer Profiles** | 200,000+ | ~2 minutes |
| **Product-Account Relationships** | 1.1 Million+ | ~2 minutes |
| **Data Points Processed** | Comprehensive PII, UBO, KYB hierarchies | Batch-optimized |

**Tested Capabilities:**
- ✅ Comprehensive identity mapping including **PII**, **UBO (Ultimate Beneficial Ownership)** structures, and **KYB entity hierarchies**
- ✅ Complex **1:N relational node mapping** to detect risk propagation across product lines and nested accounts

---

### **Precision Risk Decisioning**

At the core of the system is the **Master Risk Engine**, a hybrid decision-making layer that balances granular quantitative weighting with a **Zero-Tolerance Hard Override Logic**.

| Component | Function | Regulatory Benefit |
|-----------|----------|-------------------|
| **Weighted Aggregation** | Tunable engine based on institution's **Risk Appetite Statement (RAS)** | Customizable risk weighting for behavior, channel, jurisdiction |
| **Deterministic Guardrails** | Non-dilutable triggers for critical high-risk indicators | Absolute regulatory safety and defensible **SAR/STR** posture |

**Hard Override Triggers:**
- 🚫 **Sanctions Nexus**
- 🚫 **Foreign PEP Exposure**
- 🚫 **Shell Bank Status**
- 🚫 **Opaque Beneficial Ownership**

By bypassing weighted averages when critical threats are detected, the system maintains **absolute regulatory safety**, **institutional integrity**, and a **defensible posture** for **SAR/STR filing** and internal audits.

---

## 🛡️ Core Capabilities & Risk Framework

Global Sentinel's architecture is built on the principle of **Defensible Logic**. Each capability is designed to ensure that the transition from raw data to a Risk Rating is **transparent**, **documented**, and fully aligned with the **Risk-Based Approach (RBA)**.

---

### 1️⃣ Dynamic Jurisdictional Orchestration

| Feature | Implementation | Outcome |
|---------|----------------|---------|
| **Inherent Geography Risk (IGR)** | Merges **Basel AML Index** + **Transparency International CPI** | Unified 1–10 jurisdictional risk scale |
| **FATF Status Multipliers** | 1.5× (Grey-listed) / 2.0× (Black-listed) | Immediate portfolio-wide re-rating |
| **Event-Driven Updates** | Automated re-calculation on FATF designation changes | Real-time compliance posture |

---

### 2️⃣ Multi-Dimensional Product Risk Taxonomy

| Component | Description |
|-----------|-------------|
| **Inherent Risk Factors (RF)** | Cash-intensity, anonymity, settlement finality |
| **Mitigating Factors (MF)** | Transaction limits, mandatory face-to-face onboarding |
| **Output** | Granular **Residual Product Risk** score reflecting true institutional exposure |

---

### 3️⃣ Six-Pillar Weighted Scoring Engine

The engine executes simultaneous evaluation across **six critical pillars** for a 360-degree risk profile view:

| Pillar | Weight | Risk Dimension |
|--------|--------|----------------|
| **Geography** | 1.4 | Macro-jurisdictional exposure |
| **Product** | 1.2 | Inherent vulnerability of service utilized |
| **Channel** | 0.8 | Delivery method risk (Non-F2F vs. Branch) |
| **Identity** | 1.0 | Entity transparency and complexity |
| **Behavior** | 1.5 | Transactional velocity, volume, and value deviations |
| **KYC Status** | 1.1 | Verification integrity and due diligence completeness |

---

### 4️⃣ Deterministic "Hard Override" Guardrails

To prevent **Risk Dilution** — a common failure where a critical threat is *"averaged out"* by low-risk data — the system employs **non-dilutable triggers**.

| Override Condition | Forced Classification | Regulatory Rationale |
|--------------------|----------------------|---------------------|
| Sanctions Nexus | **High-Risk (10.0)** | Zero-tolerance for prohibited counterparties |
| Foreign PEP Status | **High-Risk (10.0)** | Enhanced corruption exposure |
| Shell Bank Indicator | **High-Risk (10.0)** | FATF Recommendation prohibition |
| Opaque Ownership Structure | **High-Risk (10.0)** | UBO transparency requirement |

---

### 5️⃣ Audit Transparency & Explainability

| Feature | Implementation | Audit Benefit |
|---------|----------------|---------------|
| **Override Reason Tracking** | Immutable `override_reason` field | Full decision provenance |
| **Provenance Metadata** | Timestamped risk factor attribution | Internal/external examination readiness |
| **Manual Adjustment Logging** | All overrides captured with user ID | SAR/STR filing evidence |

---

## 🏛️ Regulatory Alignment & Governance

The scoring logic, weighting factors, and override triggers within Global Sentinel are meticulously mapped to internationally recognized **AML/CFT standards**. This alignment ensures that the framework remains **audit-ready** and provides a defensible methodology during regulatory examinations or independent third-party audits.

---

### 📜 FATF (Financial Action Task Force): The Global Gold Standard

| Standard | Implementation |
|----------|----------------|
| **Risk-Based Approach (RBA)** | Core architecture principle |
| **40 Recommendations** | Full operational coverage |
| **Recommendation 19 (Higher-Risk Countries)** | Automated Black/Grey list multipliers |

**Key Benefit:** The system doesn't just *"flag"* jurisdictions — it **mathematically adjusts risk weights in real-time** as FATF designations shift.

---

### 🏦 The Wolfsberg Group: Correspondent Banking & Sanctions Effectiveness

| Principle | Implementation |
|-----------|----------------|
| **AML Principles** | Integrated into Product Risk Taxonomy |
| **Correspondent Banking Guidance** | "Anonymity" and "Settlement Finality" weighted as key vulnerabilities |
| **Sanctions Screening Effectiveness** | Hard-override logic ensures zero-tolerance for prohibited counterparty nexus |

---

### 📊 Basel Institute on Governance: Jurisdictional Health Metrics

| Metric | Purpose |
|--------|---------|
| **Basel AML Index** | Evaluates country AML/CFT framework quality |
| **Bribery/Corruption Risk** | Identifies systemic institutional vulnerabilities |
| **Financial Transparency** | Measures regulatory enforcement effectiveness |

---

### 🔍 Transparency International: Corruption Perception Index (CPI) Normalization

| Function | Output |
|----------|--------|
| **CPI Normalization** | Converts to 1–10 risk scale |
| **Public Sector Corruption Detection** | Identifies environments facilitating large-scale money laundering |
| **State Resource Misappropriation Risk** | Elevated risk scoring for high-corruption jurisdictions |

---

### 🌐 Regional Supervisory Expectations

| Jurisdiction | Regulatory Framework |
|--------------|---------------------|
| **United States** | Bank Secrecy Act (BSA), FinCEN Guidelines |
| **United Kingdom** | Money Laundering Regulations, FCA Expectations |
| **Singapore** | MAS Technology Risk Management Guidelines |
| **Hong Kong** | HKMA AML/CFT Supervisory Requirements |

**Modular Configuration:** The engine's architecture allows fine-tuning of thresholds to meet specific local requirements.

---

## 🧩 Intelligence Pillars

---

## 1. Jurisdictional (Country) Risk Intelligence

> **Module:** `Country_Risk_Rating.py`

This module transforms **qualitative regulatory intelligence** into a quantitative **Inherent Geography Risk (IGR)** score. By normalizing disparate global indices, the engine produces a **unified 1–10 jurisdictional risk scale** that is both **objective and audit-ready**.

---

### Jurisdictional Risk Formula

The module applies a **weighted composite methodology**, ensuring that systemic AML vulnerabilities and corruption exposure are balanced against a jurisdiction's **formal regulatory standing**.

$$IGR = \text{Normalized}(\text{Basel AML Index} + \text{CPI Score}) \times \text{FATF Multiplier}$$

---

### Data Fusion & Normalization

| Data Source | Evaluation Criteria | Output |
|-------------|---------------------|--------|
| **Basel AML Index** | Financial transparency, bribery/corruption exposure, institutional enforcement effectiveness | Technical baseline for jurisdictional risk health |
| **Corruption Perceptions Index (CPI)** | Public sector corruption facilitating money laundering, misappropriation of state resources, regulatory capture | Normalized 1–10 risk scale |

---

### Dynamic FATF Multipliers

Aligned with **FATF Recommendation 19 (Higher-Risk Countries)**, the module applies **automated jurisdictional multipliers** based on formal FATF status.

| FATF Status | Multiplier | Action Triggered |
|-------------|------------|------------------|
| **Grey List (Increased Monitoring)** | 1.5× | Proactive elevation to High-Risk posture + mandatory EDD |
| **Black List (Call for Action)** | 2.0× | Capped at maximum risk score (10.0) + strict institutional controls |

---

### Compliance Outcome

| Capability | Benefit |
|------------|---------|
| **Event-Driven Risk Reviews** | Automatic reassessment on FATF classification changes |
| **Automated EDD Triggers** | Immediate enhanced due diligence for high-risk jurisdictions |
| **Dynamic Re-Rating** | Rapid portfolio-wide risk adjustment without manual intervention |

---

## 2. Product & Service Risk Taxonomy

> **Module:** `Product_Risk_Calculator.py`

This module quantifies the specific **exploitability of financial instruments and services**. It moves beyond static product classifications by implementing a **net-vulnerability assessment** that balances inherent product risks against the institution's active control environment.

---

### The Net-Risk Equation

The module operates on a **Residual Risk formula**, ensuring that product risk is never evaluated in isolation:

$$\text{Residual Product Risk} = (\text{Inherent Risk Factors}) - (\text{Mitigating Control Effectiveness})$$

---

### Inherent Risk Factors (RF)

The engine evaluates **19 distinct risk indicators** to determine how easily a product could be exploited for **money laundering or terrorist financing**.

| Category | Indicators |
|----------|------------|
| **Anonymity & Complexity** | Non-face-to-face onboarding, bearer instruments, complex ownership structures |
| **Liquidity & Velocity** | Rapid value transfer, quick conversion to cash or liquid assets |
| **Cross-Border Reach** | International value transfer, higher-risk jurisdiction exposure |

---

### Mitigating Factors (MF) & Controls

To prevent inflated risk classifications, the system incorporates **12 internal control layers** designed to reduce product vulnerability.

| Control Type | Examples |
|--------------|----------|
| **Transactional Thresholds** | Hard limits on transaction volume or value |
| **Onboarding Stringency** | Enhanced KYC, mandatory in-person verification |
| **Monitoring Intensity** | Frequency and depth of automated transaction monitoring |

---

### Compliance Outcome

| Benefit | Description |
|---------|-------------|
| **Granular Net-Risk Scoring** | Justifies continued use of inherently high-risk services |
| **Control Effectiveness Demonstration** | Shows internal controls reduce underlying risk to acceptable levels |
| **Audit-Ready Documentation** | Supports regulatory examination of high-risk product offerings |

**Applicable Services:** Trade Finance, Correspondent Banking, Private Banking, Crypto-Asset Services

---

## 3. Customer & Behavioral Risk Profiling

> **Module:** `risk_engine.py`

This module serves as the **final integration layer**, synthesizing **identity-based risk indicators** with **real-world activity telemetry**. By evaluating both **how a customer enters the ecosystem** and **how they interact with it**, the engine transitions from static *"paper-based"* risk assessments to **dynamic behavioral intelligence**.

---

### Critical Risk Vectors

The engine evaluates the customer across **three primary risk lenses** to determine the likelihood of illicit activity.

---

### 🎯 Politically Exposed Persons (PEP) & Entity Status

| Classification | Risk Weight | Control Requirement |
|----------------|-------------|---------------------|
| **Domestic PEPs** | Elevated | Enhanced monitoring |
| **Foreign PEPs** | Maximum | Hard override trigger |
| **Relatives & Close Associates (RCAs)** | Elevated | Enhanced due diligence |
| **High-Risk Corporate Affiliations** | Variable | Entity-level assessment |

---

### 📍 Onboarding & Delivery Channel Analysis

Risk exposure is significantly influenced by **how the customer relationship is established**.

| Channel | Risk Premium | Rationale |
|---------|--------------|-----------|
| **Face-to-Face (Branch)** | Baseline | Direct identity verification |
| **Non-Face-to-Face (Digital/Remote)** | Elevated | Identity verification challenges, synthetic identity fraud risk |
| **Third-Party Introduction** | Variable | Reliance on external due diligence |

---

### 📈 Transactional Intensity & Velocity Patterns

| Signal | Detection Logic | Typology Indicator |
|--------|-----------------|-------------------|
| **Velocity** | Rapid movement of funds in/out without economic purpose | Layering, integration |
| **Intensity** | High volumes of cash-equivalent transactions | Structuring, smurfing |
| **Threshold Proximity** | Repeated transactions near reporting limits | Deliberate avoidance of CTR/STR |

---

### Final Risk Classification

| Risk Category | Periodic Review Cycle | EDD Requirement | Monitoring Intensity |
|---------------|----------------------|-----------------|---------------------|
| **Low Risk** | 24–36 months | Standard | Baseline |
| **Medium Risk** | 12–18 months | Enhanced | Elevated |
| **High Risk** | 6–12 months | Mandatory | Continuous |

---

## ⚙️ Scoring Methodology

The final **Residual Risk Score** is derived from two distinct logic layers.

---

## Weighted Base Score

Six core pillars are evaluated using weighted scoring:

| Pillar | Weight | Description |
|--------|--------|-------------|
| **Geography** | 1.4 | Macro-jurisdictional exposure |
| **Product** | 1.2 | Inherent vulnerability of service utilized |
| **Behavior** | 1.5 | Transactional velocity, volume, and value deviations |
| **Identity / Customer Type** | 1.0 | Entity transparency and complexity |
| **KYC Control Strength** | 1.1 | Verification integrity and due diligence completeness |
| **Channel Risk** | 0.8 | Delivery method risk (Non-F2F vs. Branch) |

---

## Hard Overrides (Non-Dilutable)

If a record satisfies an override condition (for example `media_status == "Sanctions"`), the system **forces the score to 10.0**, bypassing the weighted scoring mechanism.

```python
# Hard Override Logic Example
if media_status == "Sanctions" or pep_status == "Foreign_PEP":
    final_risk_score = 10.0
    override_reason = "CRITICAL_HIGH_RISK_TRIGGER"
    bypass_weighted_calculation = True
```

**Regulatory Rationale:** This ensures **critical compliance risks cannot be diluted by statistical averaging**.

---

## 📂 Project Layout

```
Global-Sentinel/
├── Data/
│   ├── Table1_Core_Customer_Data.csv       # PII & Demographics (200k rows)
│   ├── Table2_Account_Product_Data.csv     # Relational Product Map (1.1M rows)
│   ├── Table3_Transactional_Summary.csv    # Behavioral Patterns
│   ├── Table4_Compliance_Screening.csv     # PEP / Sanctions / Media Flags
│   ├── Countries.json                      # Master Country List
│   ├── Product_Risk_Factors.json           # RF/MF Weighting Logic
│   └── FATF_Lists.json                     # Black / Grey List Source
├── Country_Risk_Rating.py                  # Geography Risk Orchestrator
├── Product_Risk_Calculator.py              # Product Vulnerability Scorer
├── generate_table1.py                      # Synthetic Customer Generator
├── generate_table2.py                      # Relational Account Generator
└── risk_engine.py                          # Master Scoring & Override Engine
```

---

## ⚡ Quick Start

### 1. Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/Global-Sentinel.git
cd Global-Sentinel

# Install dependencies
pip install pandas numpy
```

---

### 2. Execute Data Pipeline

```bash
# Calculate Jurisdictional and Product Risk Baselines
python Country_Risk_Rating.py
python Product_Risk_Calculator.py

# Run the final risk assessment
python risk_engine.py
```

---

### 3. Review Results

The final classifications are exported to:

```
Data/Final_Customer_Risk_Rating.csv
```

| Field | Description |
|-------|-------------|
| `customer_id` | Unique entity identifier |
| `final_risk_score` | Normalized 0–10 risk rating |
| `risk_category` | Low / Medium / High classification |
| `override_reason` | Specific trigger for audit transparency |
| `review_due_date` | Next periodic review deadline |

**Audit Feature:** Each record includes the specific `override_reason` field, enabling **full audit transparency and traceability**.

---

## ⚖️ License & Disclaimer

### License

Distributed under the **Apache License 2.0**.

| Permission | Status |
|------------|--------|
| Commercial Use | ✅ Permitted |
| Modification | ✅ Permitted |
| Distribution | ✅ Permitted |
| Private Use | ✅ Permitted |
| Patent Rights | ✅ Explicit grant from contributors |

---

### ⚠️ Regulatory Disclaimer

> **This framework uses synthetic data and is intended for RegTech architectural modeling and experimentation.**

| Notice | Requirement |
|--------|-------------|
| **Legal/Regulatory Advice** | This framework does **not** constitute legal, regulatory, or compliance advice |
| **Jurisdictional Adaptation** | Must be adapted to applicable jurisdictional requirements before production deployment |
| **Model Validation** | Independent model risk management (MRM) validation required for production use |
| **Regulatory Approval** | Consult with local supervisory authorities before implementation |

---

## 📬 Contact & Support

| Role | Details |
|------|---------|
| **Repository** | [GitHub](https://github.com/YOUR_USERNAME/Global-Sentinel) |
| **Issues** | [Open an Issue](https://github.com/YOUR_USERNAME/Global-Sentinel/issues) for bugs, feature requests, or compliance queries |
| **Contributions** | Pull requests welcome for new typology rules, jurisdictional data sources, and ML model integrations |

---

> **Built for Compliance. Engineered for Scale. Designed for Transparency.**

---

| Badge | Status |
|-------|--------|
| **FATF RBA Compliant** | ✅ |
| **Explainable AI (XAI)** | ✅ |
| **Audit-Ready Logging** | ✅ |
| **Hard Override Guardrails** | ✅ |
| **Dynamic FATF Integration** | ✅ |

---

© 2026 **Global Sentinel Framework** | AML/CFT Risk Intelligence Engine | Apache License 2.0

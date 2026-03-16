# 🛡️ Global Sentinel: Multi-Tiered AML/CFT Risk & Intelligence Framework

An end-to-end Pythonic implementation of algorithmic risk scoring, bridging the gap between regulatory theory and enterprise-scale data engineering.

---

## 🚀 Overview
Global Sentinel is an advanced, high-performance risk-rating ecosystem designed to automate the identification of financial crime threats across **200,000+ customer profiles** and **1.1 million product nodes**.

This framework doesn't just calculate scores; it simulates a sophisticated **Regulatory Compliance Layer** that mirrors the rigorous requirements of global standard-setters and top-tier financial regulators. By integrating **KYC (Know Your Customer)**, **KYB (Know Your Business)**, and **Sanctions Screening**, the system provides a holistic 360-degree view of institutional risk.

---

## 🏛️ Regulatory Alignment & Standards
The scoring logic and methodology are engineered to align with the risk-based approach (RBA) advocated by:

- **FATF (Financial Action Task Force):** 40 Recommendations on AML/CFT  
- **The Wolfsberg Group:** Standards on Anti-Money Laundering and Sanctions Screening  
- **JMLSG (Joint Money Laundering Steering Group):** Guidance for the UK financial sector  
- **FinCEN & EU AML Directives (6AMLD):** Adherence to UBO transparency and high-risk jurisdiction monitoring  

---

## 🧩 The Three Pillars of Intelligence

### 1. 🌍 Macro-Jurisdictional Assessment (`Country_Risk_Rating.py`)
- **Data Fusion:** Aggregates Transparency International’s CPI, Basel AML Index, FATF Greylist/Blacklist status  
- **Logic:** Normalization algorithms transform qualitative data into a quantitative **Inherent Geography Risk Score (1–10)**  

### 2. 💳 Product & Service Risk Taxonomy (`Product_Risk_Calculator.py`)
- **Risk Factors:** Liquidity, Anonymity, Velocity of Funds, Cross-Border Capability  
- **Assessment:** Distinguishes low-risk retail products (e.g., Term Deposits) vs high-risk vehicles (e.g., Correspondent Banking, Crypto-assets, Trade Finance)  

### 3. 👤 Comprehensive Customer Risk Engine (`risk_engine.py`)
- **Weighted Pillar Scoring:** Geography (1.4x), Behavior (1.5x), Product (1.2x)  
- **Compliance Overrides:** Foreign PEPs, Sanctions Hits, Shell Banks, Opaque UBO structures → automatically High-Risk  

---

## 🛠️ Technical Prowess (Under the Hood)
- **Relational Integrity:** Vectorized pandas joins across a 4-table schema  
- **Auditability by Design:** Every decision stamped with `override_reason` for transparent audit trails  
- **Scalability:** Handles high-cardinality datasets, simulating mid-to-large-scale digital bank throughput  
- **Modular Architecture:** Rating Matrices (JSON) separated from Execution Logic (Python) for real-time updates  

---

## 📂 Project Anatomy
```
.
├── Data/                          
│   ├── Table1_Core_Customer_Data.csv      # PII & KYB Demographics
│   ├── Table2_Account_Product_Data.csv    # Relational 1:N Product Nodes
│   ├── Table3_Transactional_Summary.csv   # Behavioral & Cash Intensity Data
│   ├── Table4_Compliance_Screening.csv    # PEP/Sanctions/Adverse Media
│   ├── Country_Risk_Rating.json           # Aggregated Geography Matrix
│   ├── Product_Risk_Rating.json           # Product Risk Taxonomy
│   └── Basel_Index.json / FATF_Lists.json # Raw Regulatory Source Feeds
├── Country_Risk_Rating.py                 # Macro-Risk Orchestrator
├── Product_Risk_Calculator.py             # Product Vulnerability Scorer
└── risk_engine.py                         # Final Residual Risk Processor
```

---

## ⚡ Quick Start
```bash
# Clone the intelligence suite
git clone https://github.com/YOUR_USERNAME/Global-Sentinel.git

# Install dependencies
pip install -r requirements.txt

# Execute the full rating cycle
python risk_engine.py
```

---

## 🌍🔒 Disclaimer
This project is a demonstration of advanced RegTech capabilities using **synthetic data**. It represents a commitment to building a safer financial world through data science and rigorous compliance engineering.
```

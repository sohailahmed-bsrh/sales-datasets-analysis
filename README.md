# Multi-Channel Sales Dataset Analytics & Commercial Intelligence

<p align="center">
  <a href="https://sohail.devsil.com"><strong>Portfolio</strong></a> | 
  <a href="https://github.com/sohailahmed-bsrh"><strong>GitHub Profile</strong></a> | 
  <a href="https://github.com/sohailahmed-bsrh/sales-datasets-analysis"><strong>Source Repository</strong></a>
</p>

---

## Executive Summary & Problem Statement

Commercial retail and omnichannel distributors process high-volume point-of-sale (POS) and online order datasets. Identifying operational bottlenecks, inventory turnover inefficiencies, and pricing inelasticity across disparate retail regions requires a unified data analytics framework.

This project implements a comprehensive **Multi-Channel Sales Dataset Analytics Pipeline**. Designed for retail managers and business intelligence analysts, it automates exploratory data analysis (EDA), basket size distribution modeling, margin tracking, and statistical hypothesis verification.

<div align="center">
  <img src="https://raw.githubusercontent.com/sohailahmed-bsrh/myportfolio/main/assets/images/thumbnail/sales-data-analysis.jpeg" width="650" alt="Sales Datasets Analytics"/>
  <p><em>Commercial intelligence pipeline for multi-channel transaction analysis and demand modeling.</em></p>
</div>

---

## Real-World Industry Applications

- **Omnichannel POS Analytics**: Harmonizes in-store point-of-sale receipts with digital e-commerce transactions.
- **Market Basket Analysis**: Identifies co-purchased product pairs to optimize shelf layouts and cross-sell promotional bundles.
- **Discount & Elasticity Modeling**: Measures the correlation between promotional discount depth and net profit margins.
- **Supply Chain Fulfillment Auditing**: Tracks fulfillment turnaround times from order creation to delivery across regions.

---

## Technical Architecture & Engineering Walkthrough

```
                    [Multi-Source Transactional Datasets]
                                      │
                                      ▼
                   [Schema Harmonization & Data Cleaning]
                 (Type Casting, Currency Conversion, Deduplication)
                                      │
         ┌────────────────────────────┼────────────────────────────┐
         ▼                            ▼                            ▼
[Sales Velocity Tracking]   [Market Basket Affinity]     [Regional Heatmapping]
(Transaction Velocity)      (Itemset Association)       (Geographical Distribution)
         │                            │                            │
         └────────────────────────────┼────────────────────────────┘
                                      │
                                      ▼
             [Actionable Business Intelligence Dashboard Reports]
```

### Step 1: Ingestion & Schema Alignment
Normalizes disparate retail data schemas, resolves missing values, and enforces consistent transaction timestamps across timezones.

### Step 2: Distribution Diagnostics
Examines transaction distribution skews using kernel density estimation (KDE), log transformations, and interquartile range (IQR) outlier isolation.

### Step 3: Basket Affinity Analysis
Analyzes itemset frequencies and calculates transaction support, confidence, and lift metrics to discover cross-merchandising product pairs.

### Step 4: Pricing Elasticity & Margin Evaluation
Models relationship between price markdowns and sales volume to determine whether promotional discounting generates accretive gross profit.

### Step 5: Reporting & Visual Dashboards
Generates visual executive summaries featuring categorical breakdown charts, geographical heatmaps, and sales channel contribution comparisons.

---

## Technology Stack & Implementation Specifications

| Component | Technology | Version | Architectural Function |
| :--- | :--- | :--- | :--- |
| **Data Engine** | Pandas / Python | 2.x | High-speed data wrangling, grouping, and pivots |
| **Mathematics** | NumPy | Latest | Array computations and statistical functions |
| **Plotting Suite** | Matplotlib / Seaborn | 3.8+ | Publication-quality statistical visualizations |
| **Notebook Runtime** | JupyterLab | Latest | Reproducible and interactive computational environment |

---

## Installation & Execution Guide

```bash
git clone https://github.com/sohailahmed-bsrh/sales-datasets-analysis.git
cd sales-datasets-analysis
python -m venv venv
# Windows: venv\Scriptsctivate | Unix: source venv/bin/activate
pip install -r requirements.txt
```

---

## Author & Contact Information

<table width="100%">
  <tr>
    <td width="150" align="center" valign="middle">
      <img src="https://avatars.githubusercontent.com/u/231165170?v=4" width="120" style="border-radius: 50%;" alt="Sohail Ahmed"/>
    </td>
    <td>
      <h3>Sohail Ahmed</h3>
      <p><strong>Senior Software Engineer & AI Systems Architect</strong></p>
      <p>Specializing in Full-Stack AI Application Development, Computer Vision, Deep Learning Pipelines, and Scalable Automation Architectures.</p>
      <p>
        <a href="https://sohail.devsil.com"><strong>Portfolio Website</strong></a> | 
        <a href="https://github.com/sohailahmed-bsrh"><strong>GitHub Profile</strong></a> | 
        <a href="https://www.linkedin.com/in/sohail-ahmed-546314316/"><strong>LinkedIn</strong></a> | 
        <a href="mailto:se906403@gmail.com"><strong>Email Contact</strong></a>
      </p>
    </td>
  </tr>
</table>

# Loan-Default-Analysis-Ghanaloanconnect
Data analysis and machine learning project to predict and reduce loan defaults in Ghana's lending sector

# Loan Default Analysis: Ghana Lending Sector

![GitHub](https://img.shields.io/badge/Python-3.8%2B-blue)
![GitHub](https://img.shields.io/badge/Status-Completed-brightgreen)
![GitHub](https://img.shields.io/badge/AI-ML%20Analysis-orange)

## 📋 Project Overview

This data analytics project addresses the critical challenge of loan defaults in Ghana's non-bank financial institution (NBFI) sector. GhanaLoanConnect, a peer-to-peer lending platform, faces a 16.01% default rate—significantly above industry standards—threatening its sustainability and financial inclusion mission.

## 🎯 Business Objectives

1. **Identify High-Risk Segments**: Pinpoint sectors and borrower profiles with the highest default probability
2. **Diagnose Root Causes**: Analyze factors driving repayment difficulties  
3. **Develop Mitigation Strategies**: Recommend data-driven interventions to reduce defaults by 20%

## 💡 Key Insights & Impact
Analysis of 9,578 loan records revealed critical risk patterns:

*   **Small Business loans** showed the highest vulnerability with a **28% default rate**, followed by Educational loans at **20%**
*   **Credit scores** demonstrated strong predictive power - borrowers with FICO 600-649 had a **32% default rate** vs **7%** for 750+
*   **Interest rate correlation** was evident - loans >15% interest had **24.8% default rate** vs **4.2%** for rates <8%
*   **Machine learning model** achieved **84% accuracy** in predicting high-risk borrowers

## 🚀 Recommendations & Implementation
A phased strategy was developed to transform risk management:

1.  **Risk-Based Pricing:** Implement tiered interest rates (8%-18%) based on borrower risk profiles
2.  **Sector-Specific Underwriting:** Apply enhanced due diligence for Small Business and Educational loans
3.  **Automated Decision Systems:** Integrate ML model to flag high-risk applicants and reduce processing time by 65%
4.  **Portfolio Diversification:** Rebalance toward lower-risk segments (Major Purchases: 11% default, Credit Cards: 12%)

## 📈 Expected Business Impact
- **Default Reduction:** From 16.01% to ~13% (20% improvement)
- **Financial Savings:** GHC 6.3 million annually with 225% ROI
- **Payback Period:** 3.7 months
- **Operational Efficiency:** 65% faster loan processing

## 📁 Project Deliverables
*   **[Case Study Analysis](docs/case_study.md)** - Comprehensive business analysis and methodology
*   **[Data Analysis Notebooks](notebooks/)** - Jupyter notebooks with exploratory analysis and modeling
*   **[Predictive Models](src/)** - Python implementation of logistic regression model
*   **[Visual Dashboards](reports/figures/)** - Key insights and performance metrics

### Tools & Technologies
- **Python**: Pandas, Scikit-learn, Matplotlib
- **Machine Learning**: Logistic Regression (84% accuracy)
- **Visualization**: Power BI, Excel dashboards
- **Analysis**: EDA, correlation studies, predictive modeling

### Project Structure
loan-default-analysis-ghana/
├── data/                 # Raw and processed datasets
├── notebooks/            # Jupyter notebooks for analysis
├── src/                  # Python scripts for modeling
├── reports/              # Visualizations and dashboards
├── docs/                 # Case study and documentation
└── README.md            # Project overview

Walmart AI Risk Assessment & Predictive Analysis
This repository presents a comprehensive risk analysis project focused on Walmart’s adoption of AI technologies in its supply chain and logistics systems. It includes qualitative risk identification, quantitative severity prediction using machine learning, and visual risk heatmaps — offering a full pipeline from stakeholder-level impact assessment to actionable predictive insights.

Project Objective
The goal is to assess potential risks (both negative and positive) arising from the use of AI in Walmart's evolving supply chain ecosystem, then visualize and predict these risks using analytical and machine learning techniques. This ensures data-driven risk prioritization to support smarter governance and strategic planning.

Contents
risk_register.xlsx
→ Exhaustive list of identified risks for Walmart AI adoption, with likelihood and impact scores.

RiskHeatmap_Generated.ipynb
→ Generates static and interactive heatmaps of risk likelihood vs. impact.

RiskRigester&Quant_Risk.ipynb
→ Performs quantitative predictive analysis:

Trains a Random Forest Classifier on labeled risk data.

Predicts severity levels (Low, Medium, High).

Outputs classification report, confusion matrix, and feature importance.

/images/
→ Contains generated plots like heatmaps and confusion matrices.

Analysis Highlights
Qualitative Risk Categorization
Risks classified by source: Tech limitations, Vendor dependency, Regulatory compliance, Workforce challenges, etc.

Risk levels mapped based on Likelihood and Impact scores (scale: 1–9).

Heatmap Visualization
A risk matrix shows distribution of risks across severity zones.

High-risk areas are easily spotted in red zones of the heatmap.

Machine Learning Model
Model: Random Forest Classifier

Inputs: Likelihood, Impact, and derived features

Target: Risk severity category (Low, Medium, High)

Metrics:

Accuracy: ~90%

Weighted F1-score: ~0.90

How to Use
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/walmart-risk-ai.git
cd walmart-risk-ai
Launch Google Colab or Jupyter Notebook.

Open the notebooks in order:

RiskHeatmap_Generated.ipynb for visual mapping

RiskRigester&Quant_Risk.ipynb for ML-based analysis

Run all cells — required packages will be auto-imported.

Insights
Predictive models can support early identification of high-severity risks.

AI risks are not just technical — regulatory and human-centric risks dominate.

Combining qualitative + quantitative approaches improves decision confidence.

🛠️ Tech Stack
Python (Pandas, Matplotlib, Seaborn, Scikit-Learn)

Jupyter Notebook / Google Colab

Excel for structured risk logging

References
Walmart Canada Supply Chain News:
Walmart Canada’s supply chain gets a high-tech makeover: how we’re embracing robotics and automation. (2024, March 21). https://www.walmartcanada.ca/news/2024/03/21/walmart-canada-s-supply-chain-gets-a-high-tech-makeover--how-we-
Frazer, J. (2025, March 19). Walmart and the new supply chain Reality: AI, automation, and resilience. Logistics Viewpoints. https://logisticsviewpoints.com/2025/03/19/walmart-and-the-new-supply-chain-reality-ai-automation-and-resilience/
Walmart Commerce Technologies launches AI-Powered Logistics Product. (2024, March 14). https://corporate.walmart.com/news/2024/03/14/walmart-commerce-technologies-launches-ai-powered-logistics-product


# Walmart AI Risk Assessment & Predictive Analysis

This repository presents a comprehensive risk assessment project focused on **Walmart’s use of AI in supply chain and logistics**. It combines qualitative evaluation with quantitative predictive modeling to identify, visualize, and classify the severity of operational, technical, and compliance-related risks.


## Project Objective

The goal is to assess potential risks (both negative and positive) arising from the use of AI in Walmart's evolving supply chain ecosystem, then visualize and predict these risks using analytical and machine learning techniques. This ensures data-driven risk prioritization to support smarter governance and strategic planning.

To assess and predict potential risks associated with Walmart’s AI-driven operations. The project includes:

- A detailed **risk register** with Likelihood and Impact scores.
- A **risk heatmap** to visualize severity.
- A **machine learning model** (Random Forest) to predict risk levels (Low, Medium, High).


## Project Structure

```bash
├── risk_register.xlsx                # Raw data with identified Walmart risks
├── RiskHeatmap_Generated.ipynb      # Risk heatmap generation using seaborn & plotly
├── RiskRigester&Quant_Risk.ipynb    # ML model training and quantitative risk classification
├── images/                          # Visualizations (confusion matrix, heatmaps)
└── README.md                        # Project overview (this file)
```


## Key Features

### Qualitative Risk Identification
- Categorized 29+ AI-related risks (e.g., data privacy, vendor lock-in, bias in analytics).
- Rated on **Likelihood (1–9)** and **Impact (1–9)** scale.
- Mapped into **risk levels**: Low, Medium, High.

### Risk Heatmap Visualization
- Shows where risks cluster in terms of severity.
- Helps identify "hot zones" for mitigation.

### Predictive Modeling (Random Forest)
- **Input**: Likelihood & Impact
- **Output**: Predicted risk severity
- **Model Performance**:
  - Accuracy: ~90%
  - Weighted F1-score: ~0.90
  - Visualization: Confusion matrix, classification report
 
## Example Outputs

- Static and interactive **heatmaps** of risk distribution.
- A **confusion matrix** showing model performance.
- Feature importance chart for likelihood/impact.


## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/walmart-risk-ai.git
cd walmart-risk-ai
```

### 2. Open the notebooks

Use [Google Colab](https://colab.research.google.com/) or Jupyter Notebook:

- `RiskHeatmap_Generated.ipynb` for heatmaps
- `RiskRigester&Quant_Risk.ipynb` for ML-based prediction

### 3. Run all cells

All required libraries like `pandas`, `seaborn`, `scikit-learn` will be imported in the notebooks.

## Tech Stack

- **Python** (Pandas, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter/Colab** for notebooks
- **Excel** for structured data input
- **Plotly** for interactive heatmaps

## References

- [Walmart’s AI Logistics Overview](https://www.walmartcanada.ca/news/2024/03/21/walmart-canada-s-supply-chain-gets-a-high-tech-makeover--how-we-)
- [Logistics Viewpoints – Walmart AI Use Case](https://logisticsviewpoints.com/2025/03/19/walmart-and-the-new-supply-chain-reality-ai-automation-and-resilience/)
- [Corporate AI Announcements](https://corporate.walmart.com/news/2024/03/14/walmart-commerce-technologies-launches-ai-powered-logistics-product)


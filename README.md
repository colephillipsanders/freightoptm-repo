# Freight Cost & CO₂ Optimization Capstone

Welcome to the capstone project repository! This project uses FAF5 freight data to estimate transportation cost and emissions, compare mode choices (road, rail, intermodal), and explore multi-objective optimization strategies.

## 📁 Repository Structure

```
freightoptm-repo/
├── docs/                          # Written deliverables (PDFs)
│   ├── final_capstone_paper.pdf
│   ├── capstone_presentation.pdf
│   └── appendices.pdf
├── notebooks/                     # Jupyter notebooks for analysis
│   ├── faf5_preprocessing.ipynb
│   ├── mode_choice_model.ipynb
│   └── cost_co2_multiobjective.ipynb
├── data/                          # Datasets and CSV files
│   ├── faf5_subset_2024.csv
│   └── processed_features.csv
├── images/                        # Visualizations and plots
│   ├── mode_confusion_matrix.png
│   ├── cost_vs_emissions.png
│   └── corridor_analysis.png
├── index.html                     # Main project portfolio page
├── README.md                      # This file
└── .gitignore                     # Git ignore rules for Python/Jupyter
```

## 🚀 Getting Started

1. **Upload PDFs** to the `docs/` folder
   - Final capstone paper
   - Presentation slides
   - Appendices and ethnography

2. **Add Jupyter Notebooks** to the `notebooks/` folder
   - Data preprocessing and EDA
   - Mode choice classification models
   - Cost & CO₂ optimization experiments

3. **Store Datasets** in the `data/` folder
   - FAF5 preprocessed data
   - Feature-engineered datasets
   - Any derived or intermediate CSVs

4. **Include Visualizations** in the `images/` folder
   - Confusion matrices, ROC curves
   - Cost vs. emissions trade-off plots
   - Corridor-specific analysis charts

## 📋 Project Overview

**Title:** Bypassing Forecasting for Freight Cost & CO₂ Optimization

**Key Components:**
- **Data Source:** FAF5.7.1 freight flows (United States domestic regions)
- **Modes:** Road, Rail, Intermodal
- **Targets:** Cost per shipment, CO₂ emissions per tonne-km
- **Approach:** Random Forests for mode choice, regression for cost/emissions, multi-objective optimization

## 🔗 Links & References

- View the live portfolio: `index.html`
- All links in the portfolio are pre-configured to point to files in this repository
- Once you upload files, update the links if filenames differ from the defaults

## 📝 Notes

- This repo uses Git LFS for large CSV files (if needed)
- `.gitignore` is configured for Python, Jupyter, and common data science workflows
- You can link Jupyter notebooks directly to Google Colab using GitHub's Colab integration

---

**Last Updated:** April 2026  
**Status:** Repository initialized and ready for content upload

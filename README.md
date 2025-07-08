# cancer_survival_analysis

This is my first personal project to explore the cancer patterns of patients from simulated clinical data. The analysis applies ***Kaplan-Meier Estimators*** and ***Cox-Proportional hazards models*** to estimate survival times and identify significant prognostic factors.

--- 
## Objectives
- Estimate overall survival rates over time.
- Compare survival curves by gender and treatment type
- Identify variables associated with decreased survival
- Practice Survival analysis techniques using a realistic

  ---
  ## Methodology
  The following statistical methods and tools were used
  
  **Kaplan-Meier Survival Curves** (`survfit`)
- **Log-Rank Test** to compare groups
- **Cox Proportional Hazards Model** for multivariable analysis
- Visualizations with `survminer`, `ggplot2`

  ---
   ## Tools & Packages
  - `R`, `dplyr`, `survival`, `survminer`
- Dataset: Simulated (150 patients, realistic structure)
- All scripts written in `R`

---

## Project Structure
```bash
cancer-survival-analysis/
├── data/
│   └── simulated_cancer_survival.csv
├── scripts/
│   └── analysis.R
├── visuals/
│   └── km_gender_plot.png
├── README.md
└── report.qmd (summary report)

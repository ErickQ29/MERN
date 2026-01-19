 
   
#  Pharmaceutical Treatment Analysis in R

##  Description
Analysis of 1,000 patient records evaluating medication effectiveness,
side-effects, and treatment patterns using **R** and the **tidyverse**.

##  Dataset
- **Source**: Simulated for educational analysis 
- **Size**: 1,000 patients, 12 variables (9 original + 3 engineered)
- **Key variables**: Age, Gender, Condition, Medication, Dosage,
  Treatment Duration, Side-effects, Improvement Score (0–10)

##  Key Insights
- **Most effective medication**: Escitalopram (8.6/10)
- **Most common side-effect**: Nausea (23% of cases)
- **Pattern**: Older patients (>70 years) show greater variability in response
- **Optimal dosage**: No strong correlation between higher dosage and improvement (r = 0.12)

##  Technologies
- R 4.3+
- tidyverse (dplyr, ggplot2, readr)
- RSQLite for SQL-based analysis

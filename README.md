# International-Graduate-Students-Housing-Experience

📄 Full Report: [View Analysis](International Graduate Students Housing Experience.html)

## Overview
This mixed-methods study investigates the housing experiences of international graduate students in Kitchener/Waterloo, Canada, identifying financial strategies, demographic influences, and policy recommendations for sustainable, affordable housing. Drawing from a 2025 survey (N=125) and 25 interviews, findings reveal significant challenges: 47.2% faced high difficulty securing housing, 38.4% experienced instability, and 18.4% encountered discrimination, with 36.0% excluded due to international status. Coping strategies included shared housing (46.4%, 72.4% stability) and social support (65.6%), varying by region (e.g., Asia 73.8% social support) and gender (females 76.5%). Policy priorities emphasized affordability (53.0%), university support (12.0%), and anti-discrimination measures, informed by qualitative insights on rent burdens (“$800 for a shared room”) and biases (“rejections based on accent”). Recommendations propose rent subsidies, institutional guarantors, and landlord training to enhance stability (59.2%) and well-being, addressing systemic barriers for diverse student populations.

## Objectives
- Identify financial strategies and housing experiences of international graduate students in Kitchener/Waterloo (Objective 1, RQ1).
- Assess demographic influences, including cultural/racial elements, on housing choices and coping strategies (Objective 2, RQ2).
- Develop policy recommendations for sustainable and affordable housing to improve overall experiences (Objective 3, RQ3).

## Dataset Summary
- **Source**: Primary mixed-methods data from international graduate students in Kitchener/Waterloo, Canada (2025).
- **Sample Size**: 125 survey respondents; 25 semi-structured interviews.
- **Key Variables**: Demographics (gender, region, age, academic level); housing outcomes (stability, difficulty, discrimination, exclusion); strategies (shared housing, social/university support, unofficial housing); policy priorities (affordability, support, amenities).

## Methods
- Descriptive statistics (frequencies, percentages) and visualizations (bar plots, cross-tabulations) for profiling demographics and outcomes.
- Thematic analysis (Braun & Clarke, 2006) of interviews for qualitative insights, generating 35 codes grouped into 8 themes (e.g., affordability challenges, discrimination).
- Logistic regression for predictors (e.g., region on difficulty, OR=3.3 for Europe, p=0.039); chi-square for associations (e.g., gender vs. discrimination, p=1).

## Key Findings
- Demographics: Masters-dominant (71.2%), youthful (60.0% aged 18–25), African-majority (45.6%), male-majority (59.2%); balanced gender in Africa/Asia (47.4–50.0% female).
- Housing experiences (RQ1): 47.2% high difficulty, 38.4% unstable, 18.4% discrimination (racial 26.1%, student status 43.5%), 36.0% exclusion; qualitative: “$800 for a shared room” burdens, “accent” biases.
- Financial strategies (Objective 1): Shared housing (46.4%, 72.4% stable), social support (65.6%, 64.6% stable), unofficial (24.0%, 53.3% improved); multiple moves (26.4%) common.
- Demographic influences (Objective 2): Europe/Asia females highest disadvantage (1.8–2.0), Africa higher negative impact (29.8%); females prioritize safety (62.7%), social support (76.5%); cultural platforms (Asia 7.1%).
- Policy recommendations (Objective 3, RQ3): Affordability (53.0%), university support (12.0%), amenities/safety/space (10.0% each); qualitative: rent caps, landlord training, guarantors; co-occurrences: affordability + rent reduction (11).



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher) for quantitative; NVivo or manual coding for qualitative.
- RStudio
- R packages: tidyverse, ggplot2, dplyr, nnet (logistic regression), psych (correlations)

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio for quantitative; use NVivo for thematic coding.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "nnet"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). International Graduate Students Housing Experience.

# Head and Neck Cancer Survival Analysis

This project investigates clinical predictors of survival among head and neck cancer patients using data from The Cancer Imaging Archive. It employs Kaplan-Meier analysis, Cox Proportional Hazards modeling, and Random Survival Forests (RSF).

##  Models Used

- **Kaplan-Meier (KM):** Stratified by Sex and ECOG performance status
- **Log-Rank Tests:** Confirmed significant survival differences across ECOG groups (p < 0.001)
- **Cox Proportional Hazards Model:**
  - Included Age, Sex, ECOG
  - Concordance Index: 0.68
  - ECOG and Age were significant predictors
- **Random Survival Forests (RSF):**
  - C-index: 0.702
  - Top predictors: ECOG score and Smoking exposure


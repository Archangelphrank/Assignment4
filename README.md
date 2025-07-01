# Head and Neck Cancer Survival Analysis

This project investigates clinical predictors of survival among head and neck cancer patients using data from The Cancer Imaging Archive. It employs Kaplan-Meier analysis, Cox Proportional Hazards modeling, and Random Survival Forests (RSF).

##  Models Used

- **Kaplan-Meier (KM):** Stratified by Sex and ECOG performance status
- **Log-Rank Tests:** Confirmed significant survival differences across ECOG groups (p < 0.001)
- **Cox Proportional Hazards Model:**
  - Included Age, Sex, ECOG
  
  - ECOG and Age were significant predictors
-

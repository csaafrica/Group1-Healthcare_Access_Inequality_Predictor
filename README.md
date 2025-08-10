# Group1-Healthcare_Access_Inequality_Predictor
## Project Title and Objectives
## Project 2: Healthcare Access Inequality Predictor [Group 1]

**Problem Statement:** Identify underserved populations and predict healthcare access challenges to guide health facility placement.

**Data Sources:**
- 2019 Census data from Kenya National Bureau Of Statistics
- DHS Program StatCompiler: [DHS Program StatCompiler](https://www.statcompiler.com/)
- WHO Global Health Observatory: [Data portal](https://www.who.int/data)
- OpenStreetMap (health facility locations via Overpass API)

**Deliverables:**
1. Healthcare access score for each region (combining distance, facility density, health outcomes)
2. Classification model predicting low/medium/high healthcare access
3. Interactive map showing healthcare deserts
4. Technical report/policy brief on optimal locations for new health facilities

**Technical Requirements:**
- Calculate distance matrices using geopy
- Feature engineering: create accessibility indices
- Implement logistic regression and decision tree classifiers
- Use SHAP values to explain model predictions

---

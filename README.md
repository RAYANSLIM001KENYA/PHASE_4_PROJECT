# PHASE_4_PROJECT
this is for phase 4 project
# Unraveling Insights: Model Interpretability in Chicago Traffic Crashes Data
**Project Overview**
This project analyzes Chicago traffic crash data to predict crash outcomes using machine learning models. The goal is to identify key contributing factors, improve model interpretability using SHAP and LIME, and provide actionable insights for policy interventions.

**Dataset**
- Source: Chicago Traffic Crashes Dataset
- Shape: (915,366 rows, 48 columns)
- Contains: Crash conditions, vehicle details, environmental factors.
  
**Objectives**
- Data Exploration & Cleaning – Handling missing values and ensuring consistency.
- Feature Engineering – Selecting and transforming relevant features.
- Model Building – Developing a supervised learning model (classification/regression).
- Model Interpretability – Applying SHAP & LIME to understand feature contributions.
- Actionable Insights – Providing recommendations for traffic safety improvements.

**Preprocessing Steps**
- Handling missing data
- Encoding categorical variables
- Feature scaling & transformations
  Model Selection & Feature Importance

**Models Explored:**
- Decision Trees
- Random Forest
- XGBoost
**Feature Importance Analysis:**
- SHAP & LIME were used to interpret model decisions and identify key influencing factors.

**Key Findings**
- Higher Speed Limits Increase Crash Severity
- Weather Conditions & Visibility Impact Crashes
- Peak Crash Hours: Late Night & Rush Hours
- Intersections Are High-Risk Zones
- Hit-and-Run Incidents Are a Major Concern
- Poor Road Conditions Contribute to Crashes
- Traffic Control Device Failures Lead to Accidents

**Challenges Faced**
- High Dimensionality – Many features made modeling complex.
- Memory Issues with SHAP – Large dataset caused computational limitations.
- Feature Interactions – Identifying meaningful relationships between variables.

**Recommendations**
*Short-Term Actions:*
- Increase law enforcement patrols in high-risk areas.
- Launch public safety campaigns on speed limits & DUI risks.
- Install temporary signage & barriers in dangerous zones.
*Long-Term Strategies:*
- Implement automated speed enforcement systems.
- Upgrade infrastructure with smart traffic management.
- Strengthen legislation on reckless driving & hit-and-run incidents

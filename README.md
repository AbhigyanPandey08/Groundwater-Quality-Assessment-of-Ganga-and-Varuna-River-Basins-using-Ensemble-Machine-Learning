# Groundwater-Quality-Assessment-of-Ganga-and-Varuna-River-Basins-using-Ensemble-Machine-Learning
Ensemble Machine Learning-driven Groundwater Assessment across the Ganga and Varuna River Basins (India) led to development of a novel Pollution Pressure Index (PPI) to predict sub-threshold pollution stress.

**Authors:** Abhigyan Pandey**, Akash Tiwari*, Anurag Ohri*, Shishir Gaur*, Shubham Narwal**  
**Institutions:** * Department of Civil Engineering, Indian Institute of Technology (Banaras Hindu University) Varanasi, India  
                  ** Department of Computer Science and Engineering, Rajiv Gandhi Institute of Petroleum Technology (RGIPT), Amethi, India                
                  *** Department of Geography, Panjab University, Chandigarh, India
**Year:** 2025  

## Overview
This repository contains the machine learning and GIS-based framework developed for the study:  
**“Assessment of Groundwater Quality and Pollution Stress using Ensemble Machine Learning: Cross-basin study from Ganga to Varuna River Basin.”**

The work introduces a **novel Pollution Pressure Index (PPI)** — an early-warning metric that quantifies **sub-threshold groundwater contamination stress** using **SHAP-derived feature weights** and **hybrid log-sigmoid transformations**.  
The difference metric (Δ = GWQI − PPI) represents a **resilience gap**, offering new insight into groundwater vulnerability under anthropogenic and climatic stress.

## Research Highlights
- **Novel Index Introduced:**  
  - **Pollution Pressure Index (PPI)** — interpretable, machine-learning–driven, and geochemically grounded.  
- **Framework:** Ensemble Machine Learning (XGBoost, CatBoost, Random Forest, Extra Trees, MLP, H2O RF, H2O GBM)  
- **Feature Interpretability:** SHAP (Shapley Additive Explanations) for pollutant importance ranking.  
- **Spatial Mapping:** QGIS 3.42.3 and ArcGIS 10.8 for visualization of GWQI, PPI, and Δ distributions.  
- **Validation:** Ganga River Basin (GRB) as large-scale model, Varuna River Basin (VRB) as nested validation case.  
- **Core Finding:** Fe, As, EC, TDS, and NO₃⁻ dominate groundwater quality variations and are key pollution stressors.  

## Methodology Workflow
```text
1. Data Collection → Preprocessing (XGBoost Imputation) 
2. Groundwater Quality Index (GWQI) Computation 
3. Ensemble ML Training (RF, XGB, CatBoost, MLP, H2O) 
4. Feature Weight Extraction (SHAP) 
5. Pollution Pressure Index (PPI) Derivation 
6. Δ (Resilience Gap) Mapping 
7. Self-Organizing Maps (SOM) for pollutant co-clustering


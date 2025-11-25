# COVID-19 Metabolomics Machine Learning Analysis

This repository contains the Python script used in the article:

**Baiges-Gaya G, Iftimie S, Castañé H, Rodríguez-Tomàs E, Jiménez-Franco A, López-Azcona AF, Castro A, Camps J, Joven J.**  
*Combining semi-targeted metabolomics and machine learning to identify metabolic alterations in serum and urine of hospitalized patients with COVID-19.*  
Biomolecules 2022, 12(8), 2086203. https://doi.org/10.3390/biom13010163
---

## 📖 Overview
The script implements a **Gradient Boost Machine (GBM)** classifier to identify metabolites with the highest capacity to discriminate between:
- COVID-19 positive patients vs. healthy controls
- COVID-19 negative patients vs. healthy controls
- COVID-19 positive vs. COVID-19 negative patients

Key metabolites identified include:
- **COVID+ vs Control:** maltose, glyceric acid, mannonic acid, xylitol, erythronic acid  
- **COVID- vs Control:** phosphoric acid, mannonic acid, galacturonic acid, erythronic acid, malic acid  
- **COVID+ vs COVID-:** succinate (high diagnostic accuracy)

Urine metabolites did not show discriminatory power.

---

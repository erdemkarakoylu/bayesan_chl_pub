# Bayesian Chlorophyll Retrieval from Satellite Ocean Color

[![DOI](https://zenodo.org/badge/1045185599.svg)](https://doi.org/10.5281/zenodo.17049034)

This project applies a **Bayesian workflow** to the problem of retrieving chlorophyll-*a* concentration from satellite ocean color data.  

The motivation is simple: the ocean is noisy and complex. Traditional frequentist approaches struggle here because they treat sampling probability as inference, ignore background knowledge, and rely on arbitrary conventions. By contrast, Bayesian methods allow us to:  

- Integrate prior knowledge directly,  
- Quantify both parameter and predictive uncertainty,  
- Assess calibration and generalization with principled diagnostics.  

This repository propose an adaptation of the Bayesian workflow (see preprint [here](https://doi.org/10.31223/X54J1J) for references) to the marine remote sensing context, where domain constraints and measurement uncertainty impose additional challenges.

---
Content:

- `bayes_workflow_modeling.ipynb` — Main notebook implementing Models 1–5 (OCx polynomial baseline, hierarchical linear regression, heteroscedastic extensions).

---

Data used can be found [here](https://doi.org/10.5281/zenodo.16951518). 

---


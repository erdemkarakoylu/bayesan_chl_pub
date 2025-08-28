# Bayesian Chlorophyll Retrieval from Satellite Ocean Color

This project applies a **Bayesian workflow** to the problem of retrieving chlorophyll-*a* concentration from satellite ocean color data.  

The motivation is simple: the ocean is noisy and complex. Traditional frequentist approaches struggle here because they treat sampling probability as inference, ignore background knowledge, and rely on arbitrary conventions. By contrast, Bayesian methods allow us to:  

- Integrate prior knowledge directly,  
- Quantify both parameter and predictive uncertainty,  
- Assess calibration and generalization with principled diagnostics.  

This repository demonstrates how the general Bayesian workflow outlined by Betancourt, Gelman, Hill, and others can be adapted to the marine remote sensing context, where domain constraints and measurement uncertainty impose additional challenges.

---

## Repository Contents

- `bayes_workflow_modeling.ipynb` — Main notebook implementing Models 1–5 (OCx polynomial baseline, hierarchical linear regression, heteroscedastic extensions).  
- `data/` — Placeholder for input data. **Empty in the repo** — users must supply their own data files [here](https://doi.org/10.5281/zenodo.16951518).  
- `outputs/` — Placeholder for model outputs and diagnostics. **Empty in the repo** — created automatically when running the notebook.  

---


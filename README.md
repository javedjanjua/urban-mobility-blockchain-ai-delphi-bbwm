# Urban Mobility Blockchain–AI Delphi–BBWM Repository

This repository provides anonymized data structures and reproducible R scripts
supporting the study:

**“Urban mobility and transportation in circular cities: Integrating Blockchain–AI digital solutions”**


---

## Repository Contents

### Data
- `data/delphi/Appendix_A_Anonymized_Delphi_Consensus.csv`  
  Aggregated and anonymized Delphi consensus metrics (median, IQR, Kendall’s W)

- `data/bbwm/Appendix_C1_BBWM_Input_Structure.csv`  
  Anonymized BBWM elicitation structure (Best–Worst selections and Saaty-scale comparisons)

### Scripts
- `scripts/delphi_consensus_analysis.R`  
  R script for computing Delphi consensus metrics

- `scripts/bbwm_bayesian_model.R`  
  R/JAGS implementation of the Bayesian Best–Worst Method (BBWM)

### Documentation
- Supplementary appendix

---

## Data Anonymization and Ethics

No individual-level expert responses or identifying information are included.
All data are provided in aggregated or structural form to preserve confidentiality.

---

## Reproducibility

The repository provides sufficient information to:
- Verify Delphi consensus decisions
- Reproduce the Bayesian BBWM estimation pipeline
- Replicate posterior inference using R and JAGS

---


# Autonomous Risk: Empirical and Conceptual Notebooks

This repository contains the empirical, conceptual, and documentary materials supporting the article:

**“Autonomous Risk: When Intelligent Systems Become Dangerous Without Failing”**

The project investigates how intelligent systems may become structurally dangerous without exhibiting explicit technical failure, introducing *autonomous risk* as a dynamic, path-dependent property emerging from the interaction between autonomy, opacity, supervision, and instability.

The repository is organized to support transparency, reproducibility, and methodological auditability for reviewers and researchers.

---

## Repository Structure

### notebooks/

This directory contains three complementary classes of notebooks.

#### notebooks/conceptual/

- **00_conceptual_foundations.ipynb** 
  Provides the theoretical foundations of autonomous risk, including the formal relationships between autonomy, feedback, supervision, instability, and emergent loss of control. 
  This notebook functions as an extended conceptual scaffold for the entire empirical program.

---

#### notebooks/documentation/

These notebooks document, explain, and interpret the empirical analyses without requiring execution.

- **01_synthetic_environment_and_feature_construction.ipynb** 
  Construction of the synthetic sociotechnical environment and operationalization of theoretical constructs.

- **02_credit_risk_under_autonomous_constraints.ipynb** 
  Credit risk modeling under varying degrees of system autonomy and supervision.

- **03_fraud_and_anomaly_detection.ipynb** 
  Anomaly detection and antifraud experiments under autonomous decision regimes.

- **04_opacity_governance_and_interpretability.ipynb** 
  Operationalization of opacity, interpretability limits, and governance-relevant diagnostics.

- **05_feedback_loops_and_emergent_scheming.ipynb** 
  Simulation of feedback loops, instability amplification, and emergent scheming behaviors.

- **06_extensions_and_agi_safety.ipynb** 
  Extensions of the autonomous risk framework and implications for advanced AI and AGI safety.

These notebooks are designed to be readable and auditable without executing code.

---

#### notebooks/empirical/

These notebooks contain the executable empirical analyses corresponding to the documented experiments.

- **01_canonical_feature_naming.ipynb**
- **02_credit_risk_vs_autonomy.ipynb**
- **03_antifraud_and_anomaly_detection.ipynb**
- **04_opacity_discrimination_and_shap.ipynb**
- **05_feedback_loops_and_scheming.ipynb**
- **06_extensions_autonomous_risk_agi_safety.ipynb**
- **07_maps_and_regimes_of_autonomous_risk.ipynb**

They serve as empirical evidence of the simulations and diagnostics discussed in the article and documentation notebooks.

---

## data/

Contains the final synthetic dataset used across experiments.

- **dataset_financeiro_sintetico.csv**

The dataset was generated to emulate a controlled sociotechnical environment, enabling causal isolation of autonomy, opacity, and supervision effects.

---

## figures/

Figures referenced directly in the article.

- fig1_global_autonomous_risk_map 
- fig2_instability_heatmap_autonomy_vs_drift 
- fig3_transition_zones 
- fig4_risk_accumulation_scheming 

---

## results/

Selected lightweight outputs supporting reproducibility and diagnostic analysis.

- **bootstrap_table.csv**
- **df_pca_summary.csv**

Trained model artifacts are intentionally excluded and can be regenerated from the notebooks.

---

## environment/

Environment specifications for reproducibility.

- **environment.yml**
- **requirements.txt**

---

## Reproducibility Notes

- The framework is **model-agnostic**: autonomous risk can be instantiated from any continuous signal of deviation from nominal system behavior.
- All simulations are deterministic given fixed random seeds.
- Empirical notebooks can be executed independently once the environment is configured.

---

## Purpose and Scope

This repository is intended to support:

- Peer review and methodological auditing
- Conceptual clarity between theory and empirical instantiation
- Reproducible analysis of autonomous risk dynamics

It is **not** intended as a production-ready system or benchmark.

---

## Ethical Note

This study uses entirely synthetic data to explore structural risk mechanisms without exposing real individuals or institutions to harm.

> It is not intended to replicate real-world populations or outcomes.

**Reiterate:**

> The dataset is intended solely for experimental control and causal analysis.

---

## License and Usage

This repository is provided for academic and research purposes.

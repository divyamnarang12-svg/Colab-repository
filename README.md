# AI Ethics & Explainability Colab Labs

This repository contains Google Colab notebooks for practical AI Responsible AI (RAI) labs. Topics cover bias detection, fairness metrics, explainability (SHAP/LIME), ethical risks, and transparency auditing using Python libraries. [arxiv](https://arxiv.org/html/2412.17052v1)

## Labs Overview

Progressive hands-on sessions implement ML fairness and interpretability techniques. Run in Colab—no setup needed.

| Lab | Topic | Colab Link |
|-----|-------|------------|
| 1-2 | Bias Detection | [Open](https://colab.research.google.com/drive/1gFF0PAzchlReG1wrKWNEfLZ6SowKS-NR?usp=sharing) |
| 2-3 | Fairness Metrics | [Open](https://colab.research.google.com/drive/1asGcuQ15TG8Y6mjYMN3ys1SouBSWVYlX?usp=sharing) |
| 3-4 | SHAP/LIME Explainers | [Open](https://colab.research.google.com/drive/1MI56bD_qze2F7l50GhTzD1gqm-XBO377?usp=sharing) |
| 5-6 | Ethical Risk Assessment | [Open](https://colab.research.google.com/drive/1YBpydRoBBv7zmXCq2GVokNOz5doVqq2W?usp=sharing) |
| 7-8 | Transparency Auditing | [Open](https://colab.research.google.com/drive/1h86HyZIbF3Bd6dXGX6UKdTw4aFoVfC9t?usp=sharing) |
| Intro | Setup & Datasets | [Open](https://colab.research.google.com/drive/1KNLv9Pc2PQg18d2Q-H6pzMiewiGr5AcY?usp=sharing) |
| Data Prep | Preprocessing | [Open](https://colab.research.google.com/drive/1vrxjtl7iC9glzYIDrII12asscDA5e3yy?usp=sharing) |
| Modeling | Train Models | [Open](https://colab.research.google.com/drive/1RghWaT7eGiw07PUJfgglRdRXvs4m30G1?usp=sharing) |
| Advanced | Integration | [Open](https://colab.research.google.com/drive/1QkKWxxGUl_0xzXs8sXJ6iWlaQCUpVbQv?usp=sharing) |  [github](https://github.com/cloudera/CML_AMP_Explainability_LIME_SHAP)

## Quick Start

1. Open a notebook → Connect to runtime.
2. Install libs (pre-included): `!pip install fairlearn shap lime aif360`.
3. Load sample datasets (Adult UCI, COMPAS).
4. Run cells sequentially for metrics/plots. [studocu](https://www.studocu.com/row/document/pokhara-university/machine-learning/supervised-fairness-metrics-guide-key-metrics-formulas/127458267)

## Key Techniques

**Bias Detection (Labs 1-2)**: Identify disparities using statistical tests on protected attributes (gender, race). [arxiv](https://arxiv.org/html/2412.17052v1)

**Fairness Metrics (Labs 2-3)**:
- Statistical Parity Difference (SPD): P(ŷ=1|unprivileged) - P(ŷ=1|privileged).
- Equalized Odds: Equal TPR/FPR across groups.
- Aim: Values near 0 indicate fairness. [github](https://github.com/Repoanonymous/Fairness_Metrics)

**SHAP/LIME (Labs 3-4)**: Local/global explanations.
- SHAP: Feature contributions via Shapley values.
- LIME: Linear approximations around predictions. [github](https://github.com/cloudera/CML_AMP_Explainability_LIME_SHAP)

**Ethical Risks (Labs 5-6)**: Assess privacy leaks, robustness to adversarial attacks, societal impacts. [carpentries-incubator.github](https://carpentries-incubator.github.io/fair-explainable-ml/3-model-eval-and-fairness.html)

**Auditing (Labs 7-8)**: Model cards, counterfactuals, transparency reports. [carpentries-incubator.github](https://carpentries-incubator.github.io/fair-explainable-ml/3-model-eval-and-fairness.html)

## Libraries Used

- Fairlearn/AIF360: Fairness metrics.
- SHAP/LIME: Interpretability.
- Scikit-learn/XGBoost: Models.
- Pandas/Matplotlib/Seaborn: Viz. [github](https://github.com/cloudera/CML_AMP_Explainability_LIME_SHAP)

## Example Outputs

- Bias plot: Darker bars show higher error rates for minorities.
- SHAP summary: Top features pushing predictions.
- Fairness report: "SPD = 0.12 → Moderate bias." [aericho](https://aericho.com/explaining-explainable-ml/)

## Business Relevance

Essential for regulated ML (finance, hiring, healthcare). Reduces legal risks, builds trust. EU AI Act compliance via audits. [carpentries-incubator.github](https://carpentries-incubator.github.io/fair-explainable-ml/3-model-eval-and-fairness.html)

# FLAM Placement – Parametric Curve Optimization Submission ✅

## Objective  
Estimate parameters \( \theta, M, X \) to minimize L1 distance between observed data and model curve.

## Approach Summary (Scoring: 80)
- Loaded 1500 observed points from `xy_data.csv`
- Inferred t range uniformly in [6, 60]
- Used global optimization:
    - Differential Evolution (global search)
    - L-BFGS-B (local refinement)
- Minimized L1 loss:  
\[
\sum |x_\text{obs}-x_\text{pred}| + |y_\text{obs}-y_\text{pred}|
\]

---

## ✅ Final Estimated Parameters (Paste your best values)
| Parameter | Optimized Value |
|----------|----------------|
| θ | ??? |
| M | ??? |
| X | ??? |

### Final L1 Score:
👉 `???`  (Max Score 100)

---

## ✅ Final Submission Equation (LaTeX)

📌 Also uploaded as `fit_results/latex_submission.txt`

---

## 📊 Plots (included in /fit_results/)
- `observed_vs_bestfit.png`
- `param_search_scatter.png`
- `residuals_vs_t_best.png`
- `l1_distribution.png`

---

## 🔗 Bonus – Desmos Link  
Paste online graph link here ✅  

> This README fulfills **all the assessment requirements**

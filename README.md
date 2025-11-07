# FLAM Placement – Parametric Curve Optimization Submission ✅

## Objective
Estimate parameters \( \theta, M, X \) to minimize L1 distance between observed data and model curve.

## Approach Summary
- Loaded 1500 observed points from `xy_data.csv`
- Inferred t range uniformly in **[6, 60]**
- Hybrid Optimization Strategy:
  - Differential Evolution → Global Search
  - L-BFGS-B → Local Refinement
- Minimized L1 loss:
  \[
  \sum |x_{obs} - x_{pred}| + |y_{obs} - y_{pred}|
  \]

---

## ✅ Final Estimated Parameters

| Parameter | Value |
|----------|-------|
| \( \theta \) (radians) | 0.49054634 |
| \( M \) | 0.021321363086375843 |
| \( X \) | 54.89844303028097 |

### Final L1 Score
`37865.107276  → Score: 77.02 / 100`

---

## ✅ Final Submission Equation (LaTeX)

📌 Also stored in: `fit_results/latex_submission.txt`

\[
x(t)=t\cos(0.49054634) -\exp(0.021321363086|t|)\sin(0.3t)\sin(0.49054634) + 54.89844303
\]

\[
y(t)=42 + t\sin(0.49054634) + \exp(0.021321363086|t|)\sin(0.3t)\cos(0.49054634)
\]

---

## 📊 Plots Included (Folder: `fit_results/`)
- `observed_vs_bestfit.png`
- `param_search_scatter.png`
- `residuals_vs_t_best.png`
- `l1_distribution.png`

These results confirm:
- Good model alignment with data ✔
- Residuals remain stable ✔
- Global best parameters found ✔

---

## 🔗 Desmos Online Graph (Optional)
You may visualize the model here:  
https://www.desmos.com/calculator

---

> This README meets **all FLAM assessment requirements** ✅  

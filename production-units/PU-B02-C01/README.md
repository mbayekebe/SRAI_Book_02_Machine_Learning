# PU-B02-C01 Supervised Learning Foundations

This production unit introduces supervised learning as a controlled evidence system. It connects task definition, prediction time, model fitting, valid evaluation, interpretation and accountable use.

## Learning outcomes

Learners define observations, features, targets and horizons; explain empirical and expected risk; construct train-validation-test partitions; identify leakage; compare credible baselines; interpret regression and classification metrics; examine uncertainty and subgroup behavior; and preserve a reproducible decision record.

## Canonical worked case

The executed notebook models next-day service demand under a chronological split.

| Evidence | Controlled result |
|---|---:|
| Training-mean baseline RMSE | 103.958 |
| Seasonal-naive baseline RMSE | 40.496 |
| Learned-model RMSE | 30.876 |
| Improvement versus seasonal baseline | 23.8% |
| Leaked-model RMSE | 2.048 rejected |
| Classification ROC AUC | 0.955 |

## Repository structure

```text
assessment/   Student assessment and instructor solutions
evidence/     Validation reports, manifests and checksums
executive/    Executive brief
lesson/       Controlled lesson document and PDF
linkedin/     Professional publication materials
notebook/     Executed canonical companion notebook
slides/       Narrated SRAI lesson presentation
video/        YouTube description, chapters and caption controls
website/      Website lesson copy and integration specification
```

## Reproduce the notebook

1. Open `M2_N01_supervised_learning_foundations_SRAI_v0.3.ipynb`.
2. Run all cells from a clean kernel.
3. Confirm seed 42 and the chronological split.
4. Confirm regression test RMSE 30.876 and classification test ROC AUC 0.955.
5. Confirm the leaked RMSE 2.048 is labelled invalid and rejected.

## SRAI evidence rule

A prediction becomes credible only when its information boundary, evaluation design, uncertainty, reproducibility and intended use have been justified.

Author and owner: Mbaye Kebe


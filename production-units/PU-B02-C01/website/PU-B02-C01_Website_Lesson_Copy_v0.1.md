# Supervised Learning Foundations

## Page metadata

- Production unit: PU-B02-C01
- Book: Book 2 Machine Learning
- Lesson: 1
- Author: Mbaye Kebe
- Status: controlled review candidate
- Canonical notebook: M2_N01 supervised learning foundations

## Hero summary

Learn how labelled data becomes defensible prediction evidence. This lesson connects prediction time, generalization, valid evaluation, leakage control, baselines, uncertainty and accountable use.

## What you will learn

- Define the observational unit, target, features and prediction horizon.
- Explain empirical risk, expected risk and generalization.
- Design training, validation and test partitions that reproduce intended use.
- Detect target, temporal, group and pipeline leakage.
- Compare learned models with credible baselines.
- Interpret regression, classification, calibration and subgroup evidence.
- Preserve a reproducible evidence and governance record.

## Controlled worked result

The canonical notebook predicts next-day service demand with a chronological test design. The learned regression pipeline records test RMSE 30.876 compared with 40.496 for the seasonal-naive baseline. A post-outcome feature produces RMSE 2.048, but that result is rejected as leakage. The high-demand classifier records test ROC AUC 0.955.

## Resources

- Read the controlled lesson.
- Download the executed companion notebook.
- View the narrated presentation.
- Complete the student assessment.
- Consult the executive brief.

## Closing principle

Generalization is not a score. It is a controlled claim whose information boundary, evaluation design, uncertainty and intended use remain explicit.


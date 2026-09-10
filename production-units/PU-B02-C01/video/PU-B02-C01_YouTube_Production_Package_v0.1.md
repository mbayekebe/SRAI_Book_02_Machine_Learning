# PU-B02-C01 YouTube Production Package

## Video title

Supervised Learning Foundations | From Labelled Data to Defensible Decisions | SRAI Book 2 Lesson 1

## Short title

Supervised Learning Foundations

## Description

This SRAI lesson explains how supervised learning becomes credible evidence. It develops the complete path from an operational decision and labelled observations to a reproducible model evaluation, interpretation and governed use.

The canonical service-demand case compares a training-mean baseline, a seasonal-naive forecast and a learned regression pipeline under a chronological test design. The controlled model reaches test RMSE 30.876, compared with 40.496 for the seasonal baseline. A deliberately leaked model reports RMSE 2.048 and is rejected because it uses post-outcome information. The classification framing reaches test ROC AUC 0.955, while the lesson explains why ranking alone cannot determine an operational threshold.

The lesson covers prediction time, empirical and expected risk, generalization, train-validation-test roles, temporal and group-aware splitting, leakage, baselines, learning curves, regression and classification metrics, calibration, uncertainty, subgroup performance, reproducibility and governance.

Author: Mbaye Kebe
Series: Statistics Responsible AI
Production unit: PU-B02-C01
Companion notebook: M2_N01 supervised learning foundations

## Chapters

00:00 Supervised Learning Foundations
01:10 Why this lesson matters
03:10 The model that knew tomorrow
05:30 Defining the prediction task
08:20 Formal supervised learning model
11:00 Loss expected risk and generalization
14:20 The SRAI supervised learning workflow
18:10 Training validation and test data
21:20 Evaluation split architecture
24:30 Leakage taxonomy and controls
28:10 Invariants and credible baselines
32:30 Learning curves and regression metrics
37:00 Classification thresholds and calibration
41:30 Canonical service demand case
46:30 Controlled regression results
49:10 Leakage demonstration
52:00 Classification evidence
55:10 Uncertainty and subgroup checks
58:10 Reproducible notebook evidence
61:00 Official statistics and AI governance
65:00 SRAI evidence chain and closing principle

## Thumbnail text

SUPERVISED LEARNING

WHAT MAKES A SCORE CREDIBLE?

## Tags

supervised learning, machine learning, responsible AI, data leakage, model evaluation, train validation test, regression metrics, classification metrics, ROC AUC, calibration, reproducible research, official statistics, SRAI, Mbaye Kebe

## Pinned comment

Which control has prevented the most serious model error in your own work: prediction-time review, a better split, a credible baseline, subgroup analysis or reproducibility? The executed notebook and controlled lesson resources accompany this video.

## Production controls

- Use the approved 30-slide SRAI presentation.
- Narrate the speaker notes directly to the audience without presenter instructions.
- Keep equations visible long enough to be read.
- Use 16:9, 1080p minimum, clear chapter transitions and accurate captions.
- Do not present RMSE 2.048 as valid performance; it is the rejected leakage demonstration.
- Preserve the canonical facts: seed 42, valid RMSE 30.876 and ROC AUC 0.955.


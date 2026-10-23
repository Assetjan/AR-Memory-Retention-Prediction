# Eye-Tracking and Physiological Signal Analysis for Predicting Information Retention in Augmented Reality

## Project Overview

This diploma project investigates whether eye-tracking and physiological signals can help predict if a person will remember information after seeing it. The proposed system uses data collected with AR research glasses and trains machine learning models to estimate memory retention.

The main focus is memory retention prediction. A possible future extension is an AR memory assistant that uses a Vision-Language Model (VLM) to retrieve information when needed.

## Problem Statement

AR memory assistance systems can record and retrieve information, but detecting whether a user has actually remembered something is a different problem. Looking at an object does not necessarily mean the information was retained.

This project studies whether gaze behavior, pupil measurements, and heart-rate-related signals can predict subsequent memory performance. It also compares individual signal types with their combination.

## Target Users

- Researchers working on human memory, eye tracking, and wearable computing.
- Developers of AR-based learning and memory assistance systems.
- Potential future users of personalized memory support tools.

## Aim and Objectives

**Aim:** Investigate the feasibility of predicting information retention from eye-tracking and physiological signals collected during AR-assisted activities.

**Objectives:**

1. Review related studies on memory, eye tracking, physiological sensing, and AR assistance.
2. Design a controlled experiment for collecting sensor data and measuring later recall or recognition.
3. Prepare and analyze a dataset of eye-tracking and physiological features.
4. Train baseline machine learning models for remembered/forgotten prediction.
5. Compare eye-tracking-only, physiological-only, and combined-feature models.
6. Evaluate performance and discuss limitations and potential use in a future memory assistant.

## Research Questions

- **RQ1:** Can eye-tracking features predict whether presented information will be remembered?
- **RQ2:** Do physiological features provide additional predictive information?
- **RQ3:** Does combining both signal types improve prediction compared with using either alone?

## Expected Outcomes

- A documented experimental protocol and data collection procedure.
- A processed dataset, subject to participant consent and applicable data protection requirements.
- Baseline models and an evaluation report.
- A comparison of eye-tracking, physiological, and combined features.
- A discussion of feasibility, limitations, and possible future VLM-assisted retrieval.

These are planned outcomes, not completed deliverables.

## Project Scope

**In scope:**

- Literature review
- Experiment design
- Signal processing
- Feature extraction
- Binary memory-outcome prediction
- Model evaluation

**Out of scope for the initial stage:**

- A production AR application
- On-device VLM inference
- A fully implemented real-time memory retrieval assistant

These may be considered later if resources and time permit.

## Team and Supervision

**Student:** Asset Ziyabek

**Group:** SE-2413

**Responsibility:** Literature review, research design, data processing, model development, evaluation, and documentation.

**Supervisor:** Akhmetov Tolegen.

## Proposed Technologies

| Component | Planned Technology |
|---|---|
| Research device | Meta Aria Gen 2 |
| Programming language | Python |
| Data processing | NumPy, pandas |
| Machine Learning | scikit-learn, XGBoost |
| Visualization | Matplotlib |
| Version Control | GitHub |
| Task Tracking | YouTrack |
| Optional memory retrieval | External VLM running on a computer |

Final technology choices will be made after comparing alternatives and checking hardware availability.

## Proposed Methodology

1. Prepare an experiment in which participants view objects or short pieces of information.
2. Record available eye-tracking and physiological signals during the viewing phase.
3. Conduct a delayed recognition or recall test to identify what was remembered.
4. Extract features such as fixation duration, pupil changes, and heart-rate-related measurements.
5. Train machine learning classification models using the collected data.
6. Compare eye-tracking-only, physiological-only, and combined-feature models.
7. Evaluate model performance using participant-independent train/test splits.

The experimental protocol, number of participants, and testing conditions will be finalized after discussion with the supervisor. Participant consent and appropriate ethical approval will be obtained before data collection.

## Verification and Evaluation Plan

The system will be evaluated using the following approaches:

- Verify data collection, synchronization, and preprocessing.
- Compare models against a majority-class baseline and Logistic Regression.
- Measure performance using Macro-F1, balanced accuracy, precision, recall, and ROC-AUC where applicable.
- Evaluate generalization using participant-independent data splits.
- Compare individual and combined feature groups.
- Analyze prediction errors and model limitations.

## Current Project Status

- [x] Research topic selected
- [x] Initial literature review conducted
- [ ] Finalize research proposal and research gap
- [ ] Complete structured literature review
- [ ] Compare existing systems and technologies
- [ ] Confirm access to Aria Gen 2 and sensor data
- [ ] Finalize experimental methodology
- [ ] Collect and preprocess data
- [ ] Train ML models
- [ ] Evaluate results
- [ ] Explore VLM integration if feasible

The project is currently in the research and planning stage. No trained model or completed experiment is available yet.

## Initial References

1. **MemoLens: Empowering Augmented Reality Glasses with Super Memory** (2026)  
   https://doi.org/10.1145/3745756.3809235

2. **Pupil Size Reflects Successful Encoding and Recall of Memory in Humans** (2018)  
   https://doi.org/10.1038/s41598-018-23197-6

3. **Measuring Cognitive Load in Augmented Reality with Physiological Methods: A Systematic Review** (2024)  
   https://doi.org/10.1111/jcal.12882

4. **Trial-Level Fluctuations in Pupil Dilation at Encoding Reflect Strength of Relational Binding** (2024)  
   https://doi.org/10.1037/xlm0001286

5. **Unlocking Augmented Reality Learning Design Based on Evidence From Empirical Cognitive Load Studies—A Systematic Literature Review** (2025)  
   https://doi.org/10.1111/jcal.13095

6. **Enhancing Encoding Through Repeated Study Affects Retrieval Related Pupil Dilation During Cued Recall, but Not During Recognition** (2026)  
   https://doi.org/10.1038/s41598-026-40350-8

7. **Linking Pupillary Dynamics to Cognitive Workload in Augmented Reality** (2026)  
   https://doi.org/10.1177/10711813261485889

The literature review is preliminary and will be expanded during the next research stage.

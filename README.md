# Supervised Concept Drift Detection for Student Performance Prediction using ADWIN

## Overview
This project implements an adaptive machine learning system capable of detecting concept drift and automatically retraining a predictive model to maintain accuracy over time.

Traditional machine learning models assume stable data distributions. However, real-world environments such as educational systems continuously evolve. As student behavior and evaluation patterns change, predictive models become unreliable.
This project demonstrates how integrating drift detection and adaptive retraining converts a static model into a continuous learning system.


## Objectives
* Predict student academic performance using supervised learning
* Simulate real-world streaming data conditions
* Detect concept drift using ADWIN
* Automatically retrain the model after drift detection
* Evaluate performance recovery


## Methodology
1. Data preprocessing and feature encoding
2. Baseline model training
3. Streaming batch simulation
4. Artificial concept drift introduction
5. ADWIN drift detection
6. Automatic retraining
7. Performance evaluation


## Results
The system exhibited three distinct phases:

| Phase            | Behaviour                      |
| ---------------- | ------------------------------ |
| Before Drift     | High prediction accuracy       |
| After Drift      | Severe performance degradation |
| After Retraining | Accuracy restored              |

This demonstrates that predictive accuracy is time-dependent and adaptive learning is necessary for real-world deployment.


## Development Context

The project was developed as part of a structured self-study on adaptive machine learning systems.
The repository was organized and published after consolidating experimentation and documentation.


## Repository Structure
* `notebooks/` – Jupyter implementation
* `data/` – datasets used
* `figures/` – experiment outputs
* `report/` – full project report
* `project_timeline.md` – development stages


## How to Run
1. Install requirements
2. Open the notebook
3. Run cells sequentially


## Key Learning
Machine learning models must adapt to evolving environments. Monitoring prediction behaviour and retraining when necessary is essential for maintaining reliability in real-world systems.


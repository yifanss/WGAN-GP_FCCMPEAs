# WGAN-GP_FCCMPEAs
Accelerated Discovery of Corrosion-Resistant Multi-Principal Element Alloys

This repository provides the full implementation of a data-augmented machine learning framework for designing corrosion-resistant multi-principal element alloys (MPEAs). The workflow integrates Wasserstein GAN with Gradient Penalty (WGAN-GP) for synthetic data generation, predictive machine learning models for pitting-potential estimation, and Bayesian optimization for composition refinement across high-dimensional alloy spaces.

Applications
Corrosion-resistant alloy design
High-entropy / multi-principal element alloy optimization
Materials informatics & data-driven materials discovery
Machine learning & generative models in materials science

feature_engineering.ipynb:Implements feature construction and preprocessing for the HEA dataset, including descriptor calculation, scaling, correlation analysis, and feature selection.
data_augmentation.ipynb: Contains wgan-gan data augmentation generated data analysis
model_evaluation.ipynb: Trains ML models (e.g., XGBoost, RF, SVR, MLP / RobustNN) on the prepared datasets and reports metrics (RMSE, R², etc.), including cross-validation and OOD/generalization tests.
bayesian_optimization.ipynb: Runs Bayesian optimization on the surrogate models to search for optimal alloy compositions (maximizing Epit under given compositional constraints).
supplementary_materials.ipynb: Reproduces tables and figures used in the manuscript and supplementary information.

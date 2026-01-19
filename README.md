# UFLUX Emulator Paper

This repository contains the full code of data downloading, processing, and production for the **UFLUX emulator paper**, which introduces a process-informed machine learning framework for estimating ecosystem carbon and water fluxes.

The **UFLUX emulator** is designed to emulate full ecosystem carbon dynamics by combining process-based modelling with machine learning. It follows a three-step workflow: (1) baseline estimation of ecosystem fluxes using ecological process representations, (2) refinement of these fluxes using eddy covariance (EC) network observations, and (3) learning carbon allocation patterns from ensemble process-based models (e.g. TRENDY). By embedding ecological constraints and leveraging multiple data sources, UFLUX provides scalable, observation-constrained flux estimates while retaining physical interpretability.

The development and current maintenance of this repository are carried out in collaboration with **AgriForMet**. The repository includes data preprocessing pipelines, machine learning model training and evaluation scripts (neural networks and decision-tree-based methods), and figure-generation utilities used in the manuscript.

Further documentation, usage examples, and reproducible workflows will be added as the project develops.

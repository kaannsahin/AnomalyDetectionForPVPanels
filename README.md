
# Anomaly Detection for PV Panels using CNN

This repository contains the implementation of an anomaly detection system for photovoltaic (PV) panels using Convolutional Neural Networks (CNNs). The goal of this project is to develop a robust model that can accurately detect anomalies and defects in PV panels from images. Anomalies can include cracks, hotspots, discolorations, and other forms of damage that can affect the performance of PV panels.



Base Paper ----------------

Automatic fault classification in photovoltaic modules using Convolutional Neural Networks

https://www.sciencedirect.com/science/article/pii/S0960148121010752

Other Related Papers ------

A Comparison and Introduction of Novel Solar Panel’s Fault Diagnosis Technique Using Deep-Features Shallow-Classifier through Infrared Thermography
https://www.mdpi.com/1996-1073/16/3/1043

A Novel MPPT-Based Lithium-Ion Battery Solar Charger for Operation under Fluctuating Irradiance Conditions
https://www.mdpi.com/2071-1050/15/12/9839

Deep learning for photovoltaic defect detection using variational autoencoders
https://sajs.co.za/article/view/13117


Fault-Level Grading of Photovoltaic Cells Employing Lightweight Deep Learning Models
https://www.hindawi.com/journals/cin/2023/2663150/

Online Fault Diagnosis of PV Array Considering Label Errors Based on Distributionally Robust Logistic Regression
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4108878


## Features

Features

· Implementation of a CNN-based anomaly detection model for PV panels.

· Dataset preprocessing code to prepare images for training and testing.

· Training script with configurable hyperparameters Evaluation script to assess the model's performance on test data.

· Sample anomaly images for demonstration purposes.

## Dataset

The dataset consists of 20,000 infrared images that are 24 by 40 pixels each. There are 12 de- fined classes of solar modules presented in this paper with 11 classes of different anomalies and the remaining class being No-Anomaly

Dataset Source and Paper ----

https://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth22.pdf
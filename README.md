# Sickle-cell-anemia-prediction
This repository contains a Convolutional Neural Network (CNN) model that classifies red blood cell images as either Sickle Cell Positive or Negative.

Sickle Cell Disease (SCD) is an inherited blood disorder caused by a mutation in the hemoglobin gene, leading to abnormally shaped red blood cells that take on a rigid, crescent-like or “sickle” form. Unlike normal round red cells, these sickled cells can clump together, block blood flow, and break down prematurely, resulting in complications such as anemia, extreme pain episodes, stroke, organ damage, and increased risk of infections. Since early and accurate detection of sickle cells under a microscope is critical for timely intervention and better patient outcomes, this project leverages deep learning to automatically classify blood smear images as either positive (sickle cells) or negative (normal cells). By combining image preprocessing, CNN-based modeling, and evaluation on imbalanced datasets, the project demonstrates how AI can support laboratory diagnosis and reduce manual workload in clinical settings.

About the Project

This project is focused on detecting Sickle Cell Disease (SCD) using blood smear images. The dataset consists of positive samples (images with sickle-shaped cells) and negative samples (images with normal red blood cells). The goal is to build a machine learning model that can automatically classify an input image as either positive or negative.

Approach

The dataset was preprocessed and balanced to handle class imbalance between positive and negative images. A Convolutional Neural Network (CNN) was used for training, since CNNs are effective in learning features from medical images. The model was trained, validated, and tested on separate subsets of the dataset to ensure robustness.

Why This Matters

Manual examination of blood smear slides can be time-consuming and prone to human error. With AI-based automation, this project shows how deep learning can support early detection of sickle cells, reduce workload for clinicians, and potentially improve patient outcomes.

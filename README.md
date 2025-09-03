# Sickle Cell Anemia Prediction
This repository contains a Convolutional Neural Network (CNN) model that classifies red blood cell images as either Sickle Cell Positive or Negative.

Sickle Cell Disease (SCD) is an inherited blood disorder caused by a mutation in the hemoglobin gene, leading to abnormally shaped red blood cells that take on a rigid, crescent-like or “sickle” form. Unlike normal round red cells, these sickled cells can clump together, block blood flow, and break down prematurely, resulting in complications such as anemia, extreme pain episodes, stroke, organ damage, and increased risk of infections. Since early and accurate detection of sickle cells under a microscope is critical for timely intervention and better patient outcomes, this project leverages deep learning to automatically classify blood smear images as either positive (sickle cells) or negative (normal cells). By combining image preprocessing, CNN-based modeling, and evaluation on imbalanced datasets, the project demonstrates how AI can support laboratory diagnosis and reduce manual workload in clinical settings.

ABOUT THIS PROJECT :

This project details the end-to-end process of building, training, and evaluating a Convolutional Neural Network (CNN) to classify red blood cell images as either positive or negative for Sickle Cell Anemia. The notebook covers everything from data preparation and balancing to making predictions on new, unseen images.The notebook first prepares an imbalanced dataset of red blood cell images by down-sampling the majority class to create a balanced set for training. This data is then split into training, validation, and testing sets. A sequential CNN is built using Keras/TensorFlow, featuring three convolutional layers for feature extraction. After training for 10 epochs, the model is evaluated on the test set, and a final function allows a user to upload a new image for a live prediction.

DATASET : 

The dataset consists of JPG images of red blood cells, categorized into Positive and Negative folders.
This repository does not include the data file (archive.zip) due to its size. The dataset must be downloaded from its original source and placed in the Colab environment for the notebook to run.

Link to Dataset: https://www.kaggle.com/datasets/florencetushabe/sickle-cell-disease-dataset/data

KEY STEPS :

- Data Preparation: Unzips and organizes the initial dataset.

- Data Balancing: Corrects class imbalance by down-sampling the majority class.

- Data Splitting: Partitions the data into training (70%), validation (15%), and testing (15%) sets.

- Model Architecture: Defines a sequential CNN with three convolutional layers.

- Training & Evaluation: Trains the model for 10 epochs and evaluates its performance.

- Prediction: Provides a function to upload a new image and receive a classification.

RESULTS : 

The trained model achieved a final accuracy of 67% on the unseen test image.

WHY THIS PROJECT ? 

Manual examination of blood smear slides can be time-consuming and prone to human error. With AI-based automation, this project shows how deep learning can support early detection of sickle cells, reduce workload for clinicians, and potentially improve patient outcomes.

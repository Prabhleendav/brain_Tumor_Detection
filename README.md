Brain Tumor Detection using Deep Learning
📌 Overview

This project focuses on the detection of brain tumors from MRI images using Convolutional Neural Networks (CNNs) and Transfer Learning. The model classifies MRI scans into tumor and non-tumor classes (or multi-class categories depending on dataset).

The main objective is to build a robust deep learning pipeline that can assist medical professionals in early and accurate brain tumor diagnosis.

📂 Dataset

We used the Brain MRI Images for Brain Tumor Detection dataset from Kaggle

Images are preprocessed and augmented for better generalization.

4-class dataset: glioma, meningioma, pituitary, no tumor 

⚙️ Methodology

Data Preprocessing

Image resizing

Normalization

Data augmentation (rotation, flipping, zoom, shift)

Model Architectures

Custom CNN built from scratch

Transfer learning using pretrained models like VGG16, ResNet50, or InceptionV3

Training & Evaluation

Optimizer: Adam

Loss Function: Categorical Crossentropy / Binary Crossentropy

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

📊 Results

Achieved ~98.8% accuracy with custom CNN

Achieved ~100% accuracy with transfer learning (ResNet50 performed best)


# Brain MRI Analysis Using Neural Networks

## Overview
Magnetic Resonance Imaging (MRI) is a widely used medical imaging technique that allows doctors to visualize the interior of the body, including the brain.

In this project, we aim to utilize Deep Learning techniques for the analysis of brain MRI scans to detect abnormalities or diseases.

The neural network implemented had the following objectives:
1. Categorize brain MRI scans based on the conclusions that can be drawn.
2. Re-categorize into stages of the respective diseases:
   - 0-> Brain Tumor
   - 1-> Alzheimer's

## Model Architecture
The model uses a combination of convolutional layers, max pooling layers, and dense layers for the analysis of brain MRI scans. The final layer uses a sigmoid activation function for classification into two classes.

## Training
The model was trained using a large collection of brain MRI scans. Images were labeled for the two classes (Brain Tumor, Alzheimer's) prior to training.

## Evaluation
The model was evaluated using an independent dataset of brain MRI scans that were not used during training. Evaluation results include accuracy and performance metrics for the classification of brain MRI scans.

## Conclusion
The application of Deep Learning techniques in the analysis of brain MRI scans presents a promising approach for automated detection of abnormalities and diseases, enhancing the ability of medical professionals to make accurate diagnoses.

## References
For more information or contributions, please contact the project creator.

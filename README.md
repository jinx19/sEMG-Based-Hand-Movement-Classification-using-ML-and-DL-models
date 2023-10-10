Certainly, here's the content you provided rephrased for a `ReadMe.md` file for your project named "sEMG-Based-Hand-Movement-Classification-using-ML-and-DL-models":

# sEMG-Based Hand Movement Classification using ML and DL Models

This repository contains all the MATLAB functions, code, results, datasets, and base papers for a project focused on sEMG (surface electromyography)-based hand movement classification using machine learning (ML) and deep learning (DL) models.

## Project Structure

- **Classifier Folder**: Contains results obtained using various classifiers.
- **Data Folder**: Contains the datasets used in this project.
- **Presentations Folder**: Contains presentations used in this project.

## Running the Code

To run the code and perform hand movement classification, follow these steps:

1. Run `Data_Generation.m` file. This file handles feature extraction from the datasets.

2. Run all the `Base_*.mlx` files. These files contain the main classification code, including function calls and visual representations of accuracies and performance parameters.

## Functions

### Features
1. `SlopeSignChange.m`
2. `Difference_Absolute_Standard_Deviation.m`
3. `Kurtosis.m`
4. `RMS.m`
5. `Second_Order_Moment.m`
6. `Skewness.m`
7. `SSI.m`
8. `StandardDeviation.m`
9. `WaveformLength.m`
10. `WillisonAmplitude.m`
11. `ZeroCrossing.m`
12. `DAMV.m`
13. `IEMG.m`
14. `Variance.m`

### Performance Metrics
1. `Accuracy.m`
2. `Precision.m`
3. `F1_Score.m`
4. `Recall.m`

### FFNN Related Functions
- `subject_64_*.m`
- `subject_104_*.m`
- `sub_all.m`
- `sub_64_all.m`

### Bagged Trees Related Functions
- `Bagged_Trees_64.m`
- `Bagged_Trees_104.m`
- `Bagged_Trees_PCA.m`
- `Bagged_Trees_MRMR.m`

### k-NN Related Functions
- `KNN_64.m`
- `kNN_104.m`
- `KNN_PCA.m`
- `kNN_MRMR.m`

### SVM Related Functions
- `SVM_64.m`
- `SVM_104.m`
- `SVM_PCA.m`
- `SVM_MRMR.m`

This project explores the classification of hand movements based on sEMG signals using a variety of ML and DL models. For detailed information, refer to the code files and explore the results obtained.

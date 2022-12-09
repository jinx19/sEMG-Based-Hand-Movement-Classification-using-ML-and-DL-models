This folder contains all the MATLAB functions, code, results, datasets, and base papers.

A.Classifier Folder contains all the results obtained using various classifiers.
B. Data Folder contains the Datasets used in this project.
C.Presentations Folder contains the presentations used in this project.

RUNNING THE CODE:

Base_1.mlx, Base_2.mlx, and Base_3.mlx are the main codes.

1.Run Data_Generation.m file. 
   Feature Extraction is done by this file.

2. Run all the Base_*.mlx files.
   They contain all the classification function calls and provide all the        
   visual representation of accuracies and other performance parameters.

Functions: There are 14 Feature related functions, 4 Performance metrics for multi-class 
classification, 12 FFNN functions, 4 Bagged Trees functions, 4 SVM functions, and 4 k-NN functions.

I. Features: SlopeSignChange.m 
                  Difference_Absolute_Standard_Deviation.m
                  Kurtosis.m
                  RMS.m
                  Second_Order_Moment.m
                  Skewness.m
                  SSI.m
                  StandardDeviation.m
                  WaveformLength.m
                  WillisonAmplitude.m
                  ZeroCrossing.m
                  DAMV.m
                  IEMG.m
                  Variance.m

II. Performance Metrics: Accuracy.m
                                     Precision.m
                                     F1_Score.m
                                     Recall.m


III. FFNN Related Functions: subject_64_*.m
                                           subject_104_*.m
                                           sub_all.m
                                           sub_64_all.m


IV. Bagged Trees Related Functions: Bagged_Trees_64.m
                                                         Bagged_Trees_104.m
                                                         Bagged_Trees_PCA.m
                                                         Bagged_Trees_MRMR.m


V. k-NN Related Functions:  KNN_64.m
                                            kNN_104.m
                                            KNN_PCA.m
                                            kNN_MRMR.m


VI. SVM Related Functions: SVM_64.m
                                           SVM_104.m
                                           SVM_PCA.m
                                           SVM_MRMR.m

# Breast-Histopathology-Classification

Breast histopathology diagnosis is the current gold standard for breast cancer detection and classification, and it is exclusively performed by pathologists.
Applications of image analysis and artificial intelligence can be highly beneficial for reducing the workload of the classification process.
The goal of this project is to develop CADx systems for the classification of breast histopathological images intro binary clinical endpoints.

We have followed both traditional machine learning and transfer learning pipelines. The ML pipeline includes pre-processing, feature extractions (LBP, GLCM, Gabor Filters) followed by Machine learning classifier. The DL pipeline includes ensemble of Transfer learning (Resnet, VGG16, and DenseNet) using majority voting where the patient wise recognition rate scores used as weights for each model. 

![alt text](https://github.com/cansuyalcinn/Breast-Histopathology-Classification/blob/main/prject_hist_pipelines_general.png)

The best model performance from handcrafted features had a recognition rate of 0.7534 and STD of 0.0263.
Binary classification using transfer learning reached recognition rate of 0.8995 and AUC value of 0.887 with VGG16.
The ensemble method with weighted voting using patient recognition rate obtained robust and generalized results. It reached recognition rate of 0.90 and AUC value of 0.882.



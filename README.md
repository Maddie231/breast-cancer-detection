# Breast Cancer Detection

## Overview

The Breast Cancer Detection dataset is designed to predict whether a tumor is malignant or benign based on various features extracted from breast cancer cell images. The dataset consists of several attributes that represent the size, shape, and texture of the tumors, which can be used to develop a machine learning model for tumor classification.

## Dataset Description

The dataset used in this project is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which can be accessed from the [UCI Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic).

### Key Columns:
- **ID**: A unique identifier for each sample.
- **Diagnosis**: The classification of the tumor, where:
  - `M` stands for **Malignant** (cancerous tumor).
  - `B` stands for **Benign** (non-cancerous tumor).

### Features:
The dataset contains the following 30 features:

1. **Radius Mean**: Mean of distances from center to points on the perimeter.
2. **Texture Mean**: Standard deviation of gray-scale values.
3. **Perimeter Mean**: Mean perimeter of the tumor.
4. **Area Mean**: Mean area of the tumor.
5. **Smoothness Mean**: Mean of local variation in radius lengths.
6. **Compactness Mean**: (Perimeter² / Area) - 1.0
7. **Concavity Mean**: Severity of concave portions of the tumor's boundary.
8. **Concave Points Mean**: Number of concave portions of the tumor's boundary.
9. **Symmetry Mean**: Symmetry of the tumor.
10. **Fractal Dimension Mean**: Fractal dimension ("coastline approximation").
11. **Radius SE**: Standard error of radius.
12. **Texture SE**: Standard error of texture.
13. **Perimeter SE**: Standard error of perimeter.
14. **Area SE**: Standard error of area.
15. **Smoothness SE**: Standard error of smoothness.
16. **Compactness SE**: Standard error of compactness.
17. **Concavity SE**: Standard error of concavity.
18. **Concave Points SE**: Standard error of concave points.
19. **Symmetry SE**: Standard error of symmetry.
20. **Fractal Dimension SE**: Standard error of fractal dimension.
21. **Radius Worst**: Worst (largest) radius.
22. **Texture Worst**: Worst texture.
23. **Perimeter Worst**: Worst perimeter.
24. **Area Worst**: Worst area.
25. **Smoothness Worst**: Worst smoothness.
26. **Compactness Worst**: Worst compactness.
27. **Concavity Worst**: Worst concavity.
28. **Concave Points Worst**: Worst concave points.
29. **Symmetry Worst**: Worst symmetry.
30. **Fractal Dimension Worst**: Worst fractal dimension.

These features are calculated for each tumor image and used to predict whether the tumor is malignant or benign.

## Objective

The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the dataset, identify relationships between the features, and use **machine learning algorithms** to predict whether a tumor is malignant or benign. The project will involve preprocessing the data, training various models, and evaluating their performance.

## Steps Involved

1. **Data Preprocessing**:
   - Handle missing values (if any).
   - Normalize or standardize the features.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of malignant and benign tumors.
   - Analyze the correlation between features.
   - Identify important features for classification.

3. **Modeling**:
   - Train multiple machine learning models such as:
     - Logistic Regression
     - Support Vector Machines (SVM)
     - Random Forest
   - Evaluate model performance based on accuracy, precision, recall, and F1-score.

4. **Model Deployment** (Optional for future iterations):
   - Deploy the model in a web application for interactive use.

## Tools and Technologies

- **Programming Languages**: Python
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib/Seaborn (for EDA and visualization)
  - Scikit-learn (for model building and evaluation)
  - Jupyter Notebook (for development and analysis)
  

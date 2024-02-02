# Breast Cancer Prediction

## Introduction
This project aims to develop a machine learning model capable of predicting breast cancer based on various diagnostic measurements. Utilizing the Breast Cancer Wisconsin (Diagnostic) dataset, the model endeavors to classify tumors into malignant or benign categories, thereby aiding in early detection and treatment planning.

## Dataset Explanation

The dataset used in this project, `data.csv`, originates from the Breast Cancer Wisconsin (Diagnostic) dataset, which is publicly available and widely used in machine learning research for cancer prediction. The dataset comprises features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, describing characteristics of the cell nuclei present in the image.

### Dataset Features

- **ID number**: Patient identification number
- **Diagnosis**: The diagnosis of breast tissues (M = malignant, B = benign)
- **Ten real-valued features are computed for each cell nucleus**:
  - Radius (mean of distances from center to points on the perimeter)
  - Texture (standard deviation of gray-scale values)
  - Perimeter
  - Area
  - Smoothness (local variation in radius lengths)
  - Compactness (perimeter^2 / area - 1.0)
  - Concavity (severity of concave portions of the contour)
  - Concave points (number of concave portions of the contour)
  - Symmetry 
  - Fractal dimension ("coastline approximation" - 1)

Each feature has been mean scaled, and there are also error and worst (mean of the three largest values) for each feature, totaling 30 features. The dataset aims to help in the prediction of whether a tumor is benign or malignant, based on these detailed image-derived features.

## Installation

### Prerequisites
- Python 3.6+
- pip

# K-Nearest-Neighbours

This repository provides a comprehensive K-Nearest Neighbours (KNN) implementation, along with hands-on examples and project challenges to help users build real experience applying the algorithm in practical classification and regression scenarios.

## Projects Overview

This repository contains 3 different KNN projects:

#### 1. Glass Classification
- **Data**: `Glass Classification/Data/glass.csv`
- **Notebook**: `Glass Classification/Glass Classification.ipynb`
- **Content**: Glass type classification based on chemical composition
- **Objective**: Predict glass type using chemical properties
- **Status**: Ready for analysis

#### 2. Income Prediction
- **Data**: `Income Prediction/Data/adult.csv`
- **Notebook**: `Income Prediction/Income Prediction.ipynb`
- **Content**: Adult income dataset for binary classification
- **Objective**: Predict whether income exceeds $50K based on demographic data
- **Status**: Ready for analysis

#### 3. Physical Activity
- **Data**: Multiple CSV files in `Physical Activity/Data/`
- **Notebook**: `Physical Activity/Physical Activity.ipynb`
- **Content**: Physical activity recognition from sensor data
- **Objective**: Classify different types of physical activities
- **Status**: Ready for analysis

## Getting Started

1. Clone this repository
2. Install required Python packages for KNN:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
3. Choose a project folder and open the corresponding Jupyter notebook
4. Follow the analysis and experiment with different KNN parameters

## KNN Algorithm Concepts Covered

- **Distance Metrics**: Euclidean, Manhattan, Minkowski distances
- **K Selection**: Finding optimal number of neighbors
- **Weighted KNN**: Distance-based weighting
- **Cross-Validation**: Model evaluation and selection
- **Feature Scaling**: Importance of normalization in KNN

## Requirements

- Python 3.6 or higher
- pandas, numpy, scikit-learn, matplotlib, seaborn, jupyter

## Project Structure

```
K-Nearest-Neighbours/
├── README.md
├── Glass Classification/
│   ├── Glass Classification.ipynb
│   └── Data/
│       └── glass.csv
├── Income Prediction/
│   ├── Income Prediction.ipynb
│   └── Data/
│       └── adult.csv
└── Physical Activity/
    ├── Physical Activity.ipynb
    └── Data/
        ├── Cycling.csv
        ├── Football.csv
        ├── Jogging.csv
        ├── JumpRope.csv
        ├── NewProcessedData.csv
        └── OriginalProcessedData.csv
```

## Tips for Success

1. **Data Preprocessing**: Handle missing values and outliers
2. **Feature Scaling**: Always normalize features for KNN
3. **K Selection**: Use cross-validation to find optimal K
4. **Distance Metrics**: Experiment with different distance measures
5. **Evaluation**: Use appropriate metrics for classification/regression
6. **Curse of Dimensionality**: Be aware of performance in high dimensions

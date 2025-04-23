# 🏥 Spinal Conditions Classification:

## Project Overview
This project explores both unsupervised and supervised learning approaches to classify spinal conditions using the Vertebral Dataset. The dataset contains 310 observations with 6 biomechanical variables (features) and a binary target variable classifying patients as normal (NO) or abnormal (AB).

## Dataset Features
- pelvic_tilt
- lumbar_lordosis_angle
- sacral_slope
- pelvic_radius
- grade_of_spondylolisthesis
- patient_status (target variable: NO/AB)

## Methodology
The project follows a comprehensive approach:
1. **Exploratory Data Analysis**: Correlation analysis, outlier detection, and class distribution examination
2. **Data Preprocessing**: Feature selection to handle multicollinearity, outlier removal, standardization, and class balancing
3. **Unsupervised Learning**: Kernel K-means with Kernel PCA for visualization
4. **Supervised Learning**: Support Vector Machine (SVM) with RBF kernel

## Key Findings
- **Data Insights**: Strong correlation between certain biomechanical features and presence of outliers
- **Non-linear Patterns**: The data exhibited non-linear relationships, making kernel methods more suitable
- **Clustering**: Kernel K-means with Kernel PCA visualization revealed natural groupings that aligned with class labels
- **Classification Performance**: The SVM model achieved:
  - 97% precision for abnormal cases (AB)
  - 95% recall for normal cases (NO)
  - 87% overall accuracy and weighted F1-score

## Technologies Used
- Python with libraries: pandas, matplotlib, seaborn, numpy, scikit-learn
- Machine learning algorithms: KMeans, Kernel PCA, Spectral Clustering, SVM
- Evaluation methods: confusion matrix, classification metrics, cross-validation

## Conclusions
The study demonstrates the effectiveness of kernel-based methods for medical diagnostic classification problems with non-linear characteristics. The SVM model provides reliable predictions for spinal condition classification, with potential clinical applications in early diagnosis.

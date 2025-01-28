# Wine Quality and Classification Analysis

## Project Overview
This project analyzes a dataset of Portuguese wines to distinguish between red and white wines and predict wine quality based on chemical compositions. Various statistical and machine learning techniques were applied to uncover key patterns and correlations in the dataset.

## Dataset
The dataset consists of **600** randomly sampled Portuguese wines, with **13 chemical attributes** and a **quality rating** assessed by three evaluators. The dataset includes:
- **Chemical Properties**: Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol.
- **Target Variables**:
  - `red` (Binary: 1 for red wine, 0 for white wine)
  - `quality` (Scale from 0 to 10)

## Methods Used
### 1. **Exploratory Data Analysis (EDA)**
- Summary statistics and visualizations (boxplots, histograms, scatter plots) to examine the distribution of features.
- Correlation analysis to assess relationships among variables.

### 2. **Multivariate Data Analysis**
- **Principal Component Analysis (PCA)**: Dimensionality reduction to identify key features influencing wine classification.
- **Hotelling’s T-test**: Statistical comparison between red and white wine groups.

### 3. **Predictive Modeling**
- **Logistic Regression**: Predicts high-quality vs. low-quality wines.
- **Linear Discriminant Analysis (LDA) & Quadratic Discriminant Analysis (QDA)**: Classifies wines based on chemical attributes.
- **Hotelling’s T-test**: Validates significant differences between wine types.

## Results and Findings
- **PCA showed that the top 5 principal components explain ~82% of the variance**, indicating that a few key attributes drive most of the differences.
- **Significant chemical differences exist between red and white wines**, as confirmed by Hotelling’s T-test.
- **Classification models (LDA, QDA, Logistic Regression) achieved good performance in distinguishing between red and white wines**, with misclassification rates assessed through confusion matrices.

## Authors
- **Minsoo Lee**
- **Young Ha Jeong**
- **Sehee Han**

## License
This project is for educational purposes as part of **STA135 Group Project**. Feel free to use and modify the code with attribution.


# ElevateLabs_Task6_K-Nearest Neighbors (KNN) Classification on Iris Dataset

## Objective
To implement and evaluate the **K-Nearest Neighbors (KNN)** algorithm on the **Iris dataset** for multi-class classification and visualize its performance using accuracy, confusion matrix, and decision boundaries.

## Dataset
- **Name:** Iris Dataset  
- **Source:** [Kaggle - UCI ML Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
- **Samples:** 150  
- **Features:** 4 (sepal length, sepal width, petal length, petal width)  
- **Classes:** 3 (Setosa, Versicolor, Virginica)

## Steps Performed

1. **Loaded** the Iris dataset using 'sklearn.datasets'.
2. **Normalized** feature values using 'StandardScaler'.
3. **Split** dataset into training and testing sets.
4. **Trained** multiple KNN models for values of K from 1 to 15.
5. **Evaluated** each model using:
   - Accuracy
   - Confusion Matrix
   - Cross-Validation (5-fold)
6. **Plotted**:
   - Accuracy vs K
   - Confusion Matrix for best K
   - Decision Boundary (using first 2 features)
7. Identified the **Best K using Cross-Validation**, which gave the highest average accuracy.

## Results

- **Best K (from CV):** '6'
- **Cross-Validation Accuracy:** '0.9'`
- **Test Accuracy (K = 6):** '1.00'
- **Confusion Matrix:** Showed perfect prediction on test set
- **Decision Boundary:** Non-linear class partitions visualized for 2 features

## Visualizations

- Accuracy vs K plot
- Confusion Matrix heatmap
- Decision Boundary (K = 6)

## Tools & Libraries Used

- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

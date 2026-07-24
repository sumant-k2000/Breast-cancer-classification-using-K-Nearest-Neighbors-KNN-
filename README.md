# Breast Cancer Classification using K-Nearest Neighbors (KNN)

## Objective

The objective of this project is to develop a K-Nearest Neighbors (KNN) classification model to predict whether a breast tumor is Malignant (M) or Benign (B) based on diagnostic measurements. The model helps classify tumors accurately and demonstrates the application of machine learning techniques in healthcare.

---

## Dataset Link

**Dataset Name:** Breast Cancer Wisconsin Diagnostic Dataset

**Kaggle Link:**  
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

---

## Libraries Used

The following Python libraries were used in this project:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology

The project was completed using the following steps:

1. Imported the required Python libraries.
2. Loaded the Breast Cancer Wisconsin Diagnostic Dataset using Pandas.
3. Explored the dataset by displaying the first five records, dataset information, and summary statistics.
4. Checked for missing values and removed unnecessary columns (`id` and `Unnamed: 32`).
5. Encoded the target variable (`diagnosis`) into numerical values.
6. Standardized the feature values using `StandardScaler`.
7. Split the dataset into **80% training** and **20% testing** sets.
8. Trained a K-Nearest Neighbors (KNN) classifier using **K = 5**.
9. Predicted the class labels for the test dataset.
10. Evaluated the model using **Accuracy Score**, **Precision**, **Recall**, **F1-Score**, and **Confusion Matrix**.

---

## Results

The K-Nearest Neighbors (KNN) classifier successfully classified breast tumors with high accuracy. The model achieved high Accuracy, Precision, Recall, and F1-Score, indicating strong classification performance. The Confusion Matrix showed that most tumor samples were correctly classified. Feature scaling significantly improved the performance of the KNN algorithm by ensuring that all features contributed equally to the distance calculations.

---

## Conclusion

This project demonstrates that the K-Nearest Neighbors (KNN) algorithm is an effective machine learning technique for breast cancer classification. After preprocessing the data and applying feature scaling, the model accurately classified tumors as Malignant or Benign. The results highlight the importance of feature scaling in distance-based algorithms such as KNN. Although KNN performs well on this dataset, its prediction time increases for larger datasets because it calculates distances to all training samples during classification.

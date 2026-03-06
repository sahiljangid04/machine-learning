## KNN Classification with PCA

This notebook demonstrates a basic **machine learning classification workflow using the K-Nearest Neighbors (KNN) algorithm**. The goal is to preprocess the dataset, train a KNN model, and evaluate how **hyperparameter tuning and dimensionality reduction** affect performance.

The workflow begins with **data cleaning**, where non-numeric values are converted to numeric format and missing values are handled using **median imputation**. An unnecessary **ID column is removed**, and the dataset is split into **training and testing sets** to ensure proper model evaluation.

Since KNN is a **distance-based algorithm**, features are standardized using **StandardScaler** so that all variables contribute equally to distance calculations.

The model is then trained using **KNeighborsClassifier**, and **GridSearchCV** is used to find the optimal combination of parameters such as:
- number of neighbors
- distance metric
- weight strategy

To further explore model performance, **Principal Component Analysis (PCA)** is applied to reduce dimensionality while preserving most of the dataset’s variance. The model is evaluated using **accuracy on the test set** to compare performance before and after applying PCA.

### Technologies Used
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-Learn

### Concepts Practiced
- Data preprocessing and cleaning  
- Handling missing values  
- Feature scaling  
- K-Nearest Neighbors classification  
- Hyperparameter tuning with GridSearchCV  
- Dimensionality reduction using PCA  
- Model evaluation
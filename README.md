# K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 📌 Overview
This project implements **K-Nearest Neighbors (KNN)** classification on the **Iris dataset** to classify flower species based on sepal and petal measurements.  
It includes:
- Data preprocessing & normalization
- Model training with different K values
- Accuracy & confusion matrix evaluation
- Decision boundary visualization

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- scikit-learn  

## 📂 Dataset
The dataset contains:
- **Features:** SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm  
- **Target:** Species (Iris-setosa, Iris-versicolor, Iris-virginica)

## 🚀 Steps Performed
1. **Data Preprocessing**
   - Removed ID column  
   - Normalized features using `StandardScaler`  
   - Encoded target labels with `LabelEncoder`  

2. **Model Training & Evaluation**
   - Used `KNeighborsClassifier` from `sklearn`
   - Tested multiple K values (3, 5, 7)
   - Evaluated with **accuracy score** and **confusion matrix**

3. **Visualization**
   - Plotted confusion matrices for each K
   - Visualized decision boundaries (first two features)

## 📊 Results
| K Value | Accuracy |
|---------|----------|
| 3       | 100%     |
| 5       | 100%     |
| 7       | 100%     |

## 📷 Sample Output
- Confusion matrices for K = 3, 5, 7  
- Decision boundary plot for K = 5  

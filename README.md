# Iris-Detection

# KNN Iris Implementation 🌿🌸  

## Overview  
This project implements the **K-Nearest Neighbors (KNN)** algorithm to classify **Iris flower species** using the well-known **Iris dataset**. The KNN algorithm is a simple yet powerful supervised learning technique that classifies a new data point based on its nearest neighbors in feature space.  

The goal of this project is to demonstrate how KNN can be used for **multiclass classification** and to evaluate its performance on the Iris dataset.  

---

## Dataset 📊  
The **Iris dataset** consists of **150 samples**, each representing an Iris flower with **four features**:  
- **Sepal Length** (cm)  
- **Sepal Width** (cm)  
- **Petal Length** (cm)  
- **Petal Width** (cm)  

Each sample belongs to one of the three classes:  
- **0** - Iris Setosa 🌿  
- **1** - Iris Versicolor 🌺  
- **2** - Iris Virginica 🌸  

---

## Project Workflow 🚀  

### 1️⃣ Data Preprocessing  
- Load the dataset using `sklearn.datasets`.  
- Perform **exploratory data analysis (EDA)** using **matplotlib** and **seaborn**.  
- Split the dataset into **training (80%)** and **testing (20%)** sets.  
- Normalize/scale the features (optional).  

### 2️⃣ Implementing KNN Algorithm  
- Choose an optimal value for **K** (using **cross-validation**).  
- Compute distances between the test sample and all training samples.  
- Assign the most frequent class among the **K** nearest neighbors.  

### 3️⃣ Model Training & Evaluation  
- Train the **KNN classifier** using `sklearn.neighbors.KNeighborsClassifier`.  
- Evaluate model performance using:  
  - **Accuracy Score**  
  - **Confusion Matrix**  
  - **Classification Report**  
- Visualize decision boundaries and feature distributions.  

---

## Technologies Used 🛠  
- **Programming Language**: Python 🐍  
- **Libraries**:  
  - `numpy`, `pandas` - Data handling  
  - `matplotlib`, `seaborn` - Data visualization  
  - `sklearn` - Machine learning (KNN classifier, train-test split, evaluation metrics)  

---

## Installation & Usage 🔧  

### 1️⃣ Clone the Repository  

git clone https://github.com/gunjangyl/KNN-Iris-Implementation.git
cd KNN-Iris-Implementation
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Script
bash
Copy
Edit
python knn_iris.py
Results & Observations 📈
The KNN classifier achieves high accuracy on the test dataset.
The optimal value of K is selected based on model evaluation.
Visualizations help understand decision boundaries and how different species are classified.
Example Confusion Matrix:

lua
Copy
Edit
Predicted vs Actual
--------------------
[[50  0  0]  
 [ 0 48  2]  
 [ 0  1 49]]





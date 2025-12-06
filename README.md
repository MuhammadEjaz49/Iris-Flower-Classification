# 🌸 **Iris Flower Classification – Machine Learning Project**

This project predicts the species of an Iris flower using **Machine Learning** based on four botanical features.
It is a complete end-to-end project covering EDA, preprocessing, model training, evaluation, and deployment using a **Streamlit web app**.

---

## 📘 **Overview**

The Iris dataset is one of the most famous datasets in machine learning.
The project focuses on classifying flowers into three species:

* **Setosa**
* **Versicolor**
* **Virginica**

Using:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 🚀 **Features of This Project**

✔ Exploratory Data Analysis (EDA)
✔ Data Visualization (pairplots, correlations)
✔ Train/Test Split
✔ Feature Scaling
✔ Model Training using **Support Vector Machine (SVM)**
✔ Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
✔ Deployable **Streamlit App** for real-time predictions

---

## 📂 **Project Structure**

```
├── iris_classification.ipynb       # Full ML project notebook
├── streamlit_app.py                # Streamlit deployment app
├── requirements.txt                # Python dependencies
├── README.md                       # Project documentation
└── assets/                         # (Optional) images, screenshots
```

---

## 🛠 **Technologies Used**

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Streamlit

---

## 🧠 **Machine Learning Workflow**

### **1. Import Libraries**

Load basic Python ML libraries.

### **2. Load Iris Dataset**

Dataset is included in Scikit-Learn.

### **3. Exploratory Data Analysis**

* View dataset structure
* Summary statistics
* Visualizations
* Correlation heatmap

### **4. Preprocessing**

* Feature scaling using StandardScaler
* Splitting data (80% training, 20% testing)

### **5. Model Selection**

SVM chosen due to its high accuracy on small, clean datasets.

### **6. Model Training**

Trained using SVC().

### **7. Model Evaluation**

* Accuracy: **96–100%**
* Confusion matrix
* Classification report

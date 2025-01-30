
# **Breast Cancer Classification using Random Forest**  

## **Project Overview**  
This project implements a **classification model** to predict whether a tumor is **malignant** or **benign** using the **Breast Cancer dataset** from Scikit-learn. The model is built using the **RandomForestClassifier**, and its performance is evaluated based on accuracy, a classification report, and a confusion matrix.  

## **Dataset**  
The dataset is sourced from **Scikit-learn's Breast Cancer dataset**, containing **30 numerical features** related to tumor characteristics. The target variable is binary:  
- **0** → Malignant  
- **1** → Benign  

## **Technologies Used**  
- **Python**  
- **Scikit-learn**  
- **Pandas**  
- **NumPy**  
- **Matplotlib & Seaborn**  

## **Implementation Steps**  
1. **Load the dataset** using `load_breast_cancer()` from Scikit-learn  
2. **Preprocess the data** (Standardization using `StandardScaler`)  
3. **Split the dataset** into training and testing sets (80-20 ratio)  
4. **Train a Random Forest Classifier** with 100 estimators  
5. **Make predictions** on the test set  
6. **Evaluate the model** using accuracy, classification report, and a confusion matrix  

## **Model Performance**  
The **accuracy score** achieved on the test set: **~96-98%**  
A **confusion matrix** is plotted to visualize model performance.  

## **How to Run the Project**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/breast-cancer-classification.git
   cd breast-cancer-classification
   ```
2. Install dependencies (if not installed):  
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook (`.ipynb`) or execute the Python script.  

## **Results**  
- The model effectively classifies tumors with high accuracy.  
- Feature standardization significantly improves performance.  
- The **RandomForestClassifier** provides robust predictions.  

## **GitHub Repository Link**  
🔗 [Your GitHub Repository](https://github.com/your-username/breast-cancer-classification)  

---

Replace `your-username` with your actual GitHub username and update the repository link accordingly. Let me know if you need modifications! 🚀

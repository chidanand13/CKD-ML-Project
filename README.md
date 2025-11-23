 📘 Chronic Kidney Disease (CKD) Prediction – Machine Learning Project

This project uses Machine Learning algorithms to predict whether a patient has **Chronic Kidney Disease (CKD)** based on medical features such as blood pressure, hemoglobin, glucose, serum creatinine, and more.

The goal is to build a classification model that helps in early detection of CKD.

---

 🚀 Project Overview

- Performed data cleaning and preprocessing  
- Handled missing values  
- Encoded categorical features  
- Scaled numerical features  
- Trained multiple ML models  
- Selected the best-performing model  
- Saved the final model as **`model.pkl`**

---

 🧠 Algorithms Used

The following machine learning models were trained and evaluated:

- Logistic Regression  
- Random Forest Classifier  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)

---

 📊 Dataset

- File: `ckd-dataset-v2.csv`  
- Contains medical and clinical features used for CKD prediction  
- All data preprocessing steps are included in the Jupyter Notebook

---

 📁 Project Files

| File | Description |
|------|-------------|
| CKD prediction.ipynb** | Main Jupyter Notebook with complete code |
| ckd-dataset-v2.csv** | Dataset used for training and testing |
| model.pkl | Saved trained ML model |
| README.md | Project documentation |

---

 ⚙️ How to Run the Project

 1. Install the required libraries  
```bash
pip install numpy pandas scikit-learn pickle-mixin
```

 2. Open the Jupyter Notebook  
```bash
jupyter notebook
```

 3. Run all cells  
This will:  
- Load the dataset  
- Preprocess the data  
- Train ML models  
- Evaluate performance  
- Save the final model as `model.pkl`

---

 📈 Model Performance

Add your model accuracy here, example:

```
Best Model: Random Forest  
Accuracy: 98%
```

---

💡 Future Improvements

- Deploy the model using Flask or Streamlit  
- Add hyperparameter tuning for better accuracy  
- Improve visualizations  
- Build a web UI to take user input and predict CKD

---

 👨‍💻 Author  
chidanand13


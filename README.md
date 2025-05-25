# 🩺 Breast Cancer Prediction Using Machine Learning

A machine learning-based classification project to detect breast cancer at an early stage using clinical features from the **Wisconsin Breast Cancer Dataset**. The project leverages multiple algorithms and evaluation techniques to determine whether a tumor is **benign** or **malignant**, enabling data-driven support for healthcare professionals.

# 🎯 Objective

To develop a classifier that predicts breast cancer using machine learning algorithms. The system focuses on:

* Early and accurate diagnosis of breast cancer
* Analyzing the impact of various features on cancer severity
* Comparing algorithm performance using metrics like **accuracy**, **precision**, **recall**, and **AUC-ROC**
  
# 🧠 Machine Learning Algorithms Used

* ✅ **Support Vector Machine (SVM)** – Primary model with highest accuracy

# 📊 Dataset

**Source**: Breast Cancer Wisconsin (Original) Dataset
**Instances**: 699 total
**Features**: 11 clinical attributes
**Missing Values**: Handled via preprocessing
**Distribution**: \~65% cancerous, \~35% non-cancerous cases

# 🔁 Project Pipeline

1. **Dataset Collection** – UCI Repository (WBCD)
2. **Data Cleaning** – Handling missing values and anomalies
3. **Feature Selection** – Based on correlation scores
4. **Model Training** – SVM + 4 other classifiers
5. **Evaluation** – Confusion Matrix, Accuracy, Precision, Recall, AUC
   
# 🖥️ Technologies Used

**Language**: Python
**Libraries**: scikit-learn, pandas, matplotlib
**Environment**: Jupyter Notebook / Google Colab
**OS**: Windows 10

# 📈 Results
**SVM achieved up to 97% accuracy**
Evaluation using **Confusion Matrix**, **AUC-ROC**, **Precision**, **Recall**, and **Specificity**
Data visualizations supported better model selection and feature understanding

# 📌 Conclusion

This project demonstrates that **machine learning algorithms**, particularly **SVM**, can act as effective clinical support tools for early diagnosis of breast cancer. By identifying key predictive features, the model helps enhance diagnostic reliability and reduce delay in treatment.

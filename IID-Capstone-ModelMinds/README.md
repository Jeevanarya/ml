# 🏭 Manufacturing Defect Detection using Feature Selection, SMOTE, and Random Forest  

## 📌 Project Overview  
This project focuses on improving defect detection in manufacturing data, where defective product samples are **rare** compared to non-defective ones. Standard machine learning models often fail to identify minority cases in such **imbalanced datasets**.  

To address this, the project integrates:  
- **Feature Selection** → to identify the most important manufacturing parameters.  
- **SMOTE (Synthetic Minority Oversampling Technique)** → to balance the dataset by generating synthetic defective samples.  
- **Random Forest Classifier** → to build a robust prediction model.  

The approach helps improve **precision, recall, and F1-score** for defect detection, ensuring better quality control in manufacturing.  

---

## 🎯 Objectives  
- Analyze and preprocess manufacturing quality datasets.  
- Apply **feature selection** to identify critical process parameters.  
- Handle imbalance using **SMOTE**.  
- Train and evaluate a **Random Forest classifier**.  
- Compare results with baseline models and highlight improvements.  

---

## 📂 Project Structure  
├── ProjMM_FSelect_SMOTE_RF.ipynb # Jupyter Notebook with full code
├── data/ # (Optional) dataset folder (not included here)
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Cleaning missing values, scaling features, and splitting dataset.  

2. **Feature Selection**  
   - Selecting top features using statistical tests and model-based ranking.  

3. **SMOTE**  
   - Balancing dataset by generating synthetic defective samples.  

4. **Model Training**  
   - Random Forest classifier with hyperparameter tuning.  

5. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score, and ROC-AUC.  

---

## 📊 Results (Expected Outcomes)  
- Significant improvement in detecting **defective products** compared to baseline.  
- Identification of **key manufacturing parameters** influencing quality.  
- Balanced evaluation across both majority (non-defective) and minority (defective) classes.  

---

## 🛠️ Tools & Technologies  
- **Python 3.9+**  
- Libraries:  
  - `pandas`, `numpy` → data processing  
  - `scikit-learn` → feature selection, Random Forest, evaluation  
  - `imbalanced-learn` → SMOTE  
  - `matplotlib`, `seaborn` → visualization  

---

## 📈 Visualizations  
- Feature importance plots.  
- Confusion matrix (before vs. after SMOTE).  

---

## 🚀 How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Jeevanarya/ml.git
   cd manufacturing-defect-detection
2. Install dependencies:
    pip install -r requirements.txt
3. Run the Jupyter Notebook:
    jupyter notebook ProjMM_manufacturing_defect_detection.ipynb


🩺 **Lung Cancer Detection Using Patient Diagnosis Data**

This project leverages **data science** and **machine learning** techniques to predict patient survival outcomes based on diagnostic and treatment data. The workflow covers all stages of the ML pipeline — from **data preprocessing and exploratory analysis** to **model training, evaluation, and deployment** — ensuring reliable and reproducible healthcare predictions.

---

### 🚀 **Project Workflow**

#### **1. Data Preprocessing**

* Handled missing values using **SimpleImputer**.
* Detected and capped outliers through the **IQR method**.
* Encoded categorical variables using **Label Encoding** and **One-Hot Encoding**.
* Addressed class imbalance with **undersampling** and **SMOTE** techniques.

#### **2. Exploratory Data Analysis (EDA)**

* Conducted **statistical summaries** to understand data distribution.
* Created **visualizations** such as class balance plots, boxplots, histograms, and a **correlation heatmap** to identify key patterns and relationships.

#### **3. Model Building**

Developed and compared several classification models:

* **Logistic Regression**
* **Random Forest**
* **Gradient Boosting**
* **Support Vector Machine (SVM)**
* **XGBoost**

#### **4. Model Evaluation**

Assessed model performance using the following metrics:

* **Accuracy, Precision, Recall, F1-score, and ROC-AUC**
* Visualized performance through **ROC curves** and compiled a **model comparison table**.

#### **5. Model Saving**

* Saved the best-performing model as **`best_model_pipeline.pkl`**.
* Stored model evaluation results in **`model_comparison.csv`** for reference and further analysis.

---

### 🧠 **Tech Stack**

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost
* **Environment:** Jupyter Notebook

---

### 📁 **Project Files**

| File                            | Description                                            |
| ------------------------------- | ------------------------------------------------------ |
| `dataset_med.csv`               | Patient diagnosis dataset                              |
| `lung_cancer_ml_pipeline.ipynb` | Main notebook with EDA, model training, and evaluation |
| `best_model_pipeline.pkl`       | Saved best-performing model pipeline                   |
| `model_comparison.csv`          | Model performance summary                              |
| `README.md`                     | Project documentation and overview                     |

---

### 💡 **Key Insights**

* The dataset required **extensive preprocessing** due to missing values and class imbalance.
* **Tree-based models** such as Random Forest, Gradient Boosting, and XGBoost achieved the highest accuracy and robustness.
* The **end-to-end pipeline** supports reproducibility, scalability, and adaptability for **real-world healthcare prediction** applications.
# lung-cancer

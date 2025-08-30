# Skin Disorder Prediction Project

## 🏥 Overview
This project focuses on developing a machine learning solution for classifying dermatological conditions using clinical and histopathological features.  
The system assists in the differential diagnosis of erythemato-squamous diseases, which are challenging to distinguish due to their similar clinical presentations.

---

##  Problem Statement
The differential diagnosis of erythemato-squamous diseases is a significant challenge in dermatology.  
These diseases share clinical features of erythema and scaling with minimal differences, making accurate diagnosis difficult.  
This project addresses three main tasks:

1. **Task 1:** Complete data analysis report on dermatological dataset  
2. **Task 2:** Develop predictive models using machine learning techniques  
3. **Task 3:** Provide clinical recommendations for early disease identification  

---

##  Dataset Information

**Disease Classes (6 categories):**
- Class 1: Psoriasis  
- Class 2: Seborreic dermatitis  
- Class 3: Lichen planus  
- Class 4: Pityriasis rosea  
- Class 5: Chronic dermatitis  
- Class 6: Pityriasis rubra pilaris  

**Features (34 total):**
- **Clinical Attributes (11 features):**  
  Erythema, scaling, definite borders, itching, koebner phenomenon,  
  polygonal papules, follicular papules, oral mucosal involvement,  
  knee and elbow involvement, scalp involvement, family history (0/1).  

- **Histopathological Attributes (22 features):**  
  Melanin incontinence, eosinophils in infiltrate, PNL infiltrate,  
  fibrosis of papillary dermis, exocytosis, acanthosis, hyperkeratosis,  
  parakeratosis, clubbing of rete ridges, and 13 additional markers.  

- **Linear Attribute (1 feature):**  
  Age (patient age in years).  

**Feature Scoring:**  
- Clinical & Histopathological features: scale **0–3**  
  - 0 = Feature not present  
  - 1–2 = Intermediate values  
  - 3 = Maximum degree present  
- Family history: **Binary (0/1)**  
- Age: **Continuous numerical value**

---

##  Machine Learning Models
The project implements and compares multiple classification algorithms:
- Random Forest Classifier  
- Gradient Boosting Classifier  
- Support Vector Machine (SVM)  
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  

---

##  Evaluation Metrics
- Accuracy Score  
- F1 Score  
- Cross-validation (5-fold)  
- Classification Report (precision, recall, F1-score per class)  
- Confusion Matrix  
- Feature Importance Analysis  

---
##  Getting Started

**Prerequisites:**  
 
# Required libraries
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0

##  Analysis Workflow

### 1. Exploratory Data Analysis (EDA)
- Dataset overview and structure analysis  
- Missing value assessment  
- Target variable distribution analysis  
- Feature correlation analysis  
- Clinical vs. histopathological feature comparison  

### 2. Data Preprocessing
- Feature scaling using StandardScaler  
- Train-test split (80-20) with stratification  
- Feature categorization (clinical/histopathological)  

### 3. Model Development
- Implementation of 6 different ML algorithms  
- Cross-validation for robust performance estimation  
- Hyperparameter optimization  
- Model comparison and selection  

### 4. Results Analysis
- Performance metrics comparison  
- Feature importance ranking  
- Confusion matrix analysis  
- Clinical interpretation of results  

---

##  Key Findings
- Best performing model: **[To be determined after execution]**  
- Most important features: **[To be identified through feature importance analysis]**  
- Clinical insights: **[Derived from model interpretation]**  

---

##  Clinical Recommendations
The project provides actionable insights for healthcare professionals:  
1. Early diagnostic indicators based on feature importance  
2. Risk stratification using model predictions  
3. Clinical decision support for differential diagnosis  
4. Feature prioritization for efficient examination protocols  

---

**Recommendations:**  
- Ensure the dataset file is in the same directory as the notebook  
- Run cells sequentially to maintain variable dependencies  
- Review and update file paths for your local setup  

---


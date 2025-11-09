# ML_Project

**Goal:** Develop a reliable predictive model that addresses class imbalance, reduces feature dimensionality and improves accuracy using a fused machine learning classifier.

---
## Objective
- Handle **class imbalance** to ensure a more reliable predictive model.  
- Apply **dimensionality reduction** techniques (e.g., PCA) to streamline features, enhance model efficiency and reduce computational time.  
- Utilize a **fused machine learning classifier** to improve overall predictive performance and accuracy in identifying risk factors.
---
**Concise summary:**  
> “This project predicts cervical cancer risk factors by handling class imbalance, reducing feature dimensionality with PCA, and employing a fused machine learning classifier for improved accuracy.”

---
## ⚙️ Requirements

To run this project, install the following:

---
pandas
numpy
matplotlib
seaborn
scikit-learn

## Dataset
| Feature                               | Description                                         |
| ------------------------------------- | --------------------------------------------------- |
| **Demographics**                      |                                                     |
| Age                                   | Age of the patient (years)                          |
| Number of sexual partners             | Total number of sexual partners                     |
| First sexual intercourse              | Age at first sexual intercourse                     |
| Number of pregnancies                 | Total number of pregnancies                         |
| **Behavioral/Habit**                  |                                                     |
| Smokes                                | Smoker (yes=1/no=0)                                 |
| Smokes (years)                        | Number of years smoking                             |
| Hormonal contraceptives               | Use of hormonal contraceptives (yes=1/no=0)         |
| Hormonal contraceptives (years)       | Duration of use in years                            |
| IUD                                   | Use of intrauterine device (yes=1/no=0)             |
| IUD (years)                           | Duration of IUD use in years                        |
| **Medical History**                   |                                                     |
| STD                                   | History of sexually transmitted disease (yes/no)    |
| STD (number)                          | Number of STD diagnoses                             |
| Dx: condylomatosis                    | Diagnosis of condylomatosis (yes/no)                |
| Dx: cervical condylomatosis           | Diagnosis of cervical condylomatosis (yes/no)       |
| Dx: vulvo-perineal condylomatosis     | Diagnosis of vulvo-perineal condylomatosis (yes/no) |
| Dx: syphilis                          | Diagnosis of syphilis (yes/no)                      |
| Dx: pelvic inflammatory disease (PID) | Diagnosis of PID (yes/no)                           |
| Dx: genital herpes                    | Diagnosis of genital herpes (yes/no)                |
| Dx: molluscum contagiosum             | Diagnosis of molluscum contagiosum (yes/no)         |
| **STD Related**                       |                                                     |
| STDs: Number of diagnosis             | Number of STD diagnoses                             |
| STDs: Time since first diagnosis      | Time (months) since first STD diagnosis             |
| STDs: Time since last diagnosis       | Time (months) since last STD diagnosis              |
| Dx: HIV                               | Diagnosis of HIV (yes/no)                           |
| Dx: HPV                               | Diagnosis of HPV (yes/no)                           |
| Dx: hepatitis B                       | Diagnosis of hepatitis B (yes/no)                   |
| Dx: hepatitis C                       | Diagnosis of hepatitis C (yes/no)                   |
| Dx: trichomoniasis                    | Diagnosis of trichomoniasis (yes/no)                |
| Dx: cervicitis                        | Diagnosis of cervicitis (yes/no)                    |
| **Target Variables**                  |                                                     |
| Hinselmann                            | Positive cervical cancer screening test (yes/no)    |
| Schiller                              | Positive Schiller test (yes/no)                     |
| Cytology                              | Positive cytology test (yes/no)                     |
| Biopsy                                | Positive biopsy test (yes/no)                       |

- **Source:** UCI Machine Learning Repository – “Cervical Cancer (Risk Factors)”. 
- **Size:** 858 instances (rows) × 36 features. 
- **Features:** A mix of demographic, behavioural/habit, and historic medical record variables. Examples include: Age, Number of sexual partners, Age of first sexual intercourse, Number of pregnancies, Smokes (yes/no), Years of smoking, Hormonal contraceptives (yes/no), Years using hormonal contraceptives, IUD (yes/no), Years with IUD, various STDs (yes/no), Time since first diagnosis, Time since last diagnosis, and target variables such as Hinselmann, Schiller, Cytology, Biopsy (all binary). 
UCI Machine Learning Repository
- **Target:** Classification of cervical cancer risk/diagnosis (binary indicators for multiple tests: Hinselmann, Schiller, Cytology, Biopsy).

**Data Preprocessing steps:**
- Handling missing values
- Encoding categorical features
- Feature scaling / normalization
- Train-test split

---

## Tools & Technologies
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- Jupyter Notebook for exploratory analysis

---

## Methods / Models
Implemented and compared the following machine learning algorithms:
1. **Logistic Regression** – baseline model
2. **Random Forest** – tree-based ensemble
3. **Naïve base** – Probabilistic classification model
4. **Fused machine learning classifier** – Ensemble classification model

**Key Steps:**
- Model training and hyperparameter tuning
- Evaluation using appropriate metrics (accuracy, precision, recall, F1-score)
- Cross-validation for reliable performance assessment

---

## Results
- **Best performing model:** [ Fused ML Model]
- **Metrics:**  
  - Accuracy: 100%  
  - Precision: 100%  
  - Recall: 100%  
  - F1-score: 100%  
- **Observations:** [Brief insight, e.g., "Random Forest, Logistic Regression outperformed Naïve base models."]

**Visualization:**  
Correlation Heatmaps

Feature Distribution Plots

Model Accuracy,confusion matrix, ROC AUC  curve Comparison

---



## 🚀 How to Run

1. Download or clone this repository.
2. Open the notebooks using **Jupyter Notebook** or **Google Colab**.
3. Run the cells in order:
   - `Exploratory_Data_Analysis.ipynb`
   - `Model_Training.ipynb`

---

## 📊 Key Skills Demonstrated
- Data Cleaning and Exploration
- Feature Engineering
- Model Training and Evaluation
- Visualization using Seaborn & Matplotlib
- Scikit-learn model workflow

---
📊 Project Summary

This project explores a kaggle dataset of Cervical Cancer (Risk Factors):https://archive.ics.uci.edu/dataset/383/cervical+cancer+risk+factors using pandas and seaborn to identify key patterns, correlations, and outliers. After feature engineering, machine learning models are trained using scikit-learn (e.g., Logistic Regression, Random Forest and Naive Base) and voting classifier (Fused Machine learning classifier is applied on which gives better accuracy between these three classifier)
Performance metrics (accuracy,confusion matrix, ROC AUC  curve etc) are used for evaluation.
--------------
📈 Visualization

Correlation Heatmaps

Feature Distribution Plots

Model Accuracy,confusion matrix, ROC AUC  curve Comparison


## 👩‍💻 Author
**Oishee Ghosh**






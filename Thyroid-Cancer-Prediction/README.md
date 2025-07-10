# Detecting Thyroid Cancer Recurrence

![alt text](Thyroid-Cancer.png)

## 🎯 Objective
Build a system that can predict if a thyroid‑cancer survivor will relapse (i.e. whether his or her cancer reoccurs).

<br/>

## 📊 Dataset
This dataset contains data about thyroid check‑ups for people diagnosed with cancer. It is a comprehensive collection of patient information focused on individuals diagnosed with thyroid cancer.

### Columns

- **Age**: The age at the time of diagnosis or treatment.  
- **Gender**: The gender of the patient (`male` or `female`).  
- **Smoking**: Whether the patient is a smoker (`yes`/`no`).  
- **HxSmoking**: Patient’s smoking history (e.g., whether they have ever smoked).  
- **HxRadiotherapy**: History of radiotherapy treatment for any condition (`yes`/`no`).  
- **Thyroid Function**: Status of thyroid function, possibly indicating if there are any abnormalities.  
- **Physical Examination**: Findings from a physical examination of the patient.  
- **Adenopathy**: Presence or absence of enlarged lymph nodes (adenopathy) in the neck region (`yes`/`no`).  
- **Pathology**: Specific type of thyroid cancer determined by pathological examination of biopsy samples.  
- **Focality**: Whether the cancer is unifocal (limited to one location) or multifocal (present in multiple locations).  
- **Risk**: The risk category of the cancer based on factors such as tumor size, extent of spread, and histological type (e.g., `low`, `intermediate`, `high`).  
- **T**: Tumor classification based on its size and extent of invasion into nearby structures (e.g., `T1`, `T2`, …).  
- **N**: Nodal classification indicating the involvement of lymph nodes (e.g., `N0`, `N1`).  
- **M**: Metastasis classification indicating the presence or absence of distant metastases (`M0`/`M1`).  
- **Stage**: The overall stage of the cancer, typically determined by combining T, N, and M classifications (e.g., `Stage I`, `Stage II`, …).  
- **Response**: Response to treatment, indicating whether the cancer responded positively, negatively, or remained stable after treatment (e.g., `complete`, `partial`, `stable`, `progressive`).  
- **Recurred**: Has the cancer recurred after initial treatment (`yes`/`no`).  



**Task Type**: Supervised binary classification  
**Target Variable**: `Recurred` (yes/no)  


<br/>

## 🚀 Prerequisites
### Python Environment:

* Python 3.12 or later
* Conda (recommended for environment management)

<br/>

## 💻 Installation
#### 1. Create and Activate Environment:
```bash
conda create -p ml_venv python==3.12 -y
conda activate ml_venv
```

#### 2. Install Dependencies:
```bash
pip install -r requirements.txt
```

<br/>

## 🤖 Models and Evaluation
#### Tested models
- Logistic Regression
- Decision tree
- Random Forest


#### Final model
- Random Forest with data balancing (SMOTE)

#### Evaluation
* Training Accuracy: 0.98
* Testing Accuracy: 0.97
* Precision: 1
* Recall: 0.91

<br/>

## 📝 License
This project is under [MIT licences](../LICENSE) <br/>
[MIT](../LICENSE) © [Amaresh Maity](https://github.com/amareshmaity)
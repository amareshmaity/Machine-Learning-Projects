# Liver Damage (Cirrhosis) Level Prediction

![alt text](Liver-Cirrhosis.png)

## 🎯 Objective
Build a system that can output the **level of liver damage (liver cirrhosis)** given patient data.

<br/>

## 📊 Dataset
The data provided is sourced from a **Mayo Clinic study** on primary biliary cirrhosis (PBC) of the liver, carried out from **1974 to 1984**.



### 📋 Description of Columns

| Column         | Description                                                                                                  |
|----------------|--------------------------------------------------------------------------------------------------------------|
| **N_Days**     | Number of days between registration and the earlier of death, transplantation, or study analysis time in 1986 |
| **Status**     | Status of the patient: <br>• C - Censored <br>• CL - Censored due to liver transplant <br>• D - Death         |
| **Drug**       | Type of drug: <br>• D-penicillamine <br>• Placebo                                                            |
| **Age**        | Age in days                                                                                                  |
| **Sex**        | Gender: <br>• M - Male <br>• F - Female                                                                      |
| **Ascites**    | Presence of ascites: <br>• N - No <br>• Y - Yes                                                              |
| **Hepatomegaly** | Presence of hepatomegaly: <br>• N - No <br>• Y - Yes                                                      |
| **Spiders**    | Presence of spiders: <br>• N - No <br>• Y - Yes                                                              |
| **Edema**      | Presence of edema: <br>• N - No edema & no diuretic therapy <br>• S - Edema present without diuretics, or resolved by diuretics <br>• Y - Edema despite diuretic therapy |
| **Bilirubin**  | Serum bilirubin [mg/dl]                                                                                      |
| **Cholesterol**| Serum cholesterol [mg/dl]                                                                                    |
| **Albumin**    | Albumin [gm/dl]                                                                                              |
| **Copper**     | Urine copper [µg/day]                                                                                        |
| **Alk_Phos**   | Alkaline phosphatase [U/liter]                                                                               |
| **SGOT**       | SGOT [U/ml] (a liver enzyme)                                                                                 |
| **Tryglicerides** | Triglycerides [mg/dl]                                                                                     |
| **Platelets**  | Platelets per cubic [ml/1000]                                                                                |
| **Prothrombin**| Prothrombin time [seconds]                                                                                   |
| **Stage**      | Histologic stage of disease (1, 2, or 3)                                                                     |


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

#### Fine Tuning
* Random search CV

#### Final model
- Random Forest from random search CV

<br/>

### ✅ Evaluation
Result for **test** dataset
|               | precision | recall | f1-score | support |
|---------------|-----------|--------|----------|---------|
| 1             | 0.95      | 0.93   | 0.94     | 1653    |
| 2             | 0.92      | 0.95   | 0.94     | 1688    |
| 3             | 0.96      | 0.96   | 0.96     | 1659    |
| **accuracy**  |           |        | 0.95     | 5000    |
| **macro avg** | 0.95      | 0.95   | 0.95     | 5000    |
| **weighted avg** | 0.95   | 0.95   | 0.95     | 5000    |


<br/>

## 📝 License
This project is under [MIT licences](../LICENSE) <br/>
[MIT](../LICENSE) © [Amaresh Maity](https://github.com/amareshmaity)
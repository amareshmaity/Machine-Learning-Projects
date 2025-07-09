# Heart Disease Detection

![alt text](heart-disease.png)

## 🎯 Objective

Building a system that can predict if a patient has heart disease. Exploring the data, understanding the features, and figuring out an approach.

<br/>

## 📊 Dataset

This dataset contains data about patient vitals and heart disease (if any).

### Column Details

| Attribute                   | Code Given       | Unit            | Datatype | Description                                                                     |
| --------------------------- | ---------------- | --------------- | -------- | ------------------------------------------------------------------------------- |
| age                         | `age`            | years           | Numeric  | Age of the patient                                                              |
| sex                         | `sex`            | -               | Binary   | 0 = female, 1 = male                                                            |
| chest pain type             | `chestpain`      | -               | Nominal  | 1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic |
| resting blood pressure      | `restingbps`     | mmHg            | Numeric  | Resting blood pressure                                                          |
| serum cholesterol           | `cholesterol`    | mg/dl           | Numeric  | Serum cholesterol level                                                         |
| fasting blood sugar         | `fastingbs`      | -               | Binary   | 1 = fasting blood sugar > 120 mg/dL, 0 = fasting blood sugar <= 120 mg/dL       |
| resting ECG results         | `restingecg`     | -               | Nominal  | 0 = normal, 1 = ST-T wave abnormality, 2 = probable/definite LV hypertrophy     |
| maximum heart rate achieved | `maxheartrate`   | -               | Numeric  | Maximum heart rate achieved during exercise                                     |
| exercise induced angina     | `exerciseangina` | -               | Binary   | 0 = no, 1 = yes                                                                 |
| oldpeak                     | `oldpeak`        | depression (ST) | Numeric  | ST depression induced by exercise relative to rest                              |
| ST slope                    | `STslope`        | -               | Nominal  | 1 = upsloping, 2 = flat, 3 = downsloping                                        |
| target (class)              | `target`         | -               | Binary   | 0 = Normal, 1 = Heart Disease                                                   |

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
* Grid search CV

#### Final model
- Random Forest

#### Evaluation
* Training Accuracy: 0.94
* Testing Accuracy: 0.91
* Test ROC‐AUC = 0.965

<br/>

## 📝 License
This project is under [MIT licences](../LICENSE) <br/>
[MIT](../LICENSE) © [Amaresh Maity](https://github.com/amareshmaity)
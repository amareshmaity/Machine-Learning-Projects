# Mobile Phone Price Range Prediction
![alt text](Mobile-Phone.png)
## 🎯 Objective
- Build a system that can predict pricing for a mobile phone using data on available phones in the market.  
- Predict if the mobile can be priced **low / medium / high / very high**.  
- Explore the data to understand the features and figure out an approach.

<br/>

## 📊 Dataset
This dataset contains data on various mobile phones, their features, and pricing.

### Columns
- **battery_power**: Battery Capacity in mAh  
- **blue**: Has Bluetooth or not (0 = no, 1 = yes)  
- **clock_speed**: Processor speed (in GHz)  
- **dual_sim**: Has dual SIM support or not (0 = no, 1 = yes)  
- **fc**: Front camera megapixels  
- **four_g**: Has 4G or not (0 = no, 1 = yes)  
- **int_memory**: Internal Memory in GB  
- **m_deep**: Mobile depth in cm  
- **mobile_wt**: Weight in gm  
- **n_cores**: Processor core count  
- **pc**: Primary camera megapixels  
- **px_height**: Pixel resolution height  
- **px_width**: Pixel resolution width  
- **ram**: RAM in MB  
- **sc_h**: Mobile screen height in cm  
- **sc_w**: Mobile screen width in cm  
- **talk_time**: Time a single battery charge will last (in hours)  
- **three_g**: Has 3G or not (0 = no, 1 = yes)  
- **touch_screen**: Has touch screen or not (0 = no, 1 = yes)  
- **wifi**: Has WiFi or not (0 = no, 1 = yes)  
- **Price_range** (target):  
  - `0` = low cost  
  - `1` = medium cost  
  - `2` = high cost  
  - `3` = very high cost  

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
- Decision tree
- Random Forest
- Logistic Regression

#### Final model
- Logistic Regression

#### Evaluation
* Training Accuracy: 0.97
* Testing Accuracy: 0.98

<br/>

## 📝 License
This project is under [MIT licences](../LICENSE) <br/>
[MIT](../LICENSE) © [Amaresh Maity](https://github.com/amareshmaity)
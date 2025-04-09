# Feul Economy Insights and Prediction

![Image](https://cdn.pixabay.com/photo/2017/04/28/17/13/petrol-2268907_1280.jpg)

## 📌 Table of Contents
- [📌 Overview](#-overview)
- [📊 Dataset Description](#-Dataset-Description)
- [🎯 Objectives](#-Objectives)
- [🔄 Notebook Workflow](#-Notebook-Workflow)
- [📦 Packages](#-Packages)
- [🖥️ Environment Setup](#-Environment-Setup)
- [📂 Opening and Running the Jupyter Notebook File](#-Opening and Running the Jupyter Notebook File)
- [📝 License](#-License)


### 📌 Overview

This repository contains a Jupyter Notebook that analysis key factors influencing car fuel consumption and also predicts MPG(Miles Per Gallon)

### 📊 Dataset Description

This dataset contains information about various car models from 2014-2024. Each row represents a vehicle and includes details such as fuel efficiency (city, highway, and combined MPG), engine specifications (cylinders, displacement), drivetrain type, fuel type, and more.

### 🎯 Objectives

The objective of this analysis is to identify and evaluate the key factors that contribute most significantly to fuel consumption in vehicles. By examining features such as engine specifications, drivetrain type, and vehicle class, the analysis aims to uncover patterns and insights that influence fuel efficiency. Additionally, a predictive model is developed to estimate fuel consumption based on these critical factors.

### 🔄 Notebook Workflow
- __Data Loading:__ The notebook begins by loading the dataset and inspecting its structure.
- __Data Cleaning:__ Missing values, outliers, and categorical variables are handled. 
- __Exploratory Data Analysis (EDA):__ Various visualizations and statistics are used to understand the distribution of features and the relationships between them.
- __Data Preprocessing:__ Feature engineering, scaling, train-test splits, and feature encoding (Label Encoding and One-Hot Encoding) are applied where needed.
- __Model Training:__ Machine learning models (KNN,Random Forest and Linear Regression) are trained on the dataset to MPG(Miles Per Gallon).
- __Model Evaluation:__ The models' performance is evaluated using accuracy, precision, recall, F1-score, and other metrics.
- __Conclusion:__ Key insights are drawn from the analysis, and recommendations are provided for improving obesity prevention.

### 📦 Packages 

🐼  pandas
🔢 numpy
📊 matplotlib
🌊🐦 seaborn
📈 plotly
🧠 scikit-learn

### 🖥️ Environment Setup
It's highly recommended to use a virtual environment for your projects. 

- first clone the repo
```
  # clone repo
git clone https://github.com/lamelkekana/Fuel_Economy_Insights.git
```
You can use Python’s built-in venv module to create a virtual environment

**Create the new evironment**

```
# create enironment
python -m venv <env_name>
# activate environment
obesity_env\Scripts\activate

```
**If pip is not installed in your environment, you can install it by running:**

```
python -m ensurepip --upgrade
```
**Install the Project Dependencies**
```
pip install -r requirements.txt

```
Aternatively ,you can use use conda to create environment,this is applicable if you have anaconda installed in your machine

**Create the new evironment** -

```
 # create the conda environment
conda create --name <env>
```

**This is how you activate the virtual environment in a terminal and install the project dependencies**

```
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project, requirements.txt is provided in the the repo
pip install -r requirements.txt ```
```

### 📂 Opening and Running the Jupyter Notebook File

Make sure the environment is activated as per instruction above

```

# change directory to the path to your cloned repo
cd <repository_folder>

# Launch notebook
jupyter notebook

```
**Note:** Plotly graphs may not display properly when the notebook is first opened due to their interactive nature. To experience the full functionality of the plot, please rerun all previous cells along with the current cell to ensure proper rendering and interactivity.

### 📝 License

Arslaan Siddiqui. (2024). car_data [Data set]. Kaggle. https://www.kaggle.com/datasets/arslaan5/explore-car-performance-fuel-efficiency-data/data
Licensed under GNU General Public License v3.0.

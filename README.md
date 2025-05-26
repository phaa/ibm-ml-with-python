
# Machine Learning with Python - IBM  

This repository contains code and notebooks developed during the [Machine Learning with Python](https://www.coursera.org/learn/machine-learning-with-python) course offered by IBM Skills Network through Coursera.  

<p align="center">
 <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" title="book" width="400" />
</p>

## About the Course  
This course covers the fundamental concepts of Machine Learning and its practical applications, including data preprocessing, regression, classification, clustering, dimensionality reduction, 
fundamentals of statistics and linear algebra, model evaluation and improvement, as well as best project practices.  <br/>
Since the course lectures and labs are in English, I chose to keep all code in the same language.

## Repository Structure  
The Jupyter notebook files are organized by modules, according to the course:
```
📁 Repository structure
├── 📁 Module 1 - Introduction
├── 📁 Module 2 - Linear and logistic regression
├── 📁 Module 3 - Supervised models
├── 📁 Module 4 - Unsupervised models
├── 📁 Module 5 - Model evaluation and metrics
├── 📁 Module 6 - Final project
│   ├── 📝 Practical Project - Titanic Survivors
│   ├── 📝 Final Project - Rain Prediction in Australia
├── README.md 
```

## Technologies Used  
- **Python**  
- **Jupyter Notebook**  
- **Libraries:** NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn  

## Final Project  
The three final projects of the course are in the **Module 6** folder.  
They demonstrate the application of concepts learned throughout the course, including the best techniques and approaches taught by IBM instructors.

Developed a rainfall prediction classifier. The project involved:

- Exploratory Data Analysis (EDA): Identified and addressed data leakage and outliers.
- Feature Engineering: Created a 'Season' feature from the 'Date' column and handled categorical and numerical features.
- Preprocessing Pipeline: Built a robust pipeline for data scaling, one-hot encoding, and addressing class imbalance with SMOTE.
- Model Training & Optimization: Implemented and tuned a RandomForest Classifier and an XGBoost Classifier using GridSearchCV and Stratified K-Fold cross-validation.
- Feature Selection: Analyzed feature importances and experimented with threshold-based and iterative feature selection to improve model performance.
- Model Evaluation: Assessed model performance using classification reports, confusion matrices, and F1-scores, comparing the effectiveness of different data preprocessing and modeling techniques.
- This project demonstrates skills in data cleaning, feature engineering, building machine learning pipelines, model selection, tuning, and evaluation, particularly for imbalanced datasets.

## How to Use  
1. Clone and access the repository:  
   ```bash
   git clone https://github.com/phaa/ibm-ml-with-python.git
   cd ibm-ml-with-python/
   ```
2. Activate the virtual environment (conda or venv):
   ```bash
   conda activate ibmenv
   ```
3. Run the notebooks in Jupyter lab:  
   ```bash
   jupyter lab
   ```
*Each notebook has a cell to install the necessary dependencies.* 

## Contributions  
This repository is a record of the course learning, but suggestions and improvements are always welcome!

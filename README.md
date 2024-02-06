# MACHINE-LEARNING-APPLICATIONS-IN-HEALTHCARE-SECTOR (Heart Disease Prediction System)
Welcome to the Machine Learning Applications in Healthcare Sector repository! This project focuses on leveraging machine learning techniques to address various challenges and opportunities within the healthcare domain. under this domain i have made heart diseases prediction and will add more diseases.
            ![image](https://github.com/Lonewolf050/MACHINE-LEARNING-APPLICATIONS-IN-HEALTHCARE-SECTOR/assets/106444631/a776a91a-b420-4c12-825b-b35312012865)

# Project Description
Heart diseases have emerged as a significant public health concern in India, with a noticeable increase in mortality rates over the past few decades. Studies indicate a 34% rise in death rates due to heart diseases from 1990 to 2016, making it the leading cause of death in the country.

Preventing heart diseases has become imperative, necessitating the development of effective data-driven systems for prediction and prevention. Machine learning presents a promising avenue in this regard, offering accurate predictions that can significantly improve research and preventive measures.

This repository houses a Heart Disease Prediction System powered by machine learning. Leveraging state-of-the-art algorithms and techniques, our system aims to predict heart diseases with high accuracy. By analyzing relevant medical data, including patient demographics, clinical measurements, and lifestyle factors, our models can provide valuable insights into an individual's risk of developing heart diseases.
Problem Description :
A dataset is formed by taking into consideration some of the information of 920 individuals. The problem is : based on the given information about each individual we have to calculate that whether that individual will suffer from heart disease.

# Dataset :
The Heart disease data set consists of patient data from Cleveland, Hungary, Long Beach and Switzerland. The combined dataset consists of 14 features and 916 samples with many missing values. The features used in here are,

* **Age :** displays the age of the individual.
* **Sex :** displays the gender of the individual using the following format : 1 = male 0 = female.
* **Chest-pain type :** displays the type of chest-pain experienced by the individual using the following format : 1 = typical angina 2 = atypical angina 3 = non - anginal pain 4 = asymptotic
* **Resting Blood Pressure :** displays the resting blood pressure value of an individual in mmHg (unit)
* **Serum Cholestrol :** displays the serum cholestrol in mg/dl (unit)
* **Fasting Blood Sugar :** compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false)
* **Resting ECG :** 0 = normal 1 = having ST-T wave abnormality 2 = left ventricular hyperthrophy
* **Max heart rate achieved :** displays the max heart rate achieved by an individual.
* **Exercise induced angina :** 1 = yes 0 = no
* **ST depression induced by exercise relative to rest :** displays the value which is integer or float.
* **Peak exercise ST segment :** 1 = upsloping 2 = flat 3 = downsloping
* **Number of major vessels (0-3) colored by flourosopy :** displays the value as integer or float.
* **Thal : displays the thalassemia :** 3 = normal 6 = fixed defect 7 = reversable defect
* **Diagnosis of heart disease :** Displays whether the individual is suffering from heart disease or not : 0 = absence 1,2,3,4 = present.

  
![data describe](https://github.com/Lonewolf050/MACHINE-LEARNING-APPLICATIONS-IN-HEALTHCARE-SECTOR/assets/106444631/91a40b0b-b4e5-480c-b505-94f1dd820a77)

# Key Features:
* Data Preprocessing: The dataset is carefully examined for missing values and duplicates, which are then handled appropriately.
* Exploratory Data Analysis (EDA): A comprehensive analysis of the dataset is performed, including the visualization of feature distributions and correlation matrices.
* Model Training: Several machine learning models such as Logistic Regression, K-Nearest Neighbors, Random Forest, and Decision Tree are trained on the dataset.
* Model Evaluation: The accuracy of each model is evaluated on both training and test datasets. Precision-Recall and ROC curves are also plotted for the Logistic Regression model to assess performance.
* Graphical User Interface (GUI): A simple GUI application built using Tkinter allows users to input their medical data and receive predictions for heart disease.
* GitHub Repository Structure: The repository is well-organized, containing code files, sample dataset, trained models, and a README file providing detailed instructions for usage and setup.
# Technology Used :

* **Python Programming Language** : The core programming language used for this project. Python is known for its simplicity      and readability, making it an excellent choice for various applications.
  
* **Machine Learning** : This project is mainly based on Machine Learning and its concepts . It helps in the extraction of       keywords and generating a concise and brief report of the text .
  
# Platform Used:
* Jupyter Notebook : The code is written and executed in the web-based Python Jupyter Notebook .

# Python Modules Used :

* **NumPy:** Used for numerical computations and working with arrays or matrices efficiently.
  
* **Pandas:** Utilized for data manipulation and analysis, particularly for loading datasets into DataFrame structures and performing operations like filtering, grouping, and merging
  
* **Scikit-learn:** For machine learning tasks such as model training, evaluation, and preprocessing
  
* **Matplotlib:** A plotting library for creating static, interactive, and animated visualizations in Python. It's used here for creating histograms, precision-recall curves, ROC curves, and bar charts.
  
* **Seaborn:** Built on top of Matplotlib, Seaborn provides a high-level interface for drawing attractive and informative statistical graphics. It's used here for creating a correlation matrix heatmap.
  
* **Tkinter:** A standard GUI toolkit in Python, used for creating simple desktop applications. It's employed here to create a basic user interface for inputting data and displaying prediction results.
  
# Machine Learning Models:

* Logistic Regression
  
* K-Nearest Neighbors (KNN)
  
* Random Forest
  
* Decision Tree

# Graphical User Interface

![gui with data input](https://github.com/Lonewolf050/MACHINE-LEARNING-APPLICATIONS-IN-HEALTHCARE-SECTOR/assets/106444631/7c1e43ba-da6c-4ca4-85d9-edd3af741829)
![gui result](https://github.com/Lonewolf050/MACHINE-LEARNING-APPLICATIONS-IN-HEALTHCARE-SECTOR/assets/106444631/e7289d9c-198d-4f0a-8126-4d848a0d9478)


  
# Usage:
* Clone the repository to your local machine.
* Ensure you have the required Python libraries installed. You can install them using pip: pip install -r requirements.txt.
* Run the main Python script (main.py) to execute the heart disease prediction system.
* Follow the instructions provided by the GUI to input your medical data and obtain predictions.
  
# Contributions: This Project has been Created by-
* **Aman Kumar** Github Profile :- https://github.com/Lonewolf050
* **Kartikey Teotia** 
* **Manas Kumar
* **Akul Goel**
# Contributions:
Contributions to this project are welcome! If you find any bugs, have feature requests, or want to contribute enhancements, feel free to open an issue or submit a pull request.
# License
This project is licensed under the MIT and Apache 2.0 License - see the LICENSE file for details.

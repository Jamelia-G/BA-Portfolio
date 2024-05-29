# Jamelia Gordon - Data Analyst Portfolio
Welcome to my Data Analyst portfolio! Below are the highlights of some key projects showcasing my expertise in data analysis, machine learning, and data visualization.

## Table of Contents
---
* Python
   * [Facial recognition](https://github.com/Jamelia-G/Facial-Recognition)
* R 
   * [Predicting Employee Attrition](https://github.com/Jamelia-G/Employee-Attrition)
* Tableau
   * [Visualizing Airport Delays](https://github.com/Jamelia-G/Visualizing-Airport-Delays)

## Projects
---
### Predicting Employee Attrition using R

**Project:** [Predicting Employee Attrition](https://github.com/Jamelia-G/Employee-Attrition)

**Objective:** To predict employees likely to leave

**Description:** 
The project delves into an employee dataset from 2018, encompassing demographic details, job satisfaction indicators (such as workload, years of experience, salary level, etc.), job-specific information (including location, business travel), and other pertinent data. 
The project leverages supervised learning techniques, including logistic regression, decision trees, random forests, and Lasso regression, and evaluates their effectiveness by using the False Negative Rate. Emphasizing the false negative rate, the project prioritizes minimizing instances of incorrectly predicted negative outcomes.

In principle, the project follows this framework: <br>
Uncertainty: 	Employee exits or Employee stays <br>
Business Deployment: Target employees with employee benefits <br>
Goal: $E[Profit|X,D] = P(Employee stays | X,D) * V(X,D)$

**Skills:** Data Cleaning, Exploratory Data Analysis, Predictive Modelling, Supervised Learning

**Technology:** R, Logistic Regression, Decision Trees, Random Forests, and Lasso Regression

### Face Recognition using Convolutional Neural Networks (CNN)

**Project:** [Facial recognition](https://github.com/Jamelia-G/Facial-Recognition)

**Objective:** To recognize identities given an image

**Description:** 
This project leverages facial embeddings, the VGG Face Model, and CNNs to accurately identify facial embeddings and predict identities from a pool of 105 identities. The resulting "SoftMax classifier Model" was trained on the Pins Face Recognition Dataset from Kaggle, which comprised 17,534 faces across 105 identities. The VGG Face model was first used to extract facial embeddings, which were then passed through a neural network outfitted with ReLu activation, Batch Normalization, and regularization techniques. 

**Skills:** Creating Metadata, Image Augmentation, Data Preprocessing, CNN model, hyperparameter tuning, Model Evaluation

**Technology:** PyTorch, Python (NumPy, Matplotlib, Sckit-Learn), Jupyter Notebook, Google Colab, Google Cloud Platform(GCP)

### Data Visualization of Flight Delays

**Objective:** To conduct root cause analysis of delays at MCO airport.

**Description:** 
This project uses Tableau and Tableau Prep to Extract and Load flight data for MCO airport. Project leverages Line of Detail, Calculated Fields, Parameters and Projections to diagnose the driving cause of delays and convey it clearly to stakeholders.

**Skills:** Connecting to Data Source, Filtering and Extracting, Data Visualization, Basic Statistics, Designing interactive filters, parameters, and actions

**Technology:** Tableau Prep, Tableau

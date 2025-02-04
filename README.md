# 5G Energy Consumption Modeling

This project leverages machine learning techniques to estimate the energy consumption of 5G base stations (BSs) based on engineering configurations, traffic conditions, and energy-saving methods. It was developed as part of the **ITU Global 5G Energy Consumption Challenge 2023**.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Key Features](#key-features)
4. [Problem Statement](#problem-statement)
5. [Dataset](#dataset)
6. [Tech Stack](#tech-stack)
7. [Approach](#approach)
8. [Results](#results)
9. [Future Improvements](#future-improvements)
10. [Usage](#usage)
11. [Contributions](#contributions)
12. [References](#references)

---

## Project Overview

The telecommunications industry faces significant challenges in managing the energy consumption of 5G networks. With **network operational expenditures (OPEX)** accounting for nearly 25% of telecom operators' costs—90% of which is due to energy bills—this project provides a data-driven solution to optimize energy consumption in **radio access networks (RAN)**.

### Key Objectives:
- Develop machine learning models to estimate energy consumption of 5G base stations.  
- Analyze the impact of engineering configurations, traffic conditions, and energy-saving methods.  

### Challenge Timeline:  
**July 5, 2023 – September 30, 2023**  

_For more details about the competition, [click here](#)._  

---

## Objectives

1. Analyze 5G energy consumption data to identify key trends and drivers.
2. Develop predictive models to forecast energy usage in different scenarios.
3. Provide insights to guide the development of sustainable 5G networks.

---

## Key Features

- **Data Exploration and Preprocessing**  
  Comprehensive exploration of 5G energy consumption data, including cleaning and handling missing values.

- **Visualization**  
  Intuitive and detailed visualizations to uncover patterns and correlations in energy usage.

- **Machine Learning Models**  
  Implementation of machine learning algorithms (regression) to predict energy consumption trends.

- **Optimization Insights**  
  Insights into optimizing energy consumption in 5G networks.

---

## Problem Statement
More than **70% of energy** in a telecom operator's network is consumed by RAN, particularly 5G base stations.  
The project aims to:
- Accurately predict energy consumption of base stations.   

---

## Dataset
The dataset, provided by the **International Telecommunication Union (ITU)**, includes cell-level traffic statistics for 4G/5G sites collected over several days. It is a simplified version designed for learning purposes.

### Features:
 - **Engineering Configurations**: Base station settings affecting energy consumption including hour-level energy consumption specifications.
- **Energy-Saving Methods**: Techniques implemented to reduce energy usage.  

### Target Variable:
- **Energy Consumption** (in kilowatt-hours)  

---

## Tech Stack
- **Languages**: Python  
- **Libraries**:  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

## Approach
### Data Preprocessing
- Cleaned and standardized the dataset.  
- Handled outliers.  
- Scaled features using StandardScaler.  

### Exploratory Data Analysis (EDA)
- Visualized energy consumption patterns across different base stations.  
- Analyzed correlations between traffic, configurations, and energy usage.  

### Model Development
- Tested various machine learning algorithms:  
  - Linear Regression  
  - Random Forest  
  - Gradient Boosting
  - Decision Tree
  - Lasso Regression
  - Linear Support Vector Regression
  - Ridge Regression
- Developed a meta-model by stacking multiple base models (e.g., Decision Trees, Gradient Boosting, and Random Forests) to enhance predictions of the target variable. 

### Model Evaluation
- Used train-test splits and cross-validation for robust evaluation.  
- Optimized hyperparameters using GridSearchCV.  

---

## Results

- **Mean Absolute Error (MAE)**: `4.3432`  
- **R² Score**: `0.8124`

---

## Future Improvements
- Integrate additional features such as weather conditions and advanced power-saving algorithms.  
- Experiment with advanced techniques like neural networks for better predictions.  
- Develop a dashboard for real-time energy consumption monitoring and optimization.  

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/OsatoOsazuwa/5G_Energy_Consumption_Modeling.git
   
2. Install required libraries:
   ```bash
   pip install -r requirements.txt

   

## Contributions
  Contributions are welcome! Feel free to open issues or submit pull requests to enhance this project.

## References
- [ **ITU Global 5G Energy Consumption Challenge 2023**](https://challenge.aiforgood.itu.int/match/matchitem/83)  
- [NumPy Documentation](https://numpy.org/doc/)  
- [Pandas Documentation](https://pandas.pydata.org/docs/)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)





































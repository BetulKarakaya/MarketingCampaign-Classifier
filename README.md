# **Bank Marketing Campaign Classification Project**

## **Project Overview**

This project focuses on the analysis and prediction of client subscription to a term deposit based on the data from direct marketing campaigns (phone calls) of a Portuguese banking institution. The primary goal is to predict whether a client will subscribe to a term deposit (binary classification) using machine learning models.

## **Data**

The dataset used for this project includes various client and campaign-related attributes, such as:

- **Client Information:** Age, job, marital status, education level, etc.
- **Campaign Features:** Number of contacts, days since last contact, etc.
- **Other Attributes:** Duration of last contact, previous outcome, etc.

The target variable is `y`, which indicates whether the client subscribed to the term deposit or not.

### **Data Source**

The dataset for this project is sourced from the UCI Machine Learning Repository. You can find more information and access the dataset [here](https://archive.ics.uci.edu/dataset/222/bank+marketing).
Citation:
S. Moro, P. Cortez and P. Rita. (2014). A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31.

## **License Of Data**

The dataset used in this project is sourced from the UCI Machine Learning Repository and is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to use, share, and adapt the data as long as you give proper credit to the original authors.


## **Exploratory Data Analysis (EDA)**

The EDA was performed to better understand the distribution of the features and their relationships with the target variable. The following libraries were used:

- **Pandas:** Data manipulation and initial exploration.
- **Plotly:** For creating interactive visualizations.
- **Scikit-Learn:** Basic feature scaling and transformation.
- **Seaborn:** Visualize complex analysis

Key findings from the EDA:
- Relationship between categorical features like job, marital status, and education with the target variable.
- Analysis of continuous features such as age groups.
- Correlation between features and the target variable.
- To better understand the internal structure of the data and determine the necessary steps for preprocessing and classification

## **Preprocessing**
   -  Converting categorical variables to numerical values using methods like label encoding and one-hot encoding.
   - Correcting data ranges with Min-Max scaling.
   - Applying Yeo-Johnson transformation to reduce skewness and bring the data closer to a normal distribution.
   
## **Classification Models**
   - Training machine learning models such as XGBoost and neural networks.
   - Hyperparameter tuning for XGBoost using GridSearch to optimize model performance.


  
## **Upcoming Steps**

### 1. **Application Development**
   - Developing a user-friendly interface using **Streamlit** to showcase the classification results in real-time.

## **License**

This project is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to use, share, and adapt the material, as long as you give appropriate credit to the author.



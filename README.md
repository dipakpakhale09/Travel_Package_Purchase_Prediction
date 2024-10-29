# ML_Project >> Travel Package Purchase Prediction

##  PROBLEM STATEMENT:
  
  Tourism is one of the most rapidly growing global industries and tourism forecasting is becoming an increasingly important activity in planning and managing the industry.
Because of high fluctuations of tourism demand, accurate predictions of purchase of travel packages are of high importance for tourism organizations.
The goal is to predict whether the customer will purchase the travel or not.

  #### APPROACH :
  The classical machine learning tasks like Data Exploration, Data Cleaning,Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms that’s best fit for the above case.
  
  We need to analyze the customers' data and information to provide recommendations to the Policy Maker and Marketing Team and also build a model to predict the potential customer who is going to purchase the travel package.

## ARCHITECTURE :

![image](https://github.com/Pratik-Salunkhe/ML_Project/assets/96179015/8cb82937-0527-448e-be52-5a0276335bbd)

##### 1) DATA COLLECTION AND INSERTION
##### 2) UNDERSTANDING OF DATA
          * Checking for size of data
          * Checking for statistical description of data
          * Checking for data types of columns
          * Value counts for categorical columns
##### 3) DATA - PREPROCESSING
          * Handling of duplicate records and columns 
          * Handling of Null Values
          * Handling of Categorical Data
          * Handling of Numerical Data
          * Handling of Outliers
          * Data Transformation
          * Handling Class Imbalance
##### 4) EXPLORATORY DATA ANALYSIS AND VISUALIZATION
          * Visualizations of each categorical features

![countplot_categorical_features](https://github.com/Pratik-Salunkhe/ML_Project/assets/96179015/f971fab8-22b7-443c-b065-9affdcd58af5)

          ### Observation:
              1. **Self Enquiry** is has been done by most of the customers
              2. Most of the Customers are **Salaried and Small Bussiness**.
              3. **Male** customer are **more** than **female** customers
              4. From the Productpitched **Basic** has been taken most wheather **King** very less.
              5. Most of the Customer are **Married**.
              6. Destination of Most of the Customer is **Executive** and **Manager** and Less is **VP**.


          * Visualizations of each categorical features with Target variable   *** NOTE : IMAGES Are in github Repo ***

          ### Observation:

              1. **Basic product Pitch**  Purchase More packages compare with their count.
              2.  **Unmarried**  Purchase More packages compare with their count.
              3.  **Manager**  Purchase More packages compare with their count.
              4. Rest of all are purchasing package in very normal according to their count.

          * Visualizations of each numerical continuous features  *** NOTE : IMAGES Are in github Repo ***

          ### Observation :
    
              1. Most of the customers between **26-35** age and **36-45** age group purchase the package most 
              2. Most Customer are from duration of 5-15 Duration of Pitch
              3. Best rate of purchasing Package is from 25-35 Duration of Pitch
              
          * Visualizations of each numerical discrete features  *** NOTE : IMAGES Are in github Repo ***

#### MODEL BUILDING EVALUATION :
  We experimented with algorithms like Logistic Regression, Decision Trees, Random Forests, and K-Nearest Neighbors (KNN). Despite encountering over-fitting with some models, we achieved improved precision through techniques like SMOTE for handling imbalanced data.
  
#### PERFORMANCE METRICS AND TUNING :
  We assessed model performance using accuracy and precision metrics, with KNN emerging as the best-performing model after hyper-parameter tuning. Randomized Cross Validation (RandomizedCV) aided in comparing and selecting the optimal model.

  ![performance Tabulation1](https://github.com/Pratik-Salunkhe/ML_Project/assets/96179015/b74e34ae-9343-41c9-b745-c1dd173474ca)

## CONCLUSION :

  ### Our project demonstrates the potential of machine learning in forecasting customer behavior for tourism companies. By leveraging advanced techniques and thorough analysis, we enable businesses to make informed decisions and enhance marketing strategies in the dynamic tourism landscape.


![image](https://github.com/Pratik-Salunkhe/ML_Project/assets/96179015/a6295e4f-9819-461b-9dcb-2b67cbf0c509)

  







  


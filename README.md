# Online_Purchase_Prediction
Machine learning final project focused on developing a predictive model to determine whether a website visit would result in a purchase.

## Project Overview
This project was completed as the final project for my Machine Learning course during my undergrad. The goal was to create a machine learning model that could predict whether a web visit resulted in a purchase based on user browsing behavior. 

The project involved exploring and analyzing e-commerce data, data cleaning, classifying data, and evaluating the performance. 

## Dataset
The dataset used in this project was the Online Shoppers Purchasing Intention Dataset from the UCI Repository. The dataset includes features such as:
* "Revenue"
  * Binary feature where:
      * A “True” entry for this features means that when a user visited a website, there was a transaction that was made by the user
      * A “False” entry for this features means that when a user visited a website, there was no transaction that was made by the user
* "Administrative" , “Administrative_Duration" , "Informational", "Informational_Duration", "ProductRelated", "ProductRelated_Duration"
  * All of these features explain the types of pages visited by the user, and how long they spent on these pages
* "Bounce Rate", "Exit Rate",  "Page Value"
  * These features explain how a user leaves the website
* “SpecialDay”, “Month”, “OperatingSystem”, “Browser”, “Region”, “TrafficType”, “VisitorType”, and “Weekend” 
  * These are some more more self explanatory features included in this set

Dataset: https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset
## Method 
The project followed many steps including: 
1. EDA
2. Data Cleaning
3. Model Selection
4. Model Training
5. Model Evaluation
6. Concluding Thoughts

## Technologies Used
* Python: Programming language
* Scikit-learn: Machine Learning model development, training, tuning, and evaluation
* Matplotlib: Data Visualizations
* Seaborn: Data Visualizations
* Pandas, Numpy, SciPy
  

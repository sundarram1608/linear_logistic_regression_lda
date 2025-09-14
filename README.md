# linear_logistic_regression_lda
This repository contains all the files used for analysis of two different data sets.<br>
Techniques of Encoding, Linear Regression, Logistic Regression &amp; Linear Discriminant Analysis are leveraged in this project.<br>
The coding language used here is Python Programing.

## DataSet:
- Credit card usage of customers (bank_marketing_part1_Data.csv).
- Tour Insurance claims (insurance_part2_data.csv).

## Code File: (.ipynb)
- code_file.ipynb

## Business Report: (.pdf)
This report provides a detailed explanation on approach used, record inferences, insights and provide suitable business solutions/ recommendations.<br>

- Credit card usage of customers is analyzed by clustering them in to different segments and suitable business recommendations for promotional purposes are made. <br>
- The techniques of hierarchical clustering using dendrograms and non-hierarchical method of KMeans clustering are employed.<br>
<br>
- The insurance claims data of past few years are used to make a model that predicts the claim status, based on which suitable recommendations are made to the management<br>
- The techniques of CART (Classification And Regression Tree), Random Forest & ANN (Artificial Neural Networks) are employed in the model building.  

## Libraries used:
> pandas<br>

> numpy<br>

> seaborn<br>

> matplotlib<br>
> > - pyplot

> scipy<br>
> > - cluster.hierarchy - dendrogram, linkage, fcluster 

> sklearn<br>
> > - preprocessing - StandardScaler,cluster - KMeans<br>
> > - metrics - silhouette_samples, silhouette_score, classification_report, confusion_matrix, roc_auc_score, roc_curve<br>
> > - tree - DecisionTreeClassifier<br>
> > - ensemble - RandomForestClassifier<br>
> > - neural_network - MLPClassifier<br>
> > - model_selection - train_test_split, GridSearchCV<br>

## How to run the code?
- Fork & Clone the repository
- Install the above libraries (virtual environment recommended) if not available using the command `pip install` in terminal
- Open the Code file and run all the cells. (Same Folder hierarchy as in repository to be used)



**This detailed analysis was performed by me as a part of my course work in Post Graduate Program in Data Science & Business Analytics**
 





# Company-Bankruptcy-Detection
#Introduction
Company Bankruptcy 📉💸


Data from the Taiwan Economic Journal for the years 1999–2009 representing company bankruptcy based on the business regulations of the Taiwan Stock Exchange.

In this repository we will use various predictive models to see how accurate they are in detecting whether we can correctly predict which comapnies will face bankrptcy in the future. As described in the data section, the dataset contains:

95 features (X1-X95, business regulations of Taiwan Stock Exchange)

1 Vector of labels

Our aim in this project is to use these features to understand their impact/role on the selected models and how they can help us recognizing the companies that are close to bankrupcty.
# Important :
 I have written the inferences in the ipynb file itself
# Requirements

Pandas , NumPy ,Scikit-learn , Matplotlib , Seaborn,Random Forest Classifier, Decision Tree Classifier , Logistic Regreesion,SVC, KNN

# Exploratory Data Analysis (EDA) :

In the EDA part, analyzed every feature using histogram, checked the correlation of every feature with each other. Checked the correlation among the numeric columns. 
Also correlation of categpric columns with Target columns.Correlation of numeric columns with target columns. Studied their heatmap.Drew inferences.


# Data Preprocessing:
In this step I have checked for missing values and duplicate values. Balanced the imbalance data using SMOTE. Used train test split for splitting the data.

# Feature Selection:
   Chose 86 features using feature selection library
# Model Selection:
Tried different machine learning algorithms such as logistic regression, decision tree, random forest,KNN. The models are trained on the training set and evaluated on the testing set using different evaluation metrics such as accuracy, precision, recall, and F1-score.

# Model Evaluation:
 Performed model evaluation using accuracy score, classification report, F1 score, confusion matrix.  
 
 KNN gave the best accuracy which is 98%

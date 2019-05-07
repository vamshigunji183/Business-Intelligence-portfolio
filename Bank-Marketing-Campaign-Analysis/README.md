# Bank-Marketing-Campaign-Analysis

- Analyzed the prior marketing campaigns of a Portuguese Bank using various ML techniques like Logistic Regression, Random Forests,Decision Trees, Gradient Boosting and AdaBoost and predicted if the user will buy the Bank’s term deposit or not

- Recommended, the marketing team, ways to better target customers using feature importance maps and business intuition


Instructions to run the code:
1. Make sure the data file ("bank-additional-full.csv") is in the same directory as the ipython notebook or
edit the ipython notebook accordingly.
2. Make sure to run the notebook in python 3 environment.
Make sure all the dependencies used in the notebook are installed in the local machine.
3. Run the code sequentially as given in the notebook.
4. Notebook is commented adequately to give the rational, inferences of the executed code.

### Overview
* Load data
* Exploratory Data Analysis
  * Categorical variables
      Numbers of customers...
      * JOBS <img src="./img/job.JPG"  width="50%">
      * Martial<img src="./img/martial.JPG"  width="50%">
      * Education<img src="./img/education.JPG"  width="50%">
      * Default<img src="./img/default.JPG"  width="50%">
      * Loan<img src="./img/loan.JPG"  width="50%">
      * Contact<img src="./img/contact.JPG"  width="50%">
      * Month<img src="./img/month.JPG"  width="50%">
      * Day of week<img src="./img/day.JPG"  width="50%">
      * Out come<img src="./img/joboutcome.JPG"  width="50%">
      * Target label<img src="./img/Y.JPG"  width="50%">

  ### Normalize the Data
  ### Accessing the missing values
  ###### Correlation
Correlation heatmap![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/correlation-heatmap.JPG "Correlation heatmap")


### Train and validate

|Model| AUC Score| ROC Curve|
|------------|------------|----------|
|Logistic Regression|0.7900|Logistic Regression!<img src="./img/ROC-LR.JPG"  width="50%">|
|Decision Tree |0.7919|Decision Tree <img src="./img/ROC-DT.JPG"  width="50%">|
|Random Forest|0.7979|Random Forest<img src="./img/ROC-RF.JPG"  width="50%">|
|Gradient Boosting|0.80065|Gradient Boosting<img src="./img/ROC-GB.JPG"  width="50%">|
|Ada Boost|0.8006|AdaBoost<img src="./img/ROC-Ada.JPG"  width="50%">|

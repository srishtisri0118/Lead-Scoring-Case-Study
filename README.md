# Lead-Scoring-Case-Study

Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

**Data Exploration** <br>
* Import libraries <br>
* read 'Leads.csv' file  <br>
* The ‘Leads.csv’ has the dataset present having shape (9240, 37) <br>
* The ‘Leads Data Dictionary.csv’ is data dictionary which describes the meaning of the attributes present in the “Leads” dataset <br>

**Data Cleaning and Preparation** <br>
* Check the null values and drope columns with <40% Null values <br>
* Check for missing values and treat them <br>
* Drop uneccesary columns <br>
* Bifurcate columns into categorical and numerical for visualization <br>

**Data Visualization** <br>
* Univariate and Bivariate analysis <br>
* Plot barchart for Categorical attributes to find the relation with Target variable <br>
* Plot pairplot and heatmap for Numerical attributes to find the relation with Target variable <br>

**Data Preparation for Modeling** <br>
* Create Dummy variables for categorical variables <br>
* Drop the categorical attributes for which dummy variables are created <br>
* Split the dataset into train - test data, in 70:30 ratio <br>
* Use StandardScaler() function to do Feature Scaling so that all variables are on the same scale <br>
* Feature scaling using RFE <br>

**Model Building** <br>
* Use GLM to build the model <br>
* Check p-value to eliminate attributes with high p-value <br>
* Predict on the final Model using an optimal cutoff <br>
* Model Evaluation <br>
* Plot accuracy sensitivity and specificity graph <br>
* Calculate Evaluation Metrics for train model <br>
* Plot ROC curve <br>
* Test the test data on Model
* Calculate Evaluation Metrics for test model <br>
* Assign the Lead score <br>






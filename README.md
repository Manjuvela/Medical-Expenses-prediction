
# Medical Expepenses

We are going to Predict the Future Medical Expenses of our Patients using some of the relevant information that is provided in the dataset.

The Factors and their Importance in determining the Medical Expenses of our Patients based on certain features.

Such as the Age, The Gender, The Body Mass Index, The Region, The Smoking Behavior. This Predictive Analysis is going to be a Regression Problem.

To Solve the Problem, use a lot of Regressors such as Linear Regressor, Random Forest Regressor, etc. Also understanding the Business Implications of this Project, and How this Project can be helpful in terms of Money Making or Money Saving.

Health is the extent of an individual’s continuing physical, emotional, mental, and social ability to cope with the environment.
And just because of that, you spend a lot of money just to stay fit.

You can Make an application that can help people to understand the factors which are making them unfit and the factors which are making them unfit so that it can reduce their Medical Expenses.

You can also use this Health Expense Predictor in Hospitals so that the Patients can adjust their Medical Expenses.
## Installation

Python Libraries: -

- Numpy for Mathematical Calculations.
- Pandas for Dataframe Manipulations.
- Seaborn, Matplotlib, and plotly for Data Visualizations.
- Plotly is an advanced Data Visualization Library which will help to Build amazing and Interesting Visualizations for driving huge Business Insights.
- “Fivethirtyeight” Background for our Plots.
## Documentation

Predicting the Medical Expenses of a Patient. Some Regions are Hygienic, Clean, Neat, and Prosperous, But some Regions are not The Usefulness of this factor only and only after analyzing and comparing this column concerning the “Expenses” Column.

- The Smoking factor is also considered to be one of the Most Important factors as people who smoke are always at risk when their age reaches 50 to 60.

- The Sex of the person can also play a vital role in predicting the medical expenses of a Patient.

- Our dataset contains 1338 rows and 7 columns.
The columns present in the dataset are ‘age’, ‘sex’, ‘BMI’, ‘children’, ‘smoker’, ‘region’, and ‘expenses’.

- The “Expenses” column is the target column and the rest are independent columns.

- Age is an important factor for predicting medical expenses because young people are generally more healthy than old ones.

- And the Medical Expenses for Young People will be quite less as compared to Old People.
For most adults, an ideal BMI is in the 18.5 to 24.9 range.

- For children and young people aged 2 to 18, the BMI calculation takes into account age and gender as well as height and weight.

- If your BMI is: below 18.5 – you are in the underweight range.

- BMI is useful for estimating the Medical Expenses of Patients.

- people having very less BMI or very high BMI have more chances of needing medical help and hence more expenses.

- The People who have Children have more pressure due to the Education, and Other Requirements of their children as compared to the People who do not have Children.

- we need some more information about the Different Regions specified in the Dataset.

- Understood the importance of Data analysis and visualization for determining the association between features.

- Understood, How to build Intuition by building Insights from Data Visualizations.

- Got to know about dealing with Categorical variables.

- You learned about different Assumptions to be satisfied before using a Linear Regression Model
Got to know about different predictive models such as Linear Regression, Random Forest, and Gradient Boosting models.

- Got to know how to ensemble different models
Understood the Importance of Performing Cross Validation on the Data.

- You learned the Importance of Comparing different Predictive Models.

Also came to know that the Most Important Factor to Predict the Medical Expenses of a Patient is Smoking Behavior and Age.





## Contributing

To perform a Univariate Analysis of the data and find some interesting facts about the features in the dataset.
- Univariate analysis is perhaps the simplest form of statistical analysis. Like other forms of statistics, it can be inferential or descriptive.
- The key fact is that only one variable is involved.
- Bivariate analysis is one of the simplest forms of quantitative analysis. It involves the analysis of two variables, to determine the empirical relationship between them.
- Bivariate analysis can help test simple hypotheses of association.
Analysis: -
- Compare the Age and the Expenses of our patients using a scatter plot.
- To plot a scatter chart, you are going to use the Plotly library that you imported at the beginning of this Module.
- The reason why you are using Scatter Plot using the Plotly library is that Plotly provides you with an Interactive Chart, through which you can easily drill up and down, and extract information from the charts very easily.
- We can see the Tools available for a Plotly Chart by hovering over the Top-Right of the Chart.
- Multivariate analysis is based on the principles of multivariate statistics, which involves observation and analysis of more than one statistical outcome variable at a time.
- an increasing pattern for BMI as well.
- For smokers with less BMI, the expenses are around 20 thousand rupees.
- For smokers with high BMI, the expenses are around 50 thousand rupees.
- For non-smokers, BMI is not a huge factor, their expenses range from 5k to 10k.
- Bubble Chart to represent the relation of expense with BMI, age, and smoking.

Encoding the Categorical columns: -
- The sex column,
- The smoker column, and
- The region column from the dataset all have values in object data type.

Perform feature scaling: -
- Feature scaling is a method used to normalize the range of independent variables or features of data.
- Feature Scaling helps to normalize the data within a particular range. Sometimes, It also helps in speeding up the calculations in an algorithm.
- Performing Feature Scaling using the Standard Scaler Library from sklearn.
- The transform function applies feature scaling on the testing data because the fit_transform function will first learn all the patterns in the data and then it will apply feature scaling on the data.
- We are going to build the most simple Predictive Model using Linear Regression Model.
- It is important to understand the Assumptions associated with a Model, before using that particular model because, It helps to understand whether this Model is appropriate for the Dataset or not.

Linearity: -
- The assumption of Linearity means that the relationship between the dependent variables and the independent variables must be linear.

Homoscedasticity: -
- The Homoscedasticity Assumption says that you should not have lots of Noise or Random Disturbance between the Dependent and Independent 
Variables of the Data.
-Noise or Random Disturbance is referred to the Outliers present in the Data. Homoscedasticity Assumption in a Linear Regression.

Random Forest: -
- Random Forest is an ensemble learning method for classification and regression by constructing multiple numbers of decision trees at training time and Outputting the average prediction of the individual trees in case of regression whereas outputting the class that is the mode of the classes in case of classification.

Gradient Boosting:-
- Gradient Boosting is a very popular Boosting technique.
- It works by sequentially adding the previous predictors under fitted predictions to the ensemble ensuring that the errors made previously are corrected.

Ensembling: -
- Ensemble modeling is a process where multiple diverse models are applied to obtain better predictive performance than could be obtained from any of the constituent learning algorithms alone.

Cross-validation: -
- Cross-validation is a resampling procedure that is used to evaluate our machine-learning models on limited data samples.
- The Gradient Boosting Model is the Best Choice whereas the Linear Regression Model is the worst for this Case.
- We have successfully built our predictive model and compared these predictive models based on their accuracies and Results.
## Insights

The People in the Southeast region have very high expenses as compared to people living in other regions.
So, you can cap all the Other three Regions that is the Southwest Region, the Northeast Region, and the Northwest Region, as the Expenses in these three regions are very similar to each other.
Finally, after a lot of Knee-breaking analysis. Concluding that somehow all the columns are important and shall not remove any of these columns from the dataset.

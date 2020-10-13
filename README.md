# DataAnalytics-Loan_Approval_Prediction-

Problem Statement:

About Company

XYZ Finance Company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan after that company validates the customer eligibility for loan. However, doing this manually takes a lot of time. Hence it wants to automate the loan eligibility process (real time) based on customer information.

Problem
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments; those are eligible for loan amount so that they can specifically target these customers.

So the final thing is to identify the factors/ customer segments that are eligible for taking loan. How will the company benefit if we give the customer segments is the immediate question that arises. The solution is ….Banks would give loans to only those customers that are eligible so that they can be assured of getting the money back. Hence the more accurate we are in predicting the eligible customers the more beneficial it would be for the XYZ Finance Company.

Type of problem:

The above problem is a clear classification problem as we need to classify whether the Loan_Status is yes or no. So this can be solved by any of the classification techniques like Decision Tree Algorithm.

Download Dataset Here: LoanPredictionDataset

Dataset Description: There are 2 data sets that are given. One is training data and one is testing data. It’s very useful to know about the data columns before getting in to the actual problem for avoiding confusion at a later state. Now let us understand the data columns (that has been already given by the company itself) first so that we will get a glance. The table shows the variable names and their corresponding descriptions.


Section: A (Exploratory Data Analysis)

1.  Let us analyse and visualize the categorical attribute of the given train dataset using single variable.                                      (15)

 Find out the number of male and female in loan applicants data.
 Find out the number of married and unmarried loan applicants.
 Find out the overall dependent status in the dataset.
 Find the count how many loan applicants are graduate and non graduate.
Find out the count how many loan applicants property lies in urban, rural and semi-urban areas.




2.  What conclusions are you derived from the single variable analysis?                                                                                          (5)

3.  To visualize and plot the distribution plot of all numerical attributes of the given train dataset i.e. ApplicantIncome,  CoApplicantIncome and LoanAmount.                                                                                                                                                                                                                                                                     (5)

4. Also visualize and plot the Question-1 based on Loan_status of loan applicant (Multi variable analysis).                                   (20)

5. What conclusions are you derived from the multi variable analysis?                                                                                             (5)

                                                                             Section: B (Decision Tree Classifier)

1.      Building a Decision Tree Classifier in Python using Scikit-learn Library                                                                       (50)

We’ll now predict if a consumer is likely to eligible for loan amount using the decision tree algorithm in Python. The data set contains a wide range of information for making this prediction, including the gender, married, dependents, education, self-employed, applicant_income, co-applicant_income, loan_amount, loan amount term, credit_history, property_area and whether the individual was eligible for loan amount ( i.e. loan_status). The following steps should be followed during building a decision tree classifier:

 i.      Import the libraries required to build a decision tree in Python.

 ii.     Load the train dataset and test dataset using the read_csv () function in pandas.

iii.      Data Cleaning: Preprecessing of both dataset.

              a)       Missing Values: Check where there are missing values and fix them appropriately.

 iv.     Feature Selection: Separate the independent and dependent variables using the slicing method.

 v.      Encoding to numeric data: Convert each of the categorical variables in to numeric data for modeling. For handling categorical variables, there are many methods like One Hot Encoding or Dummies. 

 vi.     Splitting Data: Split the data into training and testing sets.

 vii.    Building Decision Tree Model: Train the model using the decision tree classifier.

 viii.   Evaluating Model: Predict the test data set values using the model above.

  ix.    Calculate the accuracy of the model using the accuracy score function.

  x.     Visualizing Decision Trees


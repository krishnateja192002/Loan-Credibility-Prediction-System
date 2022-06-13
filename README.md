# Loan-Credibility-Prediction-System
Loan Credibility Prediction System using Data Mining Techniques

why:
As we know that now-a-days there is a rapid 
growth in banking sector, resulting lots of people are applying 
for bank loans. Finding out the applicant to whom the loan 
will be approved is a difficult process. Data mining 
techniques are becoming very popular nowadays because 
of the wide availability of huge quantity of data and the need 
for transforming such data into knowledge. Techniques of 
data mining are implemented in various domains such as
retail industry, telecommunication industry, biological data 
analysis, etc. A model which 
predicts loan approval/rejection of an applicant using data 
mining techniques. This can be done by training the model 
with the data of the previous records of the people applied for
loan

1.DATA SET:
Two data sets are given, one is the training data set and the 
other is the testing data set. Columns in the data sets are as 
shown in the table

![image](https://user-images.githubusercontent.com/73900660/173396419-8c2da6c2-70f4-4d60-8df7-9a64c7603811.png)

2.Data Exploration
All the packages needed to explore the data were imported, 
Then the data was explored by checking the first few columns 
and rows 
After which the summary of the statistics, the missing values, 
number of rows and columns was checked

3.Data Cleaning
After exploring the data set, some missing values were found 
which had to be filled using the median for numerical data 
and for categorical data, mode instead of mean.

4.Data Visualization
The value count was done and then data was visualized.
Even after the data analysis, there is still no unique factor to 
determine loan status. Categorical data was converted into 
numerical data

5. DATA MODELLING:
After Data Visualization, the data is modelled/trained. For
this the packages of three algorithms (Logistic regression, 
Decision tree and Random forest) were imported. Themodel 
was then defined and the accuracy score was evaluated.
Logistic Regression was the best fit with highest accuracy 
score 81.12%


conclusion :
Finally, in our model by using logistic regression model we 
predict whether the loan is approved or not. In order to 
implement this various input variables were used to get the 
output. Whenever program takes the input data it gives the 
output in the form of binary i.e., either0 or 1. If the output is 
1 then ‘1’ will be displayed and it indicates that loan is 
approved. If the output is 0 then ‘0’ will be displayed and it 
indicates that loan is not approved.
Here, we had implemented loan credibility prediction system 
that helps the organizations in making the right decision to 
approve or reject the loan request of the customers.
In this model, Logistic Regression algorithm is used for the 
prediction. Incorporation of other techniques that 
outperform the performance of popular data mining models 
has to be implemented and tested for the domain

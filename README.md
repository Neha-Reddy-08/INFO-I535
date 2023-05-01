# INFO-I535

Introduction 

Replacing an employee can be a major expense for companies and may cost them more than $100,000. As a result, most companies aim to retain their employees, but they often struggle to identify the factors that influence employee retention. Machine learning can be utilized to address this issue. 

This project's objective is to analyze the employee database of a company using machine learning algorithms to identify which factors impact employee retention. The project will focus on querying the employee database, which is stored in MongoDB, and conducting data exploration to determine the primary features that lead employees to leave the company. 

Furthermore, this project could help companies to predict which employees are most likely to leave in the future, allowing them to take appropriate measures to retain them. By doing so, companies can reduce the cost of replacing employees and create a more stable work environment. Additionally, identifying the factors that influence employee retention can assist companies in creating effective retention strategies that cater to their employees' needs and preferences. 



Dataset Description: 

The data set I used for this project is a Human Resources dataset that contains information of various employes of a company. The data was collected and made available in data.world platform. This data set contains 14,999 rows and 10 different columns.  

Sattisfaction_level: lies in the range of 0 to 1. indicates how satisfied an employee is with his current job. 

Number_project: Number of projects the employee has worked on. 

Average_monthly_hours: average number of hours an employee is working in a month. 

Time_spend_company: Number of years the employee has been working in the company. 

Work_accident: number of work accidents if any  

Promotion_last_5years: if an employee has been promoted in the last 5 years. 1 indicates yes and 0 indicates no. 

Departments: the department to which an employee belongs. 

Salary: if the salary of an employee is ‘low’, high’ or ‘medium’ 

Left: 1 if the employee is willing to leave, 0 otherwise 

Here, ‘left’ is a target variable while all others are feature variables. With the help of the feature variables, we can determine the willingness of an employee to leave the company. 


Data Exploration: 

Data exploration is the process of examining and analyzing a dataset to gain a better understanding of its structure, patterns, and relationships between variables. It involves summarizing and visualizing the data, identifying any trends or outliers, and uncovering any potential issues or biases that may affect the quality of the data. 

I have used tools like seaborn, matplot  and techniques like histogram, barplot, scatterplot, distplot and correlation matrix to gain insights into the data. The plots are explained in the next section. 



Predictive Modelling: 

Predictive modeling is the process of using statistical algorithms and machine learning techniques to analyze data and make predictions about future events or outcomes. Here, in this project, I am trying to predict if an employee is willing to leave the company or happy with his job using Machine Learning algorithms like Logistic Regression, Decision Trees and Random Forest. 

First, I have separated the feature variables and target variable(‘left’) and then divided the data into train and test sets using train_test_split method in scikit learn library.
Then, I fit each of the model to the training data and predicted the output using testing data. I have calculated accuracy and confusion matrix for each algorithm. The results are discussed in the next section. 

 

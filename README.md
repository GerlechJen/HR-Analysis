# HR Analysis

This is an end to end business analysis project that focused on Tableau for visualization. It focuseed on business understanding, what insights can be derived from the data ,I began by loading the data into MySQL database .The BI tool tableau was used to extract data from MySQL database for insightful visualizations

## Project Description 
Every company needs an HR Department. This department plays a key role in developing , reinforcing and changing the culture of an organisation.HR covers essential elements of business such as pay, performance management, training and development, recruiting and onboarding. In thsi project we have access to a huge database from which we are going to extract insights that will be benficial to teh HR company. The department will be able to gain knowledge about the recruitment process of the market. The purpose of the project is to extract many different insights from the data. 


## The Data 
The data contains details about jobs for the analytics industry. The data consists of various job descriptions for various analytical roles like Data Scientist, Data Analyst, Business Intelligence, Machine Learning Engineer, Data Engineer, . The dataset had columns like:
**Job Title:** It contains the name of the jobs given by a particular company.

**Company:** It contains the name of the companies that are providing different job ypes.

**Salary:** It contains the salary for different job roles. This column has many null values as many companies do not revel their salary publicly. 

**Job description:** This column contains the detailed description of the job given by particular companies.

**Career Level:** This column contains various career levels like entry level, middle level, senior level, etc which depend on years of experience.

**Qualification:** It contains various educational qualification an individual needs for a job. For example degree, postgraduate, etc. 

**Years of Experience:** It contains the minimum eligibility in terms of years of experience for various job roles.

**Job Type:** It contains the types of jobs required. For example full time, part time, internship, contract, etc.

**Company Website:** There are various website links here where an individual can apply. 

**Industry:** It is the domain to which  particulra job role belongs. For example Finanacial Services, Information Technology, etc.

**Date Posted:**: It shows the data when a particular job was posted. 

**Search Term:** It shows different analytic domains jobs posted belong to. For example Data Science, BI, ML, etc. 



## Insights 
Some business questions I am hoping to answer from this dataset include:

What are the total number of jobs available?

What are the total number of companies providing jobs?

What are the total number of jobs available for various domains?

What are the various career levels and its distributuion across various jobs?

What are the distributuion of jobs across various analytics fields?

Which company is providing highest number of jobs?

Which domain has the highest number of jobs?

What are the minimum required qualifications for job roles?

What are various job types for different job titles?

Which are top 5 companies with highest jobs?

  
## EDA and Cleaning of Data 
Removing Unnecessary Columns 
The data cleaning step included getting rid of columns like lower salary range, upper salary range, data source which were of no use to our analysis.

Removing Null Values and Errors
I also removed NULL values, Not Specified values, errors, missing values, as they can cause errors while changing data types or performing certain calculations. 

Changing Data Types 
I also changed the data type of the Years of Experience column from string to whole integer. The data type of the date column weas also a string and I changed that to date type. 

Replacing Values 
The experience column had a value of -1 and I changed it to 1 using replace value option. The Qualification columns had two qualification names being  'Non-Degree Tertiary' and 'Non Degree Tertiary'. So I replaced the Non Degree Tertiary with Non-Degree Tertiaryas they represent the same qualification. 

## Visual Analytics 


## Key Findings 

## Dashboard View 

# HR Analytics Project

HR analytics is revolutionizing the way human resources departments operate, leading to higher efficiency and better results overall. Although HR departments have been using analytics for years, the collection, processing, and analysis of data have predominantly been manual. Given the nature of human resources dynamics and HR key performance indicators (KPIs), this manual approach has constrained HR operations.

It is surprising that HR departments have only recently recognized the utility of machine learning in this domain. This project provides an opportunity to explore predictive analytics in the HR field.

## Problem Statement
BusyQA, a training institute specializing in analytics and data science, aims to expand its business to manpower recruitment in the data science domain. The company receives a large number of signups for its training programs and wants to connect these enrolees with clients looking to hire employees in the analytics field. Before making these connections, it is crucial to identify which candidates are genuinely seeking new employment opportunities. BusyQA possesses student information related to demographics, education, experience, and training features.

The goal of this project is to design a model that utilizes the current credentials, demographics, and experience of enrolees to predict the probability of an enrolee seeking a new job.

## Data
The provided data includes a data dictionary to aid in understanding the data structure. The following instructions apply to the data:

- Use the train data to build a dashboard and present insights.
- Use the test data only for testing the accuracy of your model.
## Questions to Address
During the analysis, we will explore the following questions to gain valuable insights:

1. Are there any prominent cities where enrolees are more inclined to look for a new job?
2. Do enrolees with lower years of experience tend to seek new job opportunities?
3. Do enrolees looking for a new job spend a significant amount of time in training?
4. Do enrolees looking for new jobs frequently change their employment or spend considerable time in their last job?
5. Are employees from the private sector more inclined towards finding new jobs?
6. Are males more inclined to seek new job opportunities compared to females?
7. Are enrolees from non-STEM backgrounds more likely to look for a new job?
8. Are there any other specific insights that can help us understand the drivers for job change?
## Task 1: Data Analysis and Visualization
To address the problem statement and answer the questions mentioned above, we will follow these steps:

1. Import the train data into an SQL database and establish a connection to Python.
2. Use Python's pandas package and basic Python for data wrangling, cleaning, and manipulation, including:
  - Checking for duplicates in the data.
  - Applying outlier treatment techniques.
  - Handling missing values appropriately.
  - Conducting univariate and bivariate analysis to gain insights.
  - Creating a correlation matrix to identify relationships between variables.
3. Utilize Python packages to provide answers to the questions and plot charts for univariate and bivariate analysis using the Matplotlib/Seaborn package.
## Task 2: Dashboard Creation with Power BI/Tableau
Using Power BI or Tableau, clean and prepare the Excel file generated from Task 1. Create a two-page report/dashboard that showcases the HR analysis. Ensure the dashboard effectively communicates the insights derived from the data.
## Task 3: Predictive Modeling with Machine Leaning models
•	Employed Decision Tree algorithms to build a machine learning model with 90% accuracy, enabling accurate prediction of the number of future candidates who will be seeking new job opportunities after enrolling in the BusyQA Data Analyst Course.
•	Collaborated with a team of professionals to gather, analyze, and interpret data related to candidate enrollment and job search trends, contributing to evidence-based decision-making and strategic planning.
•	Presented findings and recommendations based on comprehensive data analysis, highlighting the potential impact of the BusyQA Data Analyst Course on candidates' career trajectories, aiding in the development of targeted strategies to enhance job placement opportunities by 30% for enrolled candidates.


Please refer to the provided data dictionary and make sure to document your code, analysis, and insights effectively. Keep in mind the goal of predicting the probability of enrolees looking for new job opportunities.

### Additional Notes
- Make sure the necessary packages and libraries are installed before running the code.
- Document your code and analysis effectively.
- Maintain a logical and organized structure within your codebase.
- Use appropriate visualization techniques to present insights clearly.
- Keep in mind the goal of predicting the probability of enrolees looking for new job opportunities.

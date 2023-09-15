# Capstone-project-Providing-data-driven-suggestions-for-HR
This capstone project is part of **Google Advanced Data Analytics Professional Certificate** course on Coursera. In this project, we use **PACE** model for data analysis taught in the course. **PACE** means **Plan, Analyse, Construct**, and **Execute**.

Here are brief description about each stage:

**1. Plan:** In this stage, you conceptualize the scope of the project and develop the steps that will guide you through the process of completing a project.

Here are a few examples of the types of planning stage tasks:
* Research business data
* Define the project scope
* Develop a workflow
* Assess project and/or stakeholder needs

**2. Analyse:** In this stage, you will collect, prepare, and analyze all of the data for your project.

Here are a few examples of the types of analyzing stage tasks:
* Format database
* Scrub data
* Convert data into usable formats

**3. Construct:** In the construction stage you will build models that will allow you access to hidden relationships locked within data.

Here are a few examples of the types of construction stage tasks:
* Select modeling approach
* Build models
* Build machine learning algorithms

**4. Execute:** In the execution stage you will present the finding of your analysis, receive feedback, and make revisions as necessary.

Here are a few examples of execution stage tasks:
* Share results
* Present findings to other stakeholders
* Address feedback

Now lets do all steps for above project.

### Understand the business scenario and problem

The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They refer to you as a data analytics professional and ask you to provide data-driven suggestions based on your understanding of the data. They have the following question: what’s likely to make the employee leave the company?

Your goals in this project are to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.

If you can predict employees likely to quit, it might be possible to identify factors that contribute to their leaving. Because it is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.

### Familiarize yourself with the HR dataset

The [dataset](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv) contains 15,000 rows and 10 columns for the variables listed below.

Variable  |Description |
-----|-----|
satisfaction_level|Employee-reported job satisfaction level [0&ndash;1]|
last_evaluation|Score of employee's last performance review [0&ndash;1]|
number_project|Number of projects employee contributes to|
average_monthly_hours|Average number of hours employee worked per month|
time_spend_company|How long the employee has been with the company (years)
Work_accident|Whether or not the employee experienced an accident while at work
left|Whether or not the employee left the company
promotion_last_5years|Whether or not the employee was promoted in the last 5 years
Department|The employee's department
salary|The employee's salary (U.S. dollars)

### Modeling and Evaluation
We use logistic regression, decission tree and rendom forest model. We get 82% accuracy and 79% precision for logistic regression model. Below image is the confusion matix for logistic regression model.

![Confusion Matrix for logistic regression model](https://github.com/rajmanish31/Capstone-project-Providing-data-driven-suggestions-for-HR/assets/61666590/bd47b746-600d-4c18-a811-f18ba553c413)

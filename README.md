# machine_learning

## 1. Open University Learning Analytics (OULAD) dataset

In this project, we will perform 4 analytical tasks to help the office of innovative learning (OIL) at the University of Michigan to provide advisory intervention to students who are at risk of dropping the course or not likely to succeed.  

1. Conduct Exploratory Data Analysis: 
Examine variation in student engagement and performance across Open University courses.
How is the passing, dropout rate and average number of clicks students log per week in each course? 

2. Build Prediction Model of Student Success: 
Identify which students are likely to fail or succeed by day 100. 
Use demographics, engagement and assessment to build predictive model. 
Think, how data accurately captures student's knowledge, skills and abilities?

3. Investigate Biases of Prediction Models: 
Identify biases and shortcomings of prediction model. 
Is a model with mean AUC-ROC score > 89%, also fair? 
To answer above question, I have used Absolute Between ROC Area (ABROCA) to quantify fairness in predictive models. 

4. Build a Dashboard: 
Communicate data product to specific audience, so that it helps non-technically skilled instructor understand who is likely to succeed (or not) on day 100 of their course. Identify, which metrics will be useful in assessing dashboard’s use and impact? 


Data Source: 

Kuzilek, J., Hlosta, M., & Zdrahal, Z. (2017).
Open university learning analytics dataset. Scientific data, 4, 170171.
https://www.nature.com/articles/sdata2017171

## 2. Boston Housing dataset: 

In this case, we will quantify uncertainty in the linear model by bootstrapping a model predictor 5000 times to build a sampling distribution. Did we spot standard error in the mean of the sampling distribution? Yes, it's critical to present this model uncertainty to stakeholders prior to deployment.

Data Source: 

[Boston Dataset](http://lib.stat.cmu.edu/datasets/boston)

The two predictors used from the dataset are as under:
1. RM: Average number of rooms per dwelling
2. LSTAT: Average proportion of adults without high school education and the proportion of male workers classified as labourers. 






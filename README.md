# Investigating Income Inequality in United States
## About
This is a SC1015 Introduction to Data Science and Artificial Intelligence mini project which address wage discrimination. 

## Practical Motivation and Problem Definition
Income inequality, which is defined as the extent to which income is distributed in an uneven manner among a population, has been a highly discussed topic in America. This is especially so in relation to rising concerns of Racism, Sexism and Ageism, where certain races, genders and people above a certain age, are said to be unfairly paid less for the same amount of work.

As such, we would like to investigate the state of income inequality and to provide a tool that helps job seekers to determine the fair compensation they should be receiving, in an attempt to alleviate the problem.

## Project Goals
1. Explore the extent of wage discrimination based on age, gender and race in United States.
2. Develop a model that recommends wages based on modifiable factors, such as education, experience, industry and occupation and ignores non-modifiable factors such as age, gender and race. 

## Data Source 


## Models Used
1. Linear Regression
2. Polynomial Regression
3. Bayesian Ridge Regression
4. Decision Tree Regression
5. Random Forest Regression

## Conclusion
- Wage disparity based on Age, Gender and Race does exist in the United States
    - Wages start to decline after 50 years old even as years of experience increases
    - Females earn about 32% less than Males on average and underearn Males at all quartiles
    - White Americans earn about 35% more than Black and Hispanic Americans
- Machine Learning could be used to provide a fair income benchmark based only on modifiable factors but more work needs to be done
    - More data needs to be collected and in the present to accurately reflect the current situation. Including data across a few decades, which have different socio-economic situations, may have introduced bias into the data and reduced data quality. 
    - More complex models, such as nerual networks could be employed to give more accurate predictions. 


## What did we learn from this project?
- Data cleaning and pre-processing 
- Data visualisation with pandas, numpy, seaborn and matplotllib 
- Various regression models with sklearn 

## References
- <https://www.kaggle.com/datasets/fedesoriano/gender-pay-gap-dataset>
- <https://www.epi.org/unequalpower/publications/understanding-black-white-disparities-in-labor-market-outcomes/>
- <https://research.stlouisfed.org/publications/economic-synopses/2017/02/24/aging-and-wealth-inequality/#:~:text=In%20the%20United%20States%2C%20for,42%20percent%20of%20total%20wealth.&text=As%20the%20figure%20shows%2C%20the,16%20percent%20of%20the%20population.>
- <https://www.pewresearch.org/short-reads/2023/03/01/gender-pay-gap-facts/#:~:text=The%20gender%20gap%20in%20pay,%2D%20and%20part%2Dtime%20workers.>
- <https://www.w3schools.com/python/python_ml_polynomial_regression.asp>
- <https://towardsdatascience.com/bayesian-linear-regression-in-python-using-machine-learning-to-predict-student-grades-part-2-b72059a8ac7e>
- <https://medium.com/pursuitnotes/decision-tree-regression-in-6-steps-with-python-1a1c5aa2ee16>
- <https://towardsdatascience.com/random-forest-regression-5f605132d19d>

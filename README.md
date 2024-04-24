# Prodigy_DS_02

This project focuses on conducting data cleaning and exploratory data analysis (EDA) on the Titanic dataset.The Titanic dataset is a well-known dataset that provides insights into the demographics and survival rates of passengers aboard the Titanic

DATA UNDERSTANDING

The datasets is obtained from Kaggle: Titanic

The dataset contains 891 rows (entries) and 12 columns
The columns are:

PassengerId: Unique identifier for each passenger.
Survived: Binary variable indicating survival (1 = Survived, 0 = Did Not Survive).
Pclass: Ticket class (1st, 2nd, 3rd class).
Name: Passenger's name.
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard.
Parch: Number of parents/children aboard.
Ticket: Ticket number.
Fare: Passenger fare.
Cabin: Cabin number.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)



Univariate Exploration:
Univariate analysis involves scrutinizing individual variables within a dataset to understand their characteristics and distributions. In this project, I delved into the Titanic dataset, employing univariate analysis to examine various factors independently. This included constructing histograms to depict the age distribution, bar plots to illustrate passenger class distribution, and a pie chart to visualize survival rates.

Bivariate Exploration:
Moving beyond single variables, bivariate analysis explores relationships between pairs of variables. Throughout this project, I explored connections such as age versus fare through scatter plots, the number of survivors by passenger class via bar plots, and fare comparisons across passenger classes using box plots. Additionally, I utilized a correlation heatmap to visualize the relationship between age and fare.

Multivariate Exploration:
Extending the analysis to encompass multiple variables simultaneously, multivariate exploration offers a holistic view of dataset dynamics. Employing techniques like parallel coordinates plots, I investigated relationships between various factors and survival outcomes, shedding light on nuanced interactions within the Titanic dataset.

Insights and Conclusions:

- The analysis revealed a stark disparity in survival rates, with approximately 59.4% of passengers failing to survive, while 40.6% managed to do so.

- Notably, there were fewer children (aged 5-15 years) and elderly passengers (above 60 years) aboard the Titanic, indicating a skew towards younger adults.

- Passenger class emerged as a significant factor influencing survival rates, with those in Class 1 exhibiting a higher likelihood of survival compared to Class 2 and Class 3 passengers. This underscores the potential influence of socio-economic status on survival outcomes.

- Despite Class 3 accommodating the largest number of passengers, it recorded the lowest survival rate. This suggests a possible hierarchy in rescue efforts, favoring higher-class passengers.

- A positive correlation was observed between fare and survival, indicating that passengers who paid higher fares had better chances of survival.

- While not definitive, there appears to be a slight concentration of younger survivors, implying a potential preference for rescuing younger individuals.
- 

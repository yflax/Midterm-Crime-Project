# Midterm-Project
Mohammed A. and Yael F. repository for collaborating on Midterm-Project


# Process

> Project Intent :  
Implement targeted, data-driven measures to address different crime types when they are likely to occur in Toronto. Crime rates are on the rise and crimes are costly not only financially , but also becasue endanger and harm human lives.

> Plan : 
Find datasets that will provide insight to the nature of the crimes in Toronto in recent years so that predictions can be made to avert offences before they take place. Perfrom data cleaning and EDA so the data is test-ready . FInally , perform various statistical tests in order to find the most robust model to predict crime in Toronto in order to formulate the most data-informed crime-fighting strategy.

> Process:  

* Dataset finding - 'Major Crime Indicators'  from TOronot Police Service Open Data.
Join with 'Toronto Neighbourhood Demographics' from Toronto.ca Open Data.
Clean Data removing Null, redundant values /columns , converting data to correcert types. 

* EDA - Find patterns in data b/w crime type/count and features to inform our choice of statistical model 

* Statistical / Predictive Model -Multiple classification models to determine most robust model that will predict offence . ( MN Regression , Random Forest, Decision Tree, K-Nearest Neighbours) Random FOrest was the most robust model with 61.9% accuracy . Further optimization and backwards fitting would improve it.

* Tableau Visualization and create presentation with Tableau stories

> Challenges / Future Goals:
* As always , the time constraint limits our ability to maximize our results ie. there is alwasy more cleaning that can be done , an even better model to test, additional data to be added . But the other than getting things done - the goal is to learn and that was definitely accomplished ;)

* Too large dataset to loop thrrouhg with google free API to fin zipcodes for each crime location . Had to give that up for now.

* Future goal is to dig even deeper and find more demographic data that is correlated to crime incidence . Perfrom more models - like xgboost for example




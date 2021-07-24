# BQML-Prediction

Objectives

Use BigQuery to access the public NCAA dataset.
Explore the NCAA dataset to gain familiarity with the schema and scope of the data available.
Prepare and transform the existing data into features and labels.
Split the dataset into training and evaluation subsets.
Use BQML to build a model based on the NCAA tournament dataset.
Use your newly created model to predict NCAA tournament winners for your bracket



BigQuery
BigQuery is Google's fully managed, NoOps, low cost analytics database. With BigQuery you can query terabytes and terabytes of data without managing infrastructure or needing a database administrator. BigQuery uses SQL and takes advantage of the pay-as-you-go model. BigQuery allows you to focus on analyzing data to find meaningful insights.

There is a newly available dataset for NCAA basketball games, teams, and players. The game data covers play-by-play and box scores back to 2009, as well as final scores back to 1996. Additional data about wins and losses goes back to the 1894-5 season in some teams' cases.

Machine Learning
Google Cloud offers a spectrum of Machine Learning options for data analysts and data scientists. The most popular are:

Machine Learning APIs: use pretrained APIs like Cloud Vision for common ML tasks.
AutoML: create custom ML models with no coding needed.
BigQuery ML: use your SQL knowledge to build ML models quickly right where your data already lives in BigQuery.
AI Platform: build your own custom ML models and put them in production with Google's infrastructure.
In this lab you will use BigQuery ML to prototype, train, evaluate, and predict the 'winners' and 'losers' between two NCAA basketball tournament teams.
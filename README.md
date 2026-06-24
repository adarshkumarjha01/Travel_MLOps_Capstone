Project Summary
This project uses three travel datasets — flights, hotels, and users — to build machine learning models and a complete MLOps pipeline. The idea is straightforward: given that travel platforms generate enormous amounts of transactional data, there is real value in predicting prices, understanding user demographics, and personalising recommendations.

I worked through three modelling tasks. First, a regression model to predict flight prices using the flights dataset. Second, a classification model to predict user gender from their travel behaviour. Third, a collaborative filtering recommender to suggest hotels. On the engineering side, I built a Flask API, containerised it with Docker, deployed it on Kubernetes, set up an Airflow DAG to automate retraining, added a Jenkins CI/CD pipeline, tracked experiments with MLFlow, and built a Streamlit dashboard.

The datasets cover flights and hotel bookings across Brazilian cities between September 2019 and July 2023, with 1,340 unique users across 5 companies.

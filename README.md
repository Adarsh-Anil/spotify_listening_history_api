# Spotify Data Pipeline

Data pipeline that extracts a user's listening activity from the spotify API using python, postgreSQL, dbt, Metabase, Airflow and docker.

# Objective

To perform a deep analysis of an user's listening history to retrieve information about artists, genres and more. This pipeline calls spotify API every hour to extract data from the listening hours, load the responses to a database, apply transformations and visualize the metrics in a dashboard. Since the dataset is small and there doesn't need to be up and running 24 x 7 this is built using open source tools and hosted locally to avoid any cost.

# Tools and Technologies

* Containerization : [Docker](https://www.docker.com/), [Docker Compose](https://docs.docker.com/compose/)
* Orchestration : [Airflow](https://airflow.apache.org/)
* Database : [PostgreSQL](https://www.postgresql.org/)
* Transformation : [DBT](https://www.getdbt.com/)
* Data Visualization : [Metabase](https://www.metabase.com/)
* Language : [Python](https://www.python.org/)

# Architecture


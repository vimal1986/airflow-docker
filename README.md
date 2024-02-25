## Running apache airflow 2.0 in docker with local executor.
Here are the steps to take to get airflow 2.0 running with docker on your machine. 
1. Clone this repo

2. Create dags, logs and plugins folder inside the project directory
```bash
mkdir ./dags ./logs ./plugins

# Running airflow in docker

1. docker compose up airflow-init

2. docker compose up -d

Open the browser and run below commands

localhost:8080/login

User Name : airflow
Password : airflow


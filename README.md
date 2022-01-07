# Airflow in docker
## clone the repo
cd Airflow/app1
## Run following command
docker-compose up -d
## check if docker is up and running
docker ps

## check the airflow UI
localhost:8080

## shutdown docker-compose
docker-compose down

## docker-compose.yaml can be downloaded from below link aswell
curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.2.3/docker-compose.yaml'

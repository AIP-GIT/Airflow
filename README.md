# Airflow in docker
## clone the repo
cd Airflow/app1
## Run following command
echo -e "AIRFLOW_UID=$(id -u)" > .env

docker-compose up airflow-init

docker-compose up -d
## check if docker is up and running
docker ps

## check the airflow UI
http://localhost:8080

## The flower app for monitoring the environment
http://localhost:5555

## shutdown docker-compose
docker-compose down

## docker-compose.yaml can be downloaded from below link aswell
curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.2.3/docker-compose.yaml'

## convinience script
curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.2.3/airflow.sh'

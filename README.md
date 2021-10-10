# airflow_etl_test
To the test the Airflow working 

# Commands for running the Airflow in Docker:

- download the docker-compose.yaml file


- To intialize the environment:

  docker-compose up airflow-init

- To run Airflow:

  docker-compose up

- To check for the containers runnning:

  docker ps

- Interact with the container:

  docker exec -it container_id bash
  
- To access the webserver:
  
  http://localhost:8080
  
- To stop and delete containers and delete the volumes with database data:
  
  docker-compose down --volumes --rmi all
  
  


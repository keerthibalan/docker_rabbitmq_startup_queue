# docker_rabbitmq_startup_queue
This repository is responsible for building rabbitmq docker with auto queue creation

# Rabbitmq

 RabbitMQ is one of the most popular open-source message brokers. From T-Mobile to Runtastic, RabbitMQ is used worldwide at small startups and large enterprises.

 RabbitMQ is lightweight and easy to deploy on-premises and in the cloud. It supports multiple messaging protocols and streaming. RabbitMQ can be deployed in distributed and federated configurations to meet high-scale, high-availability requirements

 # Create the default queue in the definition.json file

 Refer to the source code

 # Create the dockerfile
 Refer to the source code

 # Create Rabbitmq Image using dockerfile

 docker build -t keerthibalan/rabbitmq:3.8.12 .

 # Create the rabbitmq container
 docker container create -it --name rabbitmq keerthibalan/rabbitmq:3.8.12

 # Rabbitmq container port
 56172, 5672

 # Rabbitmq host port
  56172, 5672

# Create the container and start using the docker compse

docker-compose -f rabbitmq-compose.yaml up

# stop the rabbitmq using docker compose

docker-compose of rabbitmq-compose.yaml down

# Login to rabbitmq admin console 

http://localhost:15672

![Uploading image.png…]()


 
 

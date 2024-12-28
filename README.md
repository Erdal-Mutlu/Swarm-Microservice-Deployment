# Swarm-Microservice-Deployment
Course End Project

Docker Commands
docker swarm init #Start swarm
docker stack deploy -c docker-stack.yml vote_stack #Deploy services
docker service scale vote_stack_worker=5 #Increase the worker image’s replicas

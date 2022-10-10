Demo Docker Swarm Project

1. Install Vagrant on your machine
1. Use git pull to get the source code.
2. go to infrastructure folder.
3. in your terminal write vagrant up to get the infrastructure
4. ssh to swarm-manager.
5. Write docker stack deploy -c docker-compose-swarm. yaml docker-app
6. In your browser open http://192.168.99.101:8080/

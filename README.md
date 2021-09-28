# local-docker-efk
Helps you debug your local docker container logs using EFK

# Docker Compose Up
docker-compose -f "docker-compose.yml" up -d --build

# View Kibana
http://localhost:5601/

# Set up your index
filebeat*

# Docker Compse Down
docker-compose -f 'docker-compose.yml' -p 'local-docker-efk' down 
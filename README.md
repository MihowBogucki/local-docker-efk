# local-docker-efk
Helps you debug your local docker container logs using EFK

# Docker Compose Up
docker-compose -f "docker-compose.yml" up -d --build

# View Kibana
http://localhost:5601/

# Set up your index
## Step 1: Define an index pattern
Index pattern name - filebeat*

## Step 2: Configure settings
Time field - @timestamp

# Docker Compse Down
docker-compose -f 'docker-compose.yml' -p 'local-docker-efk' down 

## Tips
EFK stack can be resource-intensive. Configure your docker resources accordingly to what your machine is capable of.
# debug mode
docker compose up --force-recreate -d --build

# deployment 
sudo docker compose  -f  docker-compose-deploy.yml  up  --force-recreate -d --build
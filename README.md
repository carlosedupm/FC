#Comandos a serem execudados para buildar e executar imagem

#DEV
docker compose -f docker-compose.yaml up --build

#PROD
docker compose -f docker-compose.prod.yaml up --build

# Serviços usados para desenvolvimento

Inicia um conjunto de serviços usados durante o desenvolvimento de software. Tornando desnecessário instalar manualmente cada serviço direto na máquina.

## Executar serviços

```sh
sudo docker swarm init
sudo docker stack up dev-services -c docker-compose.yaml
```

## Outros comandos úteis

```sh
# listar serviços
sudo docker stack services dev-services

# listar containers
sudo docker stack ps dev-services
```

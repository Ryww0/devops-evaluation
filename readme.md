# évaluation devops
## Lancement du container de l'app front
```
cd app
docker compose up --build
```
[voir le Dockerfile du front](https://github.com/Ryww0/devops-evaluation/blob/main/app/Dockerfile)

[voir le docker-composer.yaml du front](https://github.com/Ryww0/devops-evaluation/blob/main/app/docker-compose.yml)

le site est disponible à l'adresse `http://localhost:3000`

## Lancement du container de l'api
`````
cd 'API POKEMEON'
docker compose up --build
`````
[voir le Dockerfile de l'api](https://github.com/Ryww0/devops-evaluation/blob/main/API%20POKEMON/Dockerfile)

[voir le docker-composer.yaml de l'api](https://github.com/Ryww0/devops-evaluation/blob/main/API%20POKEMON/docker-compose.yml)

**ATTENTION: Le service app se lance avant le service db, ce qui provoque une erreur. Il faut relancer le service app depuis docker desktop.**

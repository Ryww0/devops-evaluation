# évaluation devops
## Lancement du container de l'app front
```
cd app
docker compose up --build
```
le site est disponible à l'adresse `http://localhost:3000/`

## Lancement du container de l'api
`````
<br>
cd 'API POKEMEON'
docker compose up --build
</br>
`````
**ATTENTION: Le service app se lance avant le service db, ce qui provoque une erreur. Il faut relancer le service app depuis docker desktop.**

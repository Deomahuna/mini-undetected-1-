# mini-undetected
Test DeployAI : aucune détection automatique possible (pas de
docker-compose.yml/Dockerfile/package.json/requirements.txt/composer.json/
index.html à la racine).
Deux tests possibles depuis /projects/:id/build-config :
1. Mode "Générer à partir d'un langage" (node/python/php/static).
2. Mode "J'ai déjà mon propre Dockerfile" -> chemin "Dockerfile.custom".

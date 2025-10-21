# our base image
FROM postgres:17.2-alpine

# Aller initialiser la bdd avec les données situées dans le dossier init
COPY init/ /docker-entrypoint-initdb.d/ 

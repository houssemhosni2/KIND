FROM nginx:alpine

#Définir le chemin de construction avec une valeur par défaut
ARG BUILD_PATH=dist/DevOps_Project_Front

#Copier les fichiers compilés
COPY ${BUILD_PATH} /usr/share/nginx/html

#Exposer le port 80 pour Nginx
EXPOSE 80
# Utilise l'image officielle MySQL
FROM mysql:8.0

# Variables d’environnement pour initialiser la base
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=cena_db
ENV MYSQL_USER=enigme
ENV MYSQL_PASSWORD=Enigme96@

# Copie ton fichier SQL dans le dossier d'initialisation
COPY db.sql /docker-entrypoint-initdb.d/

# Expose le port MySQL
EXPOSE 3306


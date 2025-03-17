# Utiliser une image légère de Python
FROM python:3.11-slim

# Définir le dossier de travail dans le conteneur
WORKDIR /app

# Copier le script dans l'image Docker
COPY app/server.py .

# Exposer le port 8000
EXPOSE 8000

# Commande pour lancer le serveur
CMD ["python", "server.py"]

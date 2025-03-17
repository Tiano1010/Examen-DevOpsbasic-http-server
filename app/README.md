# Basic Docker Project

Ce projet met en place un serveur HTTP minimaliste avec Python et Docker.

## 📌 Prérequis
- Docker installé : [Télécharger Docker](https://www.docker.com/get-started)
- Docker Compose installé

## 🚀 Lancer l'application

### 1️⃣ Sans Docker Compose
```sh
docker build -t basic-http-server .
docker run -p 8000:8000 basic-http-server
2️⃣ Construire l’image
docker build -t basic-http-server .
3️⃣ Taguer l’image
docker tag basic-http-server monpseudo/basic-http-server:v1.0
docker tag basic-http-server monpseudo/basic-http-server:latest
4️⃣ Pousser l’image sur DockerHub
docker push tiano1010/basic-http-server:v1.0
docker push tiano1010/basic-http-server:latest
5️⃣ Télécharger et exécuter depuis un autre environnement
docker run -p 8000:8000 monpseudo/basic-http-server:v1.0

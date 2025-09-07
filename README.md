## 📂 TP Kafka Streams — Traitement de flux en temps réel

Ce dossier regroupe des mini-projets basés sur Kafka Streams permettant d’illustrer le traitement de données en temps réel à l’aide de Apache Kafka, Spring Boot et Docker.

📌 Contenu

- [`click-counter-app`](./click-counter-app): application simulant des clics utilisateurs envoyés à Kafka, traités via Kafka Streams, puis exposés en temps réel via une API REST.
- [`weatherStreamApp`](./weatherStreamApp): application de traitement de flux de données météorologiques en direct avec Kafka Streams.
- [`docker-compose.yaml`](./docker-compose.yaml): fichier pour lancer un environnement Kafka + Zookeeper nécessaire au fonctionnement des applications.

## ▶️ Mise en route

1. **Démarrer l’environnement Kafka :**:
   ```bash
   docker-compose up -d
   ```

2. **Accéder au projet souhaité** puis exécuter les étapes spécifiques (producteur, processeur de flux et consommateur).

## ⚙️ Pré-requis
- Java 17 ou version supérieure
- Maven
- Docker

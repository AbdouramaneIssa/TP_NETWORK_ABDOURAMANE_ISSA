# TP Réseaux et Volumes Docker - Abdouramane Issa

## 📄 Description

Ce repository contient les fichiers et captures d'écran réalisés pour le **TP Réseaux et Volumes Docker** dans le cadre de ma formation (B2A).  
Le TP est divisé en deux parties :

- **Réseaux Docker** : 10 cas pratiques pour explorer les différents types de réseaux Docker (bridge, host, overlay, etc.).
- **Volumes Docker** : 3 exercices pour apprendre à créer et utiliser des volumes pour persister des données.

Chaque cas/exercice est documenté avec :

- Un fichier `commandes.txt` listant les commandes exécutées.
- Des **captures d’écran** montrant les résultats.
- Des fichiers supplémentaires si nécessaire (`docker-compose.yml` dans CAS7, etc.).

---

## 📁 Structure du Repository

```bash
CAS1               : Création d’un réseau bridge et test de connectivité entre conteneurs.
CAS2               : Création de deux réseaux bridge isolés et test d’isolation.
CAS3               : Connexion d’un conteneur à deux réseaux (frontend et backend).
CAS4               : Utilisation d’un réseau avec résolution DNS personnalisée.
CAS5               : Comparaison des réseaux bridge et host.
CAS6               : Création d’un réseau overlay avec Docker Swarm.
CAS7               : Utilisation de Docker Compose pour gérer des réseaux.
CAS8               : Création d’un réseau avec un sous-réseau personnalisé.
CAS9               : Test de bande passante réseau (simulation avec iperf3).
CAS10              : Nettoyage complet des réseaux Docker.
DOCKER-VOLUME-2.1  : Création d’un volume nommé pour Nginx.
DOCKER-VOLUME-2.2  : Utilisation d’un volume avec MySQL (mot de passe : 1234).
DOCKER-VOLUME-2.3  : Nettoyage des volumes inutilisés.

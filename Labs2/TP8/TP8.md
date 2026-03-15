## TP 8 — Accès distant sécurisé avec SSH

Ce TP porte sur la configuration d’un accès distant sécurisé aux équipements réseau à l’aide du protocole **SSH**.  
L’objectif est de configurer les paramètres de base du routeur et des commutateurs, puis d’activer l’accès SSH afin de permettre l’administration distante des équipements de manière sécurisée.

Le TP permet aussi de comprendre la différence entre **Telnet** et **SSH** : contrairement à Telnet, SSH chiffre les échanges et renforce l’authentification lors de la connexion à un équipement réseau.  
La configuration comprend notamment le nom d’hôte, le nom de domaine, la génération des clés RSA, la création d’un utilisateur local, l’activation de SSH version 2 et la configuration des lignes VTY pour n’autoriser que l’accès SSH.

### Topologie
![Topologie du TP](./capture.png)

**Compétences mobilisées :**
- Administration distante d’équipements réseau
- Configuration de SSH sur routeur et switch Cisco
- Génération de clés RSA
- Configuration des lignes VTY
- Authentification locale
- Sécurisation de l’accès distant
- Différence entre Telnet et SSH
- Tests de connectivité et d’accès distant
## TP 6 — Routage dynamique avec RIPv2

Ce TP porte sur la configuration et la vérification du protocole de routage dynamique **RIPv2** dans une topologie multi-routeurs.  
L’objectif est de configurer RIPv2 sur les routeurs, annoncer les réseaux appropriés, limiter l’envoi inutile de mises à jour grâce à `passive-interface`, puis vérifier la propagation correcte des routes entre les différents sous-réseaux.

Le TP permet également d’étudier le comportement de **RIPv2** comme protocole de routage sans classe, en désactivant la **récapitulation automatique** avec `no auto-summary`, puis en observant l’impact sur les tables de routage et la convergence du réseau.

Enfin, une **route statique par défaut** est configurée et redistribuée via RIP afin de simuler un accès à Internet et de propager une passerelle de dernier recours aux autres routeurs.

### Topologie
![Topologie du TP](./capture.png)

**Compétences mobilisées :**
- Configuration de RIPv2
- Routage dynamique IPv4
- Annonce de réseaux avec `network`
- Utilisation de `passive-interface`
- Désactivation de `auto-summary`
- Lecture et analyse de tables de routage
- Redistribution d’une route statique par défaut
- Vérification de la convergence et de la connectivité réseau
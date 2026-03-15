## TP 5 — Récapitulation de routes statiques

Ce TP porte sur l’optimisation du routage statique dans une topologie multi-routeurs à l’aide de la **récapitulation de routes**.  
Après la configuration du réseau et l’analyse des besoins en routage, l’objectif est de déterminer combien de routes statiques sont nécessaires pour joindre les réseaux distants, puis de réduire ce nombre en calculant une **route récapitulative** unique.

Le TP repose sur une analyse binaire des adresses réseau afin d’identifier les bits communs, calculer le masque de la route récapitulative, déterminer l’adresse réseau résumée, puis remplacer plusieurs routes existantes par une seule route plus générale.

Cette manipulation permet de mieux comprendre l’optimisation des tables de routage et l’intérêt de la synthèse de routes dans une architecture IP. 

### Topologie
![Topologie du TP](capture.png)

**Compétences mobilisées :**
- Routage statique IPv4
- Analyse de tables de routage
- Identification des réseaux directement connectés et distants
- Calcul de route récapitulative
- Récapitulation de routes statiques
- Optimisation de la table de routage
- Interconnexion de réseaux multi-routeurs
- Tests de connectivité réseau (`ping`)
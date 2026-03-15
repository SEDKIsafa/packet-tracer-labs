## TP 7 — Routage dynamique avec OSPFv2

Ce TP porte sur la configuration du protocole de routage dynamique **OSPFv2** dans une topologie multi-routeurs.  
L’objectif est de configurer les paramètres de base des équipements, attribuer les adresses IP aux interfaces et aux hôtes, puis activer OSPF sur chaque routeur afin d’annoncer les réseaux directement rattachés à l’aide de la commande `network` et d’un **wildcard mask**.

Le TP permet également d’observer l’établissement des relations de voisinage entre routeurs OSPF, ainsi que la diffusion automatique des routes au sein de l’aire configurée.

Enfin, plusieurs commandes de vérification et de dépannage sont utilisées pour analyser le fonctionnement du protocole, notamment `show ip protocols`, `show ip ospf neighbor` et `show ip ospf interface`. 

### Topologie
![Topologie du TP](./capture.png)

**Compétences mobilisées :**
- Configuration de OSPFv2
- Routage dynamique IPv4
- Annonce de réseaux avec `network`
- Utilisation de wildcard masks
- Établissement de voisinages OSPF
- Lecture de table de routage
- Vérification avec `show ip protocols`
- Vérification avec `show ip ospf neighbor`
- Vérification avec `show ip ospf interface`
- Tests de connectivité réseau (`ping`)
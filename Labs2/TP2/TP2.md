## TP 2 — NAT statique

Ce TP porte sur la configuration de la traduction d’adresses **NAT statique** dans un réseau interconnecté.  
L’objectif est de mettre en place un mappage fixe entre des adresses IPv4 privées et des adresses IPv4 publiques, afin de permettre la communication entre des machines internes et un réseau externe.

Le TP comprend la création de la topologie, la configuration de base des hôtes et des équipements, l’identification des interfaces **inside** et **outside**, puis la mise en place des règles de traduction à l’aide de la commande `ip nat inside source static`.

La configuration est ensuite vérifiée à l’aide de tests de connectivité et de l’affichage de la table de traduction NAT.

### Topologie
![Topologie du TP](capture.png)

**Compétences mobilisées :**
- Configuration de NAT statique
- Mappage IPv4 privé / public
- Distinction `ip nat inside` / `ip nat outside`
- Configuration de routeurs Cisco
- Interconnexion de réseaux
- Vérification des traductions avec `show ip nat translation`
- Tests de connectivité réseau
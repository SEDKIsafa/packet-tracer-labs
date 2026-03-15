## TP 3 — NAT dynamique

Ce TP porte sur la configuration de la **NAT dynamique** dans un réseau interconnecté comportant plusieurs réseaux privés.  
L’objectif est de permettre à des hôtes internes d’accéder à un réseau externe en utilisant un **pool d’adresses IPv4 publiques**, attribuées dynamiquement selon la disponibilité.

Le TP comprend la configuration de la topologie, la mise en place de plusieurs VLANs côté réseau interne, l’adressage des interfaces des routeurs, puis la définition de **listes de contrôle d’accès (ACL)** pour identifier les plages privées autorisées à être traduites.

Un **pool NAT** est ensuite créé et associé aux réseaux internes afin d’assurer la traduction dynamique des adresses lors des communications vers le réseau externe.

### Topologie
![Topologie du TP](./capture.png)

**Compétences mobilisées :**
- Configuration de NAT dynamique
- Création d’un pool d’adresses publiques
- Utilisation d’ACL pour sélectionner les réseaux à traduire
- Distinction `ip nat inside` / `ip nat outside`
- VLANs et sous-interfaces sur routeur
- Interconnexion de réseaux
- Traduction d’adresses IPv4 privées / publiques
- Tests de connectivité réseau
## TP 9 — Configuration de l’adressage IPv6

Ce TP porte sur la configuration et la vérification de l’adressage **IPv6** dans un réseau simple composé d’un routeur, de deux commutateurs et de deux hôtes.  
L’objectif est d’activer le routage IPv6 sur le routeur, configurer des adresses globales unicast sur les interfaces, définir une adresse **link-local**, puis mettre en œuvre deux modes d’attribution côté client : configuration manuelle et autoconfiguration **SLAAC**.

Le TP introduit également l’utilisation de **EUI-64** pour la génération automatique d’une partie d’adresse IPv6, ainsi que l’analyse des échanges entre un hôte et le routeur lors de l’autoconfiguration.

Enfin, la connectivité est vérifiée à l’aide de tests `ping` vers les adresses globales et link-local.  

### Topologie
![Topologie du TP](./capture.png)

**Compétences mobilisées :**
- Configuration d’adressage IPv6
- Activation de `ipv6 unicast-routing`
- Configuration d’adresses globales et link-local
- Utilisation de EUI-64
- Autoconfiguration IPv6 avec SLAAC
- Vérification avec `show ipv6 interface brief`
- Tests de connectivité IPv6
- Compréhension des échanges d’autoconfiguration
## TP 9 — Configuration d’un agent relais DHCP

Ce TP porte sur la mise en place d’un serveur DHCPv4 situé sur un réseau différent de celui des clients.  
Dans un premier temps, le serveur DHCP est configuré avec un pool d’adresses, puis les clients sont placés en mode d’attribution automatique afin d’observer les limites du broadcast DHCP à travers un routeur.

Le TP introduit ensuite la configuration d’un **agent relais DHCP** sur le routeur à l’aide de la commande `ip helper-address`, afin de transférer les requêtes DHCP vers le serveur distant.

L’objectif est de comprendre pourquoi un client situé sur un autre sous-réseau ne reçoit pas automatiquement sa configuration IP, puis de mettre en place la solution permettant l’attribution correcte des paramètres réseau.

### Topologie
![Topologie du TP 9](./capture.png)

**Compétences mobilisées :**
- Configuration d’un serveur DHCPv4
- Attribution dynamique d’adresses IPv4
- Compréhension du broadcast DHCP
- Segmentation en sous-réseaux
- Configuration d’un agent relais DHCP
- Utilisation de `ip helper-address`
- Routage entre réseaux
- Tests de connectivité réseau
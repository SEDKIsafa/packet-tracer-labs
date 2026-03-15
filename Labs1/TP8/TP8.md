## TP 8 — DHCPv4 dans un réseau segmenté en VLAN

Ce TP porte sur la mise en place d’un service DHCPv4 dans un réseau local segmenté en plusieurs VLANs.  
Le premier scénario permet d’observer le comportement des hôtes lorsqu’ils sont configurés en DHCP sans serveur d’attribution adapté.

Le second scénario met en œuvre un routeur configuré en **router-on-a-stick**, avec des sous-interfaces associées à plusieurs VLANs via l’encapsulation **802.1Q**.  
Des pools DHCP distincts sont ensuite configurés sur le routeur pour chaque VLAN, avec définition de la passerelle par défaut, du serveur DNS, du nom de domaine, de la durée du bail et des adresses exclues.

L’objectif est de permettre aux machines clientes d’obtenir automatiquement une configuration IPv4 correcte selon leur VLAN d’appartenance, puis de vérifier la connectivité entre les équipements.

### Topologie
![Topologie du TP 8](./capture.png)

**Compétences mobilisées :**
- Configuration de pools DHCPv4
- Attribution dynamique d’adresses IP
- Exclusion d’adresses dans un pool DHCP
- Configuration de passerelle par défaut et DNS
- VLANs et segmentation logique
- Trunk 802.1Q
- Sous-interfaces sur routeur Cisco
- Routage inter-VLAN
- Vérification de baux DHCP et tests de connectivité
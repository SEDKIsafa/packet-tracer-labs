## TP 7 — Routage Inter-VLAN

Ce TP porte sur la mise en place du routage inter-VLAN dans un réseau local segmenté.  
L’objectif est de créer plusieurs VLANs sur un commutateur, d’affecter les ports correspondants aux différents réseaux, puis de configurer une liaison trunk 802.1Q entre le switch et le routeur.

Le TP introduit ensuite la configuration de sous-interfaces sur le routeur avec encapsulation `dot1Q`, afin de permettre la communication entre plusieurs VLANs distincts à l’aide d’un routage de niveau 3.

Cette manipulation permet de comprendre le fonctionnement du modèle **router-on-a-stick**, le rôle des passerelles par VLAN et la communication entre réseaux logiques séparés.

![Topologie du TP 7](./capture.png)

**Compétences mobilisées :**
- Création et configuration de VLANs
- Affectation de ports sur commutateur
- Configuration d’un trunk 802.1Q
- Configuration de sous-interfaces sur routeur Cisco
- Encapsulation `dot1Q`
- Routage inter-VLAN
- Passerelles par défaut
- Tests de connectivité réseau (`ping`)
#  Analyse de Trafic Réseau avec Wireshark

**Auteur :** EL BENISSI ADAM
**Type :** Analyse Forensique Réseau / Packet Sniffing  
**Outil :** Wireshark  

---

##  Résumé du Projet
Ce dépôt regroupe une analyse technique détaillée de plusieurs captures réseau effectuées dans divers environnements (loopback, Ethernet et Wi‑Fi). Le travail vise à mettre en évidence la maîtrise des techniques de capture, de décodage et d’interprétation des flux réseau, afin d'identifier les comportements normaux et les éventuelles anomalies.

##  Compétences Démontrées
* **Capture de Paquets :** Maîtrise de l'interface Wireshark et de la sélection d'interfaces.
* **Filtrage Avancé :** Utilisation de filtres d'affichage (ex: `http`, `tls`, `ip.addr`) pour isoler le trafic pertinent.
* **Analyse Protocolaire :**
    * **HTTP/DNS :** Étude du trafic en clair.
    * **TLS :** Observation et décodage du handshake SSL/HTTPS.
    * **ICMP :** Vérification et diagnostic de la connectivité.
* **Statistiques :** Utilisation des outils Wireshark pour visualiser la répartition et le volume du trafic.

##  Contenu du Dépôt
* **`Rapport_Analyse_Wireshark.pdf`** : Rapport complet détaillant l’étude de trois scénarios de capture.
* **`evidence/`** : Captures d’écran illustrant l’interface Wireshark et les flux analysés.

##  Points Clés du Rapport
Le rapport analyse trois types de trafic :
1.  **Loopback :** Trafic local entre processus pour diagnostic.
2.  **Ethernet :** Trafic standard des utilisateurs (Web, DNS, SSH).
3.  **Wi-Fi :** Analyse du trafic sans fil, incluant les trames de gestion et retransmissions.

---
*Projet effectué dans le cadre de mon apprentissage en cybersécurité.*

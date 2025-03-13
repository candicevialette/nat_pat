# 🛡️ Découverte du NAT et PAT

![Banner](image/background.png)

## 📄 Description

Ce dépôt contient les ressources dédiées à la découverte et à la configuration du NAT et du PAT, telles que présentées dans le TP corrigé "Bloc2_sem2-atelier-09_Nat_VIALETTE_Candice_corrige.docx". Vous y trouverez des documents explicatifs, des fichiers de configuration Cisco Packet Tracer, et des guides pratiques pour maîtriser la translation d’adresses IP et la redirection de ports.

L’objectif de ce TP est de comprendre et de mettre en œuvre :
- Le **NAT statique** pour associer une adresse IP privée fixe à une adresse IP publique.
- Le **NAT dynamique** qui attribue temporairement des adresses publiques à partir d’un pool.
- Le **PAT (Port Address Translation)**, permettant à plusieurs hôtes internes de partager une unique adresse IP publique grâce à l’utilisation de numéros de ports.

---

## 📚 Qu'est-ce que le NAT et le PAT ?

**Network Address Translation (NAT)** permet de masquer les adresses IP privées d’un réseau interne en les traduisant en adresses IP publiques, facilitant ainsi la communication avec Internet. Selon les besoins, le NAT se décline en plusieurs formes :

- **NAT statique** : une correspondance fixe entre une adresse IP privée et une adresse IP publique.
- **NAT dynamique** : une attribution temporaire d’adresses IP publiques issues d’un pool défini.
- **PAT (NAT Overload)** : permet à plusieurs dispositifs internes d’accéder à Internet via une seule adresse IP publique en différenciant les connexions grâce aux numéros de ports.

Ces mécanismes sont essentiels pour optimiser l’usage des adresses IP, sécuriser l’accès aux ressources internes et gérer efficacement le trafic entre réseaux privés et publics.

---

## 📂 Structure du Dépôt


```
📂 decouverte-packet-tracer/
|
├── 📂 Documents/
│   └── Bloc1_sem1-atelier_02_VIALET...
|
├── 📂 Réseaux/
│   ├── Bloc1_sem1-atelier_02_Activite...
│   ├── Bloc1_sem1-atelier_02_Activite...
│   └── Bloc1_sem1-atelier_02_Activite...
|
├── 📂 image/
│   └── background.png
|
└── README.md
```

---

## ⚙️ Prérequis

- **Cisco Packet Tracer** installé sur votre machine  
  [Télécharger Cisco Packet Tracer](https://packet-tracer.fr.malavida.com/windows/)
- Connaissances de base en protocoles réseau tels que **ICMP**, **TCP**, **UDP** ainsi que des notions de routage.

---

## 🚀 Mise en Œuvre

### 1. Cloner le Dépôt

```bash
git clone https://github.com/votre_nom_utilisateur/tp-nat-pat.git
cd tp-nat-pat
```
### 2. **Parcourir la Documentation**

Consultez le dossier `documentation/` pour des guides d'analyse détaillés.

### 3. **Ouvrir les Captures de Paquets**

1. Lancez **Cisco Packet Tracer**.
2. Importez les fichiers `.pka` et '.pkt' disponibles dans le dossier `Réseaux/`.
3. Utilisez les différents scénarios pour configurer et analyser les réseaux.

---
## 👉 **Fonctionnalités Clés de Cisco Packet Tracer**
- **Création de réseaux virtuels** : Construisez des topologies réseau complètes avec des routeurs, commutateurs et autres équipements Cisco.
- **Simulation de protocoles réseau** : Expérimentez avec des protocoles comme **ICMP**, **TCP**, **UDP**, **HTTP**, **FTP**.
- **Outils de diagnostic** : Utilisez les commandes `ping`, `traceroute` et d'autres outils pour dépanner les réseaux.
- **Configuration des services** : Apprenez à configurer **DHCP**, **DNS**, **NAT**, et d'autres services essentiels.
- **Prise en charge des réseaux sans fil** : Simulez des réseaux Wi-Fi avec des points d'accès et des appareils mobiles.
- **Simulation d'IoT** : Intégrez et configurez des appareils connectés pour des scénarios de maison intelligente.

---

## 💡 **Bonnes Pratiques**

- **Sauvegardez régulièrement vos configurations** pour éviter toute perte de données.
- **Utilisez Utilisez des annotations** pour documenter vos topologies réseau.
- **Testez différents scénarios** pour comprendre le comportement des protocoles.
- **Expérimentez avec des erreurs de configuration** pour améliorer vos compétences en dépannage.

---

## 📚 **Ressources Utiles**

- [Cours sur le NAT]([https://www.netacad.com/courses/packet-tracer](https://www.it-connect.fr/chapitres/nat-translation-dadresse/))
- [Cours sur le NAT/PAT]([https://www.netacad.com/](https://www.it-connect.fr/le-nat-et-le-pat-pour-les-debutants/))
- [Documentation Packet Tracer](https://www.netacad.com/portal/resources/packet-tracer)

---

## 🌍 **Licence**

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus d'informations.

---

### 🗓 **Date de Création**
Janvier 2025

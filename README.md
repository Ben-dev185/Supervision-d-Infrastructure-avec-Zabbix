#  Supervision d'Infrastructure avec Zabbix

##  Présentation

Ce projet consiste à déployer et configurer une solution complète de supervision avec Zabbix afin de surveiller en temps réel une infrastructure composée de plusieurs serveurs Linux virtualisés sous VMware.

L'objectif est de détecter rapidement les incidents, superviser les performances système et recevoir des alertes automatiques en cas d'anomalie.

Ce laboratoire reproduit les besoins réels d'une équipe d'exploitation informatique chargée d'assurer la disponibilité et la continuité des services.

---

##  Objectifs du projet

* Déployer un serveur Zabbix
* Superviser plusieurs serveurs Linux
* Installer et configurer les agents Zabbix
* Mettre en place des alertes automatiques
* Créer des tableaux de bord de supervision
* Surveiller les ressources critiques des serveurs

---

##  Technologies utilisées

| Domaine         | Technologies       |
| --------------- | ------------------ |
| Supervision     | Zabbix 6.x         |
| Virtualisation  | VMware Workstation |
| Système         | Ubuntu Server      |
| Base de données | MySQL              |
| Serveur Web     | Apache             |
| Langage         | PHP                |
| Réseau          | TCP/IP             |

---

##  Architecture du projet


![Architecture](https://github.com/Ben-dev185/Supervision-d-Infrastructure-avec-Zabbix/blob/e812d02c0eb705d03fee62b8aa3d358a5e7f1205/Architecture.png)
   
                   


---

##  Réalisations

### 1. Déploiement du serveur Zabbix

* Installation de Zabbix Server
* Configuration de MySQL
* Installation d'Apache et PHP
* Configuration de l'interface Web

### 2. Déploiement des agents

* Installation des agents Zabbix sur plusieurs serveurs Linux
* Configuration de la communication entre les agents et le serveur
* Vérification de la remontée des métriques

### 3. Supervision système

Surveillance en temps réel de :

* Utilisation CPU
* Consommation mémoire RAM
* Espace disque
* Activité réseau
* Disponibilité des services
* Disponibilité des hôtes

### 4. Mise en place des alertes

Configuration de triggers :

* WARNING
* AVERAGE
* HIGH

Notifications automatiques envoyées par email en cas d'incident ou de dépassement de seuil.

### 5. Création de dashboards

* Graphiques temps réel
* Visualisation de l'état des serveurs
* Historique des événements
* Cartographie de l'infrastructure

---

##  Captures d'écran

### Ajout et supervision des hôtes

![Hôtes supervisés](https://github.com/Ben-dev185/Supervision-d-Infrastructure-avec-Zabbix/blob/bd935440cb486f0a3eb2bdc6b15186e99c0ed5d9/configuration%20et%20supervision%20des%20hotes.png)

### Gestion des événements et alertes

![Événements](https://github.com/Ben-dev185/Supervision-d-Infrastructure-avec-Zabbix/blob/97e66d7662c9c53fa83dec51f6d57aa717178698/gestion.png)

### Détection automatique d'une panne d'agent

![Agent Down](https://github.com/Ben-dev185/Supervision-d-Infrastructure-avec-Zabbix/blob/46a9b028d80859cb7c716cee20bd476b26252346/Detection%20d'alerte.png)

---

## 🔍 Métriques surveillées

* Charge processeur
* Utilisation mémoire
* Espace disque disponible
* Interfaces réseau
* Temps de disponibilité
* Processus système
* Disponibilité des agents

---

##  Exemple d'incident détecté

Lors des tests, l'arrêt volontaire d'un agent Zabbix a permis de vérifier le bon fonctionnement du système d'alerte.

Après plusieurs minutes sans réponse, Zabbix a automatiquement détecté l'indisponibilité du serveur supervisé et généré une alerte de niveau moyen visible depuis le tableau de bord.

---

##  Compétences développées

* Supervision d'infrastructure
* Zabbix Server
* Zabbix Agents
* Monitoring Linux
* Gestion des alertes
* Analyse de performances
* VMware
* MySQL
* Apache
* Administration Linux

---

##  Valeur ajoutée en entreprise

* Réduction du temps de détection des incidents
* Surveillance proactive des serveurs
* Visibilité en temps réel sur l'état du SI
* Centralisation des informations de supervision
* Amélioration de la disponibilité des services

---

##  Résultats obtenus

* Déploiement complet d'une plateforme de supervision
* Surveillance opérationnelle de plusieurs serveurs Linux
* Alertes automatiques fonctionnelles
* Tableaux de bord temps réel
* Détection rapide des anomalies système

---


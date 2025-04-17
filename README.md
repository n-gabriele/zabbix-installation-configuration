# 📡 Supervision avec Zabbix & Grafana – Projet d’Atelier Professionnel  
🎓 Réalisé par : Nathan Gabriele | BTS SIO SISR

---

## 🚀 Objectif du projet

Ce projet a pour but de **mettre en place une infrastructure de supervision complète**, basée sur **Zabbix** pour la surveillance en temps réel, et **Grafana** pour la visualisation avancée.

🧠 L'idée ? Offrir une **supervision proactive**, visuelle et centralisée des services, machines, réseaux et performances, tout en appliquant des **bonnes pratiques professionnelles** en termes de sécurité, de scalabilité et d'automatisation.

---

## 💡 Pourquoi ce projet est utile

> 💥 Un service qui tombe en panne sans qu’on le sache = des utilisateurs mécontents, des données perdues, de la crédibilité en moins.

Avec ce projet :
- Tu **détectes les incidents avant les utilisateurs**.
- Tu **visualises les métriques clés en un coup d'œil**.
- Tu **automatises la remontée d’alertes** (mails, Discord, etc.).
- Tu mets en œuvre une **architecture fiable et réaliste** digne d’un environnement pro.

---

## 🛠️ Outils utilisés

| Outil       | Rôle dans le projet                                      |
|-------------|----------------------------------------------------------|
| **Zabbix**  | Supervision (collecte, analyse, alertes, interface web)  |
| **Grafana** | Visualisation des données de supervision                 |
| **Ubuntu Server 22.04 LTS** | OS du serveur Zabbix                        |
| **Apache2, MySQL** | Support du frontend Zabbix & base de données         |
| **Agents Zabbix** | Installés sur Linux & Windows pour la collecte      |
| **Discord Webhook** | Notifications en temps réel aux équipes             |

---

## 🧱 Déploiement étape par étape

### ⚙️ Création de l’environnement
- 📦 VM Ubuntu Server configurée en réseau isolé avec IP statique
- 🔐 Configuration SSH pour l’administration distante
- 🔄 Provisionnement dynamique, disque 100 Go, RAM 8 Go

### 🔧 Installation de Zabbix
- 📥 Dépôts officiels Zabbix 7.0 LTS
- 💾 Installation MySQL pour la base de données
- 🌐 Interface web via Apache + PHP
- 🧪 Setup vérifié via `http://ip/zabbix/setup.php`

### 🧪 Ajout des hôtes & règles de découverte
- 🖥️ Agents Zabbix installés sur Windows & Linux
- 🧭 Règles de scan (DMZ, LAN), templates adaptés
- 🏷️ Groupes d’hôtes créés pour séparer serveurs/clients

---

## 📊 Tableaux de bord : Zabbix & Grafana

### 🧭 Zabbix
- Création de widgets personnalisés : CPU, RAM, E/S disque, problèmes en cours
- Cartes géographiques interactives (coordonnées GPS)
- Suivi en temps réel de l’état des hôtes

### 🎨 Grafana
- Connexion aux données Zabbix via plugin officiel
- Dashboards clairs, graphiques temps réel
- Interface plus flexible pour une **analyse avancée**

---

## 🔔 Alertes & Sécurité

### 📧 Email
- Configuration SMTP (Gmail)
- Filtres par niveau de gravité
- Envoi automatisé dès qu’un problème est détecté

### 💬 Discord
- Intégration Webhook
- Notifications instantanées dans un salon dédié

### 🔒 Certificat SSL
- Activation HTTPS sur Apache (mkcert)
- Sécurisation des connexions à l’interface web

---

## 🛡️ Administration & Accès

- Création d’utilisateurs Zabbix (Admin, Guest…)
- Intégration LDAP pour une gestion centralisée
- Permissions par rôle & groupes, politiques d'accès personnalisées

---

## 📚 Ce que j’ai appris

- 🔍 Installer et configurer **une solution de supervision complète**
- 📈 Créer des tableaux de bord utiles et lisibles
- 🔄 Automatiser les alertes et la découverte des équipements
- 🔐 Sécuriser un service critique en production
- 🧩 Intégrer plusieurs outils dans un workflow professionnel cohérent

---

## 🧠 Pour aller plus loin

Tu veux voir à quoi ça ressemble ?
- 🔹 Interface Zabbix en action : http://zabbix.DOMAD107.peda
- 🔹 Dashboards dynamiques Grafana
- 🔹 Intégration des alertes dans Discord 🚨

👉 Ce projet peut facilement être **déployé en entreprise**, dans un lycée, ou chez toi en local pour apprendre les bases de la supervision.

---

## 📬 Me contacter

- 📧 Mail : nathanhyperespace@gmail.com
- 💼 LinkedIn / Portfolio : [à compléter si tu veux]

---

## 📝 Licence & Références

- Basé sur les outils open source Zabbix & Grafana
- Webographie incluse dans le rapport original

---


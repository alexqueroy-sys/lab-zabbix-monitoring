# 📊 Lab Zabbix — Monitoring Réseau

## 📋 Description
Déploiement de Zabbix 6.4 sur Ubuntu Server 24.04 sous VirtualBox,
simulant un outil de supervision réseau utilisé en entreprise.

## 🏗️ Architecture
| Machine | OS | Rôle | IP |
|---|---|---|---|
| UBUNTU-SRV | Ubuntu Server 24.04 | Zabbix Server + Agent | 192.168.10.1 |

## ✅ Ce qui a été configuré
- Installation Zabbix Server, Frontend et Agent
- Configuration base de données MySQL pour Zabbix
- Import du schéma SQL Zabbix
- Configuration de l'interface web Zabbix
- Dashboard de monitoring avec métriques en temps réel
- Supervision CPU, mémoire et disponibilité des hôtes

## 🛠️ Technologies utilisées
- Ubuntu Server 24.04 LTS
- Zabbix 6.4
- MySQL 8.0
- Apache2
- PHP 8.3
- VirtualBox 7.x

## 📸 Screenshots

### 1. Installation Zabbix
![Install](1.INSTALLATION%20ZABBIX%20FRONTEND.PNG)

### 2. Création base de données MySQL
![SQL](2.CREATION%20BASE%20DE%20DONNEES%20MYSQL.PNG)

### 3. Configuration Zabbix Server
![Config](3.CONFIGURATION%20ZABBIX%20SERVER.PNG)

### 4. Zabbix Server actif
![Actif](4.ZABBIX%20SERVER%20RUNNING.PNG)

### 5. Interface web Zabbix
![Web](5.INTERFACE%20WEB%20ZABBIX.PNG)

### 6. Dashboard Zabbix
![Dashboard](6.DASHBOARD%20ZABBIX.PNG)

## 📚 Ce que j'ai appris
- Déployer un outil de supervision réseau professionnel
- Configurer une base de données pour une application
- Surveiller les performances d'un serveur en temps réel
- Interpréter les métriques et alertes du dashboard

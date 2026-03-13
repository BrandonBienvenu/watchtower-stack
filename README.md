📊 Watchtower Stack — Grafana + Prometheus + Node Exporter
![Status](https://img.shields.io/badge/statut-terminé-brightgreen)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu%20Server-E95420?logo=ubuntu)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?logo=virtualbox)
> Stack de monitoring complète pour surveiller des serveurs Linux en temps réel — métriques CPU, RAM, disque et réseau via des dashboards Grafana interactifs.
>
> 🌐 **Ce projet est présenté sur [brandonbienvenu.fr](https://brandonbienvenu.fr)**
---
📋 Sommaire
Aperçu
Dashboard
Stack technique
Installation rapide
Documentation complète
Ce que j'ai appris
---
Aperçu
Ce projet déploie une stack de monitoring complète sur Ubuntu Server dans VirtualBox. L'objectif est d'avoir une visibilité totale sur l'état et les performances d'un serveur en temps réel.
Ce qui a été mis en place :
Prometheus — collecte et stockage des métriques toutes les 15 secondes
Node Exporter — expose les métriques système (CPU, RAM, disque, réseau)
Grafana — dashboards interactifs avec visualisation en temps réel et alertes
---
Dashboard
<img width="100%" alt="Grafana Dashboard" src="https://github.com/user-attachments/assets/b724f1a0-f7e3-4451-97ee-ecb91ef57c8b" />
---
Stack technique
Outil	Rôle	Port
Prometheus	Collecte & stockage métriques	9090
Node Exporter	Exposition métriques système	9100
Grafana	Visualisation & dashboards	3000
Ubuntu Server	OS hôte	—
VirtualBox	Virtualisation	—
---
Installation rapide
```bash
# Installer Node Exporter
sudo apt install prometheus-node-exporter

# Installer Prometheus
sudo apt install prometheus

# Installer Grafana
sudo apt install grafana

# Lancer les services
sudo systemctl start prometheus
sudo systemctl start grafana-server
sudo systemctl start prometheus-node-exporter

# Activer au démarrage
sudo systemctl enable prometheus
sudo systemctl enable grafana-server
sudo systemctl enable prometheus-node-exporter
```
---
Documentation complète
📄 La documentation technique complète du projet est disponible ici — installation pas à pas, configuration Prometheus, création des dashboards Grafana et résolution des problèmes rencontrés.
📥 Accéder à la documentation complète
---
Ce que j'ai appris
Déploiement d'une stack de monitoring sur Linux
Configuration de Prometheus pour scrapper des métriques
Création et personnalisation de dashboards Grafana
Gestion des services systemd
Surveillance des performances système en temps réel
---
Compétences démontrées
`Grafana` `Prometheus` `Node Exporter` `Ubuntu Server` `Linux` `Monitoring` `systemd` `VirtualBox` `Infrastructure IT`
---
> 💡 *Projet réalisé dans le cadre de mon homelab personnel.*
>
> 🌐 *Présenté sur [brandonbienvenu.fr](https://brandonbienvenu.fr) — Brandon Bienvenu, BAC PRO CIEL, Reims*

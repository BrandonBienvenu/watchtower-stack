# 🚀 Grafana + Prometheus + Node Exporter Monitoring

![Monitoring](https://img.shields.io/badge/Status-Production-green)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu-blue)
![Skills](https://img.shields.io/badge/Skills-SysAdmin%20%7C%20DevOps-yellow)

---

## 🔍 Project Overview
Une **stack de monitoring complète** pour surveiller vos serveurs Linux en temps réel :

- 📊 **Grafana** : dashboards interactifs et prêts à l’emploi  
- ⚡ **Prometheus** : collecte et stockage des métriques  
- 🖥️ **Node Exporter** : performance CPU, RAM, disque, réseau
- **Accédez au projet ici :** [GitHub Repo](https://github.com/BrandonBienvenu/-Grafana-Prometheus-and-Node-Exporter-)

**Objectif :** Avoir une visibilité totale sur l’état et les performances d’un serveur.

---

## 🎨 Highlights
- Dashboards Grafana modernes et clairs  
- Surveillance multi-serveur via Node Exporter  
- Alertes simples configurables  
- Facile à déployer sur Ubuntu Server




 # ![Grafana Dashboard] 
 <img width="3360" height="1878" alt="grafana-dashboard-english" src="https://github.com/user-attachments/assets/b724f1a0-f7e3-4451-97ee-ecb91ef57c8b" />

---

## 🛠️ Installation rapide

```bash
# Installer Node Exporter
sudo apt install prometheus-node-exporter

# Installer Prometheus
sudo apt install prometheus

# Configurer Prometheus pour scrapper Node Exporter
# Installer Grafana
sudo apt install grafana

# Lancer les services
sudo systemctl start prometheus
sudo systemctl start grafana-server
sudo systemctl start prometheus-node-exporter

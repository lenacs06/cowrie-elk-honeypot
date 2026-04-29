🇺🇸 English
#  Cowrie Honeypot + ELK Stack

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch)
![Kibana](https://img.shields.io/badge/Kibana-FF6F00?style=for-the-badge&logo=kibana&logoColor=white)
![Filebeat](https://img.shields.io/badge/Filebeat-00BFB3?style=for-the-badge)
![Cowrie](https://img.shields.io/badge/Cowrie-Honeypot-red?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Security](https://img.shields.io/badge/Focus-Cybersecurity-blue?style=for-the-badge)

---

## 📚 Overview

This project simulates a vulnerable SSH server using **Cowrie Honeypot**, capturing real-world attack attempts and analyzing attacker behavior through the **ELK Stack**.

> 🔍 Objective: Monitor, analyze, and visualize attacks in near real-time.

---

## ⚙️ Architecture

```text
[ Attacker ]
     ↓
Cowrie Honeypot (SSH)
     ↓
cowrie.json (logs)
     ↓
Filebeat (ingestion)
     ↓
Elasticsearch (indexing)
     ↓
Kibana (visualization)
```
## 📄 Features

- Capture real SSH brute-force attacks
- Structured JSON log collection
- Log ingestion pipeline with Filebeat
- Indexing and search with Elasticsearch
- Interactive dashboards in Kibana
- Attack behavior analysis

## 📊 Dashboards
- Top attacking IPs
- Most targeted usernames
- Most used passwords
- Attacks over time

## 🧰 Technologies
- Docker
- Cowrie Honeypot
- Filebeat
- Elasticsearch
- Kibana
- Linux

## 🔢 Environment
- Elastic Stack (Elasticsearch, Kibana, Filebeat): 8.15.0
- Cowrie Honeypot: Docker image
- Docker: 24.x
- OS: Ubuntu Server 24.04

## 📌 Status

✔️ Fully functional in a local environment

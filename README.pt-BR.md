# 🛡️ Cowrie Honeypot + ELK Stack
 
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch)
![Kibana](https://img.shields.io/badge/Kibana-FF6F00?style=for-the-badge&logo=kibana&logoColor=white)
![Filebeat](https://img.shields.io/badge/Filebeat-00BFB3?style=for-the-badge)
![Cowrie](https://img.shields.io/badge/Cowrie-Honeypot-red?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux)
![Status](https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge)
![Security](https://img.shields.io/badge/Foco-Cibersegurança-blue?style=for-the-badge)

---

## 📚 Visão Geral

Este projeto simula um servidor SSH vulnerável utilizando o **Cowrie Honeypot**, capturando tentativas reais de invasão e analisando o comportamento dos atacantes através do **ELK Stack**.

> 🔍 Objetivo: Monitorar, analisar e visualizar ataques em tempo quase real.

---

## ⚙️ Arquitetura

```text
[ Atacante ]
     ↓
Cowrie Honeypot (SSH)
     ↓
cowrie.json (logs)
     ↓
Filebeat (ingestão)
     ↓
Elasticsearch (indexação)
     ↓
Kibana (visualização)
```

---

## 🚀 Funcionalidades

-  Captura de ataques SSH (força bruta)  
-  Coleta de logs estruturados em JSON  
-  Pipeline de ingestão com Filebeat  
-  Indexação e busca com Elasticsearch  
-  Dashboards interativos no Kibana  
-  Análise do comportamento de atacantes  

---

## 📊 Dashboards

-  IPs que mais atacam  
-  Usuários mais utilizados  
-  Senhas mais tentadas  
-  Ataques ao longo do tempo  

---

## 🧰 Tecnologias

-  Docker  
-  Cowrie Honeypot  
-  Filebeat  
-  Elasticsearch  
-  Kibana  
-  Linux  

---

## 🔢 Ambiente

- Elastic Stack (Elasticsearch, Kibana, Filebeat): 8.15.0  
- Cowrie Honeypot: imagem Docker  
- Docker: 24.x  
- Sistema Operacional: Ubuntu Server 24.04  

---

## 📌 Status

✔️ Projeto totalmente funcional em ambiente local  

# DevOps Homelab

Projekty z mojego homelaba — nauka DevOps pod rozmowę kwalifikacyjną.

## Stack
- **Linux** — Debian na Proxmox VE
- **Docker** — kontenery, docker-compose
- **ELK Stack** — Elasticsearch + Kibana + Filebeat
- **Ansible** — automatyzacja instalacji agentów
- **AWS** — EC2 z logami wysyłanymi do homelabowego ELK

## Projekty

### Centralny ELK w homelabie
- Elasticsearch + Kibana na VM w Proxmoxie
- Filebeat zbiera logi systemowe
- Dashboard w Kibanie z wizualizacjami

### Logi z chmury AWS
- EC2 na AWS wysyła logi do homelabowego ELK
- Unified monitoring — homelab i chmura w jednym miejscu

### Automatyzacja z Ansible
- Playbook automatycznie instaluje Filebeat na nowych maszynach
- Idempotentny — można uruchamiać wielokrotnie

### WordPress na Docker Compose
- WordPress + MySQL postawione jedną komendą
- Volumes dla persystencji danych

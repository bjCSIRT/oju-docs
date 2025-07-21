# Oju – Cybersecurity Monitoring Platform

Oju is an open-source cybersecurity monitoring platform for organizations and web platforms. It provides automated surveillance, threat detection, and alert management through real-time scanning, entity management, and integration with threat intelligence tools.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Integrations](#integrations)
- [Support](#support)

---

## Project Overview

Oju provides automated surveillance and threat detection for organizational entities and their websites through comprehensive scanning, real-time alerting, and incident response coordination. It helps security teams proactively monitor infrastructure and respond to incidents.

---

## Features

- **Multi-Platform Monitoring** – Monitor SSL, domains, website defacements, and availability.
- **Entity Management** – Organize platforms under organizational units with focal points.
- **Real-Time Dashboard** – View alerts, platform statuses, and global trends in one place.
- **Automated Alerting** – Trigger notifications and ticketing when issues arise.
- **Incident Response** – Integrated with RTIR for automated ticket creation.
- **Threat Intelligence** – Leverages VirusTotal for malware and URL analysis.

---

## Technologies Used

- **Django** – Backend and REST API
- **Vue.js** – Frontend interface
- **PostgreSQL** – Data storage
- **Redis** – Caching and background queue
- **Celery** – Distributed task execution
- **Nginx** – Web server and HTTPS reverse proxy
- **Docker / Docker Compose** – Deployment and service orchestration

---

## Installation

### Step 1: Install Prerequisites

- Docker Engine `v20.10+`
- Docker Compose `v1.29+`
- 2GB RAM (4GB recommended)
- 40GB disk space
- Ports `80` and `443` must be available

---

### Step 2: Install Oju

```bash
git clone https://github.com/bjCSIRT/oju.git
cd oju
./install.sh # for linux system

---

## Integrations

- RTIR : Automated incident response ticketing
- VirusTotal : Threat detection and scanning
- Cerebrate : Organizational data synchronization

---

## Support

- Issues : GitHub Issues
- Contact : bjcsirt@asin.bj
- Documentation : https://bjcsirt.github.io/oju

---

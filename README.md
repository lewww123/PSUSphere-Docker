# PSUSPHERE

## Short Descriptiion

This project containerizes the **PSUSphere Django Web Application** using Docker and Docker Compose. It allows anyone to run the system with a single command without manual setup of dependencies.
---


##PRoject Overview
PSUSphere is a Django-basef web application(student organiztion/portal system). >
This repository includes Docker configuration for easy deployment and portability

## List of Features
- Manage Colleges (Create, Update, Delete)
- Manage Academic Programs per College
- Manage Student Records
- Manage Organizations per College
- Track Organization Memberships
- Admin Dashboard with Search and Filter Functionalities
- Automatic timestamp tracking (created_at, updated_at)

---

##Prerequisites
Before running the project, mmake sure you have installed:
- Docker 
- Docker Compose
Check Installation
bash
docker --version
docker compose version
---

###STEP1 
git clone 
cd PSUSpehere
---

###STEP2 DOCKER SET-UP
- Build the Docker Image
docker build -t psusphere:latest .
- Run the app
docker compose up -d
- check running containers
docker ps
###STEP3 ACCESS THE APPLICATION
https://localhost:8000
---
## 👨‍💻 Authors

- Lewin Rey Kurt D. Laguisma 

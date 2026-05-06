# ☁️ WordPress & MariaDB Deployment on Google Cloud (GCP)

Este repositorio contiene la infraestructura como código (IaC) para desplegar un sitio web de WordPress autoalojado con una base de datos MariaDB, utilizando contenedores dentro de una máquina virtual en Google Cloud Platform.

## 🛠️ Stack Tecnológico (Tech Stack)
* **Cloud Provider:** Google Cloud Platform (Compute Engine)
* **OS:** Ubuntu 24.04 LTS
* **Containerization:** Docker & Docker Compose
* **Database:** MariaDB (10.6.4-focal)
* **Frontend:** WordPress (Latest)

## 🏗️ Arquitectura del Proyecto
El archivo `docker-compose.yml` orquesta dos servicios principales que se comunican a través de una red interna de Docker:
1. Un contenedor de base de datos relacional (MariaDB) con volúmenes persistentes para evitar la pérdida de datos.
2. Un contenedor de aplicación (WordPress) expuesto al puerto 80 del servidor web.

## 🚀 Cómo ejecutar este proyecto
Para replicar esta infraestructura en cualquier servidor Linux con Docker instalado:

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/JJJuaNNNRRRuiZZZ/wordpress-docker-gcp.git](https://github.com/JJJuaNNNRRRuiZZZ/wordpress-docker-gcp.git)

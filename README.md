# Proyecto DevOps con AWS y Docker

## Descripción del Proyecto

Este proyecto implementa un entorno DevOps utilizando servicios de AWS, Docker y GitHub para automatizar el despliegue de una aplicación web. Se utilizan herramientas de Infraestructura como Código (IaC), automatización y contenedores para facilitar la implementación y gestión de la aplicación.

---

## Objetivo

Implementar una arquitectura DevOps en AWS que permita:

* Automatización del despliegue
* Infraestructura como código
* Contenedores Docker
* Scripts de automatización
* Gestión de recursos en AWS

---

## Tecnologías Utilizadas

* AWS EC2
* AWS CloudFormation
* AWS S3
* Docker
* Docker Compose
* Python
* Bash
* GitHub
* Linux Ubuntu

---

## Arquitectura del Proyecto

GitHub Repository
↓
AWS EC2 Instance
↓
Docker Container
↓
Aplicación Web Flask

---

## Estructura del Proyecto

```
proyecto-devops/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
│
├── scripts/
│   └── setup.sh
│
├── aws/
│   └── cloudformation.yaml
│
└── README.md
```

---

## Configuración del Entorno

### 1. Clonar el repositorio

```
git clone https://github.com/usuario/proyecto-devops.git
```

### 2. Entrar al proyecto

```
cd proyecto-devops
```

---

## Configuración Docker

### Construir contenedor

```
sudo docker-compose build
```

### Ejecutar contenedor

```
sudo docker-compose up -d
```

---

## Script de Automatización Bash

El proyecto incluye scripts para automatizar la configuración del servidor:

```
./scripts/setup.sh
```

Este script instala:

* Docker
* Python
* Git
* Dependencias necesarias

---

## Script Python AWS (Boto3)

El script Python permite:

* Listar instancias EC2
* Listar buckets S3
* Generar reportes

Ejecutar:

```
python3 aws_script.py
```

---

## CloudFormation

El proyecto incluye infraestructura como código utilizando CloudFormation.

Archivo:

```
cloudformation.yaml
```

Este archivo crea:

* Instancias EC2
* Recursos S3
* Configuración básica

---

## Despliegue

Una vez ejecutado el contenedor, la aplicación estará disponible en:

```
http://IP_PUBLICA:5000
```

---

## Evidencias

El proyecto incluye:

* Capturas de AWS EC2
* Capturas Docker
* Capturas CloudFormation
* Capturas GitHub

---

## Autor

Sebastián Díaz
Proyecto DevOps
AWS Learner Lab

---

## Estado del Proyecto

Proyecto completado y funcional en AWS Learner Lab.

---

## Notas

Este proyecto fue desarrollado como práctica de implementación DevOps utilizando herramientas modernas de automatización y despliegue continuo.

---

## Licencia

Uso académico

---

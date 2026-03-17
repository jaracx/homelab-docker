# 🛡️ HomeLab: DNS Sinkhole & Monitoring

Este proyecto implementa una infraestructura de red local segura utilizando **Docker** para filtrar tráfico malicioso y publicidad a nivel de DNS.

## 🚀 Tecnologías utilizadas
* **Parrot OS**: Sistema operativo base.
* **Docker & Docker Compose**: Orquestación de contenedores.
* **Pi-hole**: DNS Sinkhole para bloqueo de trackers y anuncios.
* **Uptime Kuma**: Monitoreo de disponibilidad de servicios.

## 🛠️ Configuración
El despliegue se realiza mediante una receta de `docker-compose` que gestiona la persistencia de datos en el host, asegurando que las listas de bloqueo y el historial de monitoreo sobrevivan a reinicios del contenedor.

## 📈 Resultados
* Reducción de telemetría y anuncios en dispositivos de la red local.
* Panel de monitoreo activo con alertas de disponibilidad.
* Gestión centralizada de listas negras (Adlists).

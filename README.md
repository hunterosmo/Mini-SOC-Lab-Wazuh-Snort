🛡️ Mini SOC – Centro de Mando

Este proyecto es una implementación práctica de un Mini SOC (Security Operations Center) basado en Wazuh + Snort + Python, creado para aprender, practicar y experimentar con monitoreo, detección de intrusos y análisis de eventos de seguridad en entornos Windows.

El sistema corre sobre Windows 11 y utiliza Docker + WSL2 para desplegar Wazuh, mientras que el equipo principal actúa como agente monitoreado, incluyendo un sensor IDS Snort que alimenta alertas directamente a Wazuh.

Además, se desarrolló un script en Python que automatiza el análisis consultando la API de Wazuh, permitiendo detectar amenazas y generar reportes básicos desde consola.

📦 ¿Qué trae este proyecto?

Este proyecto incluye 4 guías completas en formato HTML, documentadas paso a paso:

📘 Guía Maestra Wazuh
Instalación y despliegue de Wazuh en Docker desde cero.

🖥️ Guía Agente Wazuh (Windows)
Instalación y configuración del agente en Windows 10/11.

🕵️ Guía Snort + Wazuh
Configuración de Snort + Npcap e integración directa con Wazuh.

🤖 Guía de Automatización en Python
Creación del script SOC y entorno virtual para análisis automático.

Este proyecto está diseñado para estudiantes, autodidactas y personas que quieren aprender Blue Team desde cero sin saltarse pasos, usando herramientas reales.

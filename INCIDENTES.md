# 🚨 PLAN DE RESPUESTA ANTE INCIDENTES
## Tech Solutions Inc.

---

## 1. Objetivo

Este documento establece las acciones que deben realizarse cuando se detecte una actividad sospechosa o un posible incidente de seguridad en el servidor Linux.

El objetivo es identificar rápidamente el problema, contenerlo, analizarlo y recuperar el funcionamiento normal del servidor.

---

## 2. Tipos de incidentes

Los principales incidentes que pueden presentarse son:

- 🔴 Intentos repetidos de acceso mediante SSH.
- 🔴 Accesos no autorizados.
- 🔴 Puertos o servicios desconocidos.
- 🔴 Consumo anormal de CPU o memoria.
- 🔴 Modificación no autorizada de archivos.
- 🔴 Intentos de ataque de fuerza bruta.
- 🔴 Actividad sospechosa detectada por Fail2Ban.

---

## 3. Detección

Cuando se detecte una actividad sospechosa, primero se debe revisar el estado general del servidor.

### Revisar procesos

```bash
ps aux --sort=-%cpu | head

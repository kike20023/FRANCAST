# 🖥️ ARQUITECTURA DE SEGURIDAD DEL SERVIDOR
## Tech Solutions Inc.

---

## 1. Descripción

La arquitectura de seguridad implementada para Tech Solutions Inc. está formada por diferentes componentes que trabajan en conjunto para proteger, monitorear y administrar el servidor Linux.

Cada herramienta cumple una función específica dentro de la infraestructura.

---

## 2. Componentes principales

### 🖥️ Servidor Linux

Es el componente central de la infraestructura.

En él se ejecutan los servicios, aplicaciones, procesos y herramientas de seguridad.

---

### 🔑 SSH

SSH permite administrar el servidor de manera remota mediante una conexión segura.

Se aplicaron medidas de endurecimiento para reducir los riesgos de acceso no autorizado.

```text
Administrador
      │
      │ Conexión SSH
      ▼
┌─────────────────┐
│  Servidor Linux │
└─────────────────┘

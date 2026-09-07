# 🔐 SEGURIDAD DEL SERVIDOR LINUX
## Tech Solutions Inc.

---

## 1. Objetivo

El objetivo de este proyecto es implementar medidas básicas de seguridad para proteger el servidor Linux de Tech Solutions Inc., reduciendo los riesgos relacionados con accesos no autorizados, ataques de fuerza bruta y servicios expuestos innecesariamente.

Las principales herramientas utilizadas fueron:

- SSH
- UFW
- Fail2Ban
- Bash
- Git y GitHub

---

# 2. Endurecimiento de SSH

SSH es el servicio utilizado para administrar el servidor de manera remota.

Antes de modificar la configuración se recomienda realizar una copia de seguridad:

```bash
sudo cp /etc/ssh/sshd_config /etc/ssh/sshd_config.bak

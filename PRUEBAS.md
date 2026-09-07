# 🧪 PRUEBAS Y VALIDACIÓN DEL SERVIDOR
## Tech Solutions Inc.

---

## 1. Objetivo

El objetivo de este documento es registrar las pruebas realizadas después de implementar las medidas de seguridad del servidor Linux.

Las pruebas permiten comprobar que SSH, UFW, Fail2Ban y los sistemas de monitoreo funcionan correctamente.

---

## 2. Prueba de SSH

Se verificó que el servicio SSH se encuentre activo:

```bash
sudo systemctl status ssh

# 03 — Preparación del sistema

1. Actualiza índices y paquetes:
   ```bash
   sudo apt update 
   ```
   ![Update/Upgrade](../assets/img/03-preparacion_sistema/03-sudoupdate.png)  

   ```bash
   sudo apt upgrade
   ```
   ![Update/Upgrade](../assets/img/03-preparacion_sistema/03-sudoupgrade.png)

2. Configura zona horaria e idioma si procede.

   ```bash
      date
      sudo timedatectl set-timezone "Europe/Madrid"
   ```
   ![FechaYHora](../assets/img/03-preparacion_sistema/03-fechayhora.png)
   ![FechaYHora](../assets/img/03-preparacion_sistema/03-fecha.png)


> Resultado esperado: sistema actualizado y listo para instalar dependencias.

# 04 — PostgreSQL en Linux

1. Instala PostgreSQL desde repos (se ejecuta ese codigo, pones la contraseña y le das a continuar):
   ```bash
   sudo apt -y install postgresql
   ```
   ![Servicio PostgreSQL](../assets/img/04-postgresql_linux/04-sqlLinux.png)

2. Verifica el servicio (se ejecuta ese codigo y tiene que dar ese resultado):
   ```bash
   sudo systemctl status postgresql
   ```
   ![Servicio PostgreSQL](../assets/img/04-postgresql_linux/04-verificacion.png)

3. (Opcional) Cambia contraseña del usuario `postgres` o crea rol específico para Odoo.

> Resultado esperado: PostgreSQL instalado y activo.

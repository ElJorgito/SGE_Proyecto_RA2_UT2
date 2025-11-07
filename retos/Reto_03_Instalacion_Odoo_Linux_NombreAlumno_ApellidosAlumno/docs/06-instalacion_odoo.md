# 06 — Instalación de Odoo

## Método A — Paquete oficial (repositorio Odoo)  
Enlace fuente: https://www.odoo.com/documentation/17.0/es/administration/on_premise/packages.html  
1. Añade repositorio/clave y luego instala `odoo`:
> Ejecuta estos codigos por pantalla y todo deberia funcionar
   ```bash
   -wget -q -O - https://nightly.odoo.com/odoo.key | sudo gpg --dearmor -o /usr/share/keyrings/odoo-archive-keyring.gpg
   -echo 'deb [signed-by=/usr/share/keyrings/odoo-archive-keyring.gpg] https://nightly.odoo.com/17.0/nightly/deb/ ./' | sudo tee /etc/apt/sources.list.d/odoo.list
   -sudo apt-get update && sudo apt-get install odoo
   ```
> Resultado esperado: binarios/código de Odoo instalados.

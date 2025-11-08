# 05 — Integración con Gmail (OAuth GCP + Add-on)

> En este apartado se va a ver como integrar el gmail con Odoo

## Requisitos
- Cuenta Google Cloud (GCP).

## Pasos resumidos

1. **Activar plugin de correo** en Odoo e instalar *Odoo Inbox Add-on* en Gmail.
> Primero tenemos que activar el plugin del correo e los ajustes generales
![Plugin](../assets/img/05-integracion_gmail/05-integracion-plugin.png)

2. En **Google Cloud Console**: habilitar *Gmail API*, crear **OAuth Client (Web)**, configurar **redirect URI** de Odoo.


3. Copiar **Client ID/Secret** a Odoo (Gmail server settings) y **Guardar**.


4. Probar desde Gmail: crear contacto/oportunidad desde el add-on.



![GCP OAuth](../assets/img/05-integracion_gmail/paso01_gcp-oauth.png "GCP OAuth")

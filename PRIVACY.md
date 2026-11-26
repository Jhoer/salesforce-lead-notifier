# Política de Privacidad – Salesforce Lead Notifier

**Última actualización:** 25 de noviembre de 2026

Salesforce Lead Notifier funciona de manera 100% local en el navegador del usuario y no recopila, almacena en servidores externos, vende ni comparte información personal o datos de Salesforce con terceros.

## Qué información procesa localmente
- **Notificaciones de Salesforce Lightning (`*.salesforce.com` / `*.force.com`):** La extensión lee únicamente dentro de tu navegador el título, detalle y enlace del registro notificado en la campana de Salesforce para mostrar el banner nativo de Windows y reproducir tu alerta sonora.
- **Preferencias de usuario (`chrome.storage.local`):** El tono seleccionado, volumen, audio personalizado opcional (`.mp3` / `.wav`) y preferencia de apertura de pestaña se guardan exclusivamente de forma local en tu dispositivo.

## Permisos utilizados
- `notifications`: Mostrar banners nativos de escritorio y abrir el registro correspondiente al hacer clic.
- `storage`: Guardar preferencias de sonido y URLs temporales de alertas recientes en el dispositivo.
- `tabs`: Detectar pestañas activas de Salesforce Lightning y enfocarlas o abrir el registro notificado.

## Transferencia a terceros
No existe transmisión de datos fuera de tu navegador. Todo el procesamiento se realiza localmente en tu equipo.

# uptime-kuma

Monitoreo externo del homelab (status.mystoredigital.cloud).
Vigila los tuneles publicos de casa y alerta por Telegram cuando el homelab pierde internet.

Desplegado en el VPS dokploy via Dokploy + Traefik + Let's Encrypt.
Datos en el volumen `kuma-data` (SQLite).

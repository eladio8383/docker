# Checklist de escalada de privilegios

## Antes de escalar
- Recolectar usuarios, grupos y permisos.
- Revisar `sudo -l`.
- Revisar SUID / SGID.
- Revisar `cron` y servicios.

## Evaluar rutas comunes
- `sudo` sin passwd.
- binarios SUID con ejecución de scripts.
- credenciales en archivos de configuración.
- Ficheros de cron con permisos ampliados.
- acceso a claves privadas.

## Técnicas
- Exploit local.
- Abuse of writable files.
- Kerberoasting / AS-REP Roasting (AD).
- Abuso de permisos de servicio.

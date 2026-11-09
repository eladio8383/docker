# Plantilla de escalada de privilegios

## 1. Identificación del usuario
```bash
whoami
id
```

## 2. Enumeración del sistema
```bash
uname -a
cat /etc/os-release
sudo -l
```

## 3. Servicios y procesos
```bash
ps aux
ss -tulpn
```

## 4. Permisos SUID / sudo
```bash
find / -perm -4000 2>/dev/null
```

## 5. Archivos con permisos sospechosos
```bash
ls -l /etc/cron* 2>/dev/null
ls -l /var/www 2>/dev/null
```

## 6. Ruta explotada
- Técnica:
- Comando:

## 7. Privilegios obtenidos
```bash
whoami
id
```

## 8. Mitigación
- Reducir permisos:
- Revisar sudoers:
- Revisar SUID:

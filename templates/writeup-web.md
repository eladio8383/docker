# Plantilla para máquinas web

## Datos
- App:
- URL:
- Framework:
- Dificultad:

## Reconocimiento
```bash
whatweb http://<IP>
nikto -h http://<IP>
```

## Enumeración de contenido
```bash
gobuster dir -u http://<IP> -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt
```

## Vulnerabilidades sospechosas
- XSS
- SQLi
- LFI
- RCE
- IDOR

## Explotación
```bash
# payload / curl / burp
```

## Escalada web / acceso shell
```bash
# reverse shell / rutas de carga
```

## Resultados
- Flag:
- Datos expuestos:

## Recomendaciones
- Hardening:
- Configuración del servidor:

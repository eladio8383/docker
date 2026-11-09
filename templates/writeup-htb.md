# Plantilla de writeup para HTB / CTF

## Información general
- Máquina:
- Dificultad:
- OS:
- Tipo:
- IP:

## Reconocimiento
### Nmap
```bash
nmap -sC -sV -p- -T4 <IP>
```

### Enumeración de servicios
```bash
nmap -sV --version-all -p 21,22,80,443,3306,8080 <IP>
```

## Enumeración web
```bash
whatweb http://<IP>
curl -I http://<IP>
```

## Explotación
### Vulnerabilidad elegida
- Nombre:
- Forma de explotación:

```bash
# payload
```

## Post-explotación
```bash
whoami
id
hostname
```

## Escalada de privilegios
```bash
sudo -l
uname -a
```

## Flags
- User:
- Root:

## Notas finales
- Causa raíz:
- Vector de ataque:
- Recomendación:

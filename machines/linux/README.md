# Plantilla para máquinas Linux

## Datos
- Nombre:
- IP:
- Versión del SO:
- Dificultad:

## Enumeración inicial
```bash
whoami
id
uname -a
ls -la
```

## Servicios activos
```bash
ss -tulpn
```

## Explotación
```bash
# payload / exploit
```

## Escalada
```bash
sudo -l
find / -perm -4000 2>/dev/null
```

## Resultado
- Usuario comprometido:
- Root obtenido:

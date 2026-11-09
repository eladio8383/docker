# Plantilla para máquinas Windows

## Datos de la máquina
- Nombre:
- Dificultad:
- IP:
- Dominio:

## Reconocimiento
```powershell
ipconfig /all
systeminfo
net user
net group
```

## Enumeración de servicios
```powershell
Get-Service
netstat -ano
```

## Credenciales y acceso
```powershell
whoami
hostname
```

## Escalada de privilegios
```powershell
whoami /priv
Get-ChildItem C:\Users\
```

## Flags / evidencia
- User:
- Administrator:

## Resumen
- Vector de acceso:
- Qué vulnerabilidad se explotó:
- Recomendaciones:

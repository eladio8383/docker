# Plantilla para Active Directory

## Datos
- Dominio:
- Nombre del equipo:
- IP:
- Dificultad:

## Enumeración
```powershell
whoami /all
net users
net group /domain
nltest /domain_trusts
```

## Reconocimiento del dominio
```powershell
Get-ADUser -Filter *
Get-ADComputer -Filter *
```

## Kerberos / credenciales
```powershell
klist
mimikatz
```

## Escalada
```powershell
# técnica / abuso de privilegios
```

## Resultado
- Dominio comprometido:
- Usuario explotado:

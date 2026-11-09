# Repositorio de Writeups y Máquinas

Este repositorio está pensado para guardar plantillas de writeups, apuntes de máquinas, checklist de enumeración y documentación útil para retos de ciberseguridad, labs, CTFs y entornos de prueba.

## Estructura

- `templates/`: plantillas de writeup para distintos tipos de retos.
- `machines/`: carpetas por tipo de máquina y contexto.
- `checklists/`: listados de pasos para enumeración, explotación y escalada de privilegios.
- `notes/`: comandos útiles y notas rápidas.
- `docker-compose.yml`: ejemplo de stack para infraestructura local.

## Plantillas disponibles

- `templates/writeup-basic.md`
- `templates/writeup-htb.md`
- `templates/writeup-thm.md`
- `templates/writeup-ctf.md`
- `templates/writeup-linux.md`
- `templates/writeup-web.md`
- `templates/writeup-forensics.md`
- `templates/writeup-privilege-escalation.md`

## Máquinas por tipo

- `machines/windows/`
- `machines/linux/`
- `machines/web/`
- `machines/active-directory/`
- `machines/cloud/`

## Uso recomendado

1. Copia la plantilla que más se adapte al reto.
2. Crea una carpeta en `machines/` con el nombre de la máquina.
3. Completa enumeración, explotación y evidencias.
4. Guarda flags, comandos y lecciones aprendidas.
5. Añade la nota final con resumen técnico y mitigación.

## Plantilla rápida

```md
# [Nombre de la máquina]

## Información
- Tipo:
- Dificultad:
- Sistema operativo:
- IP:
- Fecha:

## Enumeración
### Nmap
```bash
nmap -sC -sV -A <IP>
```

### Servicios
- Puerto 80: HTTP
- Puerto 22: SSH
- Puerto 445: SMB

## Explotación
### Vulnerabilidad
- Descripción:
- Vector:

```bash
# comando / payload
```

## Escalada de privilegios
```bash
# comandos
```

## Flags
- User:
- Root:

## Resumen
- Qué aprendí:
- Qué falta por mejorar:
- Mitigación sugerida:
```

## Licencia

Este repositorio está pensado para uso personal y de aprendizaje.

# Plantilla para forense / artefactos

## Caso
- Nombre del caso:
- Tipo de evidencia:
- Formato:
- Fecha:

## Análisis inicial
```bash
file evidence.img
md5sum evidence.img
sha256sum evidence.img
```

## Montaje / adquisición
```bash
mkdir /mnt/evidence
mount -o loop evidence.img /mnt/evidence
```

## Hallazgos
- Archivos sospechosos:
- Procesos relevantes:
- Mensajes/metadatos:

## Análisis forense
```bash
ls -R /mnt/evidence
strings suspicious.bin | head -200
```

## Conclusión
- Resumen del caso:
- Indicadores de compromiso:
- Impacto:

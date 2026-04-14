---
name: generate-pitch
description: Genera un pitch deck completo desde un brief de texto o documento. Produce archivo .pptx listo para presentar.
---

# Skill: generate-pitch

Genera un pitch deck profesional completo.

## Uso

```
/generate-pitch [brief o descripcion del negocio]
```

## Proceso

1. Analizar el brief con `content-analyzer`
2. Generar estructura con las 10-12 slides estandar
3. Escribir contenido por slide
4. Crear archivo `.pptx` con python-pptx
5. Guardar en `output/` con timestamp

## Inputs aceptados

- Texto libre describiendo el negocio
- Path a documento Word/PDF
- URL de landing page o sitio web

## Output

- `output/pitch_deck_YYYYMMDD_HHMMSS.pptx`
- Resumen de slides generados en consola

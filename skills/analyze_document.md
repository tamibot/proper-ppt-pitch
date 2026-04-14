---
name: analyze-document
description: Analiza un documento (PDF, Word, texto) y extrae estructura para presentacion. Devuelve JSON con puntos clave y estructura sugerida de slides.
---

# Skill: analyze-document

Extrae insights de documentos para estructurar presentaciones.

## Uso

```
/analyze-document [path al archivo o URL]
```

## Proceso

1. Leer el documento
2. Identificar: problema, solucion, mercado, equipo, financials
3. Extraer metricas y data points clave
4. Sugerir estructura de slides
5. Devolver JSON estructurado

## Output

```json
{
  "title": "...",
  "tagline": "...",
  "audience": "...",
  "key_messages": [],
  "suggested_slides": [],
  "data_points": [],
  "missing_sections": []
}
```

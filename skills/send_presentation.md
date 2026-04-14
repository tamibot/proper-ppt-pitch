---
name: send-presentation
description: Envia una presentacion por Gmail como adjunto o como link de Google Slides. Usa cuando quieras compartir el deck generado.
---

# Skill: send-presentation

Envia el pitch deck por email usando Gmail MCP.

## Uso

```
/send-presentation [archivo.pptx] [email destinatario] [mensaje opcional]
```

## Proceso

1. Verificar que el archivo existe
2. Subir a Google Drive (opcional)
3. Crear draft en Gmail con adjunto o link
4. Confirmar con usuario antes de enviar

## Requiere

- `GOOGLE_CLIENT_ID` y `GOOGLE_CLIENT_SECRET` en `credentials/.env`
- Gmail MCP conectado

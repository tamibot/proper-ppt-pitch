# CLAUDE.md — Configuracion para Claude Code

Este archivo define el comportamiento, reglas y contexto para Claude Code en este proyecto.

## Proyecto

**Proper PPT Pitch** — Generador automatico de presentaciones con IA para Antigravity Google.

## Comportamiento esperado

- Respuestas concisas y directas, sin texto de relleno
- No pedir confirmacion para operaciones de lectura/escritura de archivos locales
- Priorizar velocidad de iteracion sobre perfeccion prematura
- Usar siempre los modelos mas recientes de Claude (Sonnet 4.6 por defecto)

## Stack tecnico

- **Backend:** Python 3.11+
- **IA:** Anthropic Claude API (claude-sonnet-4-6, claude-opus-4-6, claude-haiku-4-5)
- **Presentaciones:** python-pptx
- **Integraciones:** Google API, Gmail MCP, Calendar MCP

## Convenciones de codigo

- Snake_case para variables y funciones en Python
- Docstrings solo donde la logica no es evidente
- No agregar manejo de errores para casos imposibles
- Validar solo en boundaries del sistema (input usuario, APIs externas)

## Credenciales

- NUNCA commitear archivos .env o credenciales reales
- Usar `credentials/.env` (gitignoreado)
- Ver `credentials/.env.example` como referencia

## Agentes disponibles

Ver `/agents/` para las definiciones de agentes especializados.

## Permisos

Claude Code tiene permisos completos en este proyecto. Ver `.claude/settings.json`.

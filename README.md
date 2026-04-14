# Proper PPT Pitch — Antigravity Google

Proyecto de generacion automatica de presentaciones PowerPoint con IA.

## Descripcion

Herramienta para crear pitch decks profesionales usando Claude AI, con integraciones a Google Slides, Gmail y Calendar.

## Estructura del proyecto

```
proper_ppt_pitch/
├── README.md              # Este archivo
├── CLAUDE.md              # Configuracion e instrucciones para Claude
├── .claude/
│   ├── settings.json      # Permisos y configuracion de Claude Code
│   └── agents/            # Agentes especializados
├── credentials/
│   └── .gitkeep           # Carpeta para credenciales (NO commitear archivos .env)
├── agents/                # Definiciones de agentes IA
├── rules/                 # Reglas de negocio y validaciones
├── skills/                # Skills personalizados
├── llm/                   # Configuracion de modelos LLM
└── src/                   # Codigo fuente principal
```

## Setup rapido

```bash
# Instalar dependencias
pip install -r requirements.txt

# Configurar credenciales
cp credentials/.env.example credentials/.env
# Editar credentials/.env con tus valores

# Ejecutar
python src/main.py
```

## Modelos LLM usados

- Claude Sonnet 4.6 — generacion principal de contenido
- Claude Opus 4.6 — tareas complejas de razonamiento
- Claude Haiku 4.5 — tareas rapidas y economicas

## Integraciones

- Google Slides API
- Gmail MCP
- Google Calendar MCP
- Anthropic Claude API

## Licencia

Propietario — Antigravity Google 2026

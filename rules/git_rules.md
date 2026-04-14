# Reglas de Git

## Archivos a NUNCA commitear

- `credentials/.env` (credenciales reales)
- `*.pem`, `*.key`, `*.p12` (certificados)
- `__pycache__/`, `*.pyc`
- `.DS_Store`
- `node_modules/`
- Outputs generados (`output/*.pptx` a menos que sean ejemplos)

## Commit messages

Formato: `tipo: descripcion breve`

Tipos:
- `feat:` nueva funcionalidad
- `fix:` correccion de bug
- `docs:` solo documentacion
- `refactor:` refactoring sin cambio de comportamiento
- `test:` tests
- `chore:` tareas de mantenimiento

## Branches

- `main` — produccion, siempre estable
- `dev` — desarrollo activo
- `feature/nombre` — features especificos
- `fix/nombre` — hotfixes

## Co-authored-by

Incluir siempre en commits generados por Claude:
```
Co-Authored-By: Claude Sonnet 4.6 <noreply@anthropic.com>
```

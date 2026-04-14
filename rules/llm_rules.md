# Reglas para uso de LLMs

## Seleccion de modelo

| Tarea | Modelo | Razon |
|-------|--------|-------|
| Generacion de slides completo | claude-sonnet-4-6 | Balance calidad/costo |
| Analisis de documentos complejos | claude-opus-4-6 | Mayor razonamiento |
| Revisiones rapidas, validaciones | claude-haiku-4-5 | Velocidad y costo |
| Agentes autonomos complejos | claude-opus-4-6 | Mejor en tool use |

## Prompting

- Siempre dar contexto de audiencia objetivo
- Especificar formato de output (JSON, markdown, texto)
- Dar ejemplos cuando el formato es no estandar
- Temperatura 0.7 para contenido creativo, 0.2 para estructurado

## Limites de tokens

- Input maximo: 100k tokens (reservar 8k para output)
- Si documento supera limite: chunking por secciones
- Siempre incluir instruccion de longitud maxima en prompt

## Costos estimados (orientativo)

- Sonnet 4.6: $3/1M input, $15/1M output
- Opus 4.6: $15/1M input, $75/1M output
- Haiku 4.5: $0.80/1M input, $4/1M output

## Seguridad

- No enviar credenciales reales en prompts
- No enviar PII de clientes en contexto
- Logs de LLM no deben contener tokens de API

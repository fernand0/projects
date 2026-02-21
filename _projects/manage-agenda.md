---
layout: project
title: manage-agenda
description: Añade eventos a Google Calendar desde emails y webs usando LLMs
image: /assets/img/slider/slide1.jpg
order: 7
---

Herramienta Python que extrae automáticamente información de eventos de emails y páginas web usando LLMs y los añade a Google Calendar.

## Características

- **Integración con Email**: Extrae eventos de mensajes de Gmail
- **Procesamiento de Páginas Web**: Extrae eventos de URLs
- **Multi-LLM**: Funciona con Gemini, Mistral y Ollama
- **Reconocimiento Inteligente de Fechas**: Parsing avanzado de fechas
- **Sincronización con Google Calendar**: Añade eventos automáticamente

## Instalación

```bash
git clone git@github.com:fernand0/manage-agenda.git
cd manage-agenda
uv sync  # o pip install -e .
```

## Uso

```bash
# Añadir eventos desde email (interactivo)
uv run manage-agenda add -i True

# Añadir eventos desde web
uv run manage-agenda add web -u https://example.com/event

# Limpiar entradas del calendario
uv run manage-agenda clean
```

## Comandos Disponibles

| Comando | Descripción |
|---------|-------------|
| `add mail` | Añade eventos desde emails |
| `add web` | Añade eventos desde páginas web |
| `clean` | Limpia eventos del calendario |
| `copy` | Copia eventos entre calendarios |
| `update-status` | Cambia estado de evento |

## Código

Disponible en [manage-agenda en GitHub](https://github.com/fernand0/manage-agenda)

Licencia: Apache-2.0

## Relaciones

Utiliza módulos de [socialModules](socialModules) para integración con email y calendario

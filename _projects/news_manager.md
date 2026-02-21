---
layout: project
title: news_manager
description: Genera artículos de noticias desde texto o URLs con Google Gemini AI
image: /assets/img/slider/slide1.jpg
order: 8
---

Aplicación CLI Python que genera artículos de noticias desde archivos de texto o URLs usando la API de Google Gemini.

## Características

- Generar noticias desde archivos locales (`--input-file`)
- Generar noticias desde URLs (`--url`)
- Instrucciones personalizadas de prompt (`--prompt-extra`)
- Modo de prompt interactivo (`--interactive-prompt`)
- Formato especial para tesis doctorales

## Instalación

```bash
git clone https://github.com/fernand0/news_manager.git
cd news_manager
python -m venv .venv
source .venv/bin/activate
pip install -e .
```

## Configuración

Crea un archivo `.env`:

```
GOOGLE_API_KEY="TU_API_KEY_AQUI"
```

## Uso

```bash
# Desde archivo local
python -m news_manager generate --input-file ./my_news.txt

# Desde URL
python -m news_manager generate --url "https://example.com"

# Con instrucciones personalizadas
python -m news_manager generate --url "https://example.com" --prompt-extra "tono formal"
```

## Publicar en Bluesky

```bash
uv run news_publisher publish
```

## Código

Disponible en [news_manager en GitHub](https://github.com/fernand0/news_manager)

Licencia: MIT

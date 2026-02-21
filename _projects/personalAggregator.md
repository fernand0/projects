---
layout: project
title: personalAggregator
description: Herramienta para agregar contenido web y generar posts markdown para Jekyll
image: /assets/img/slider/slide1.jpg
order: 4
---

Herramienta Python para agregar contenido de múltiples fuentes web y generar posts markdown para Jekyll.

## Características

- Agrega contenido desde múltiples URLs usando selectores CSS personalizables
- Extrae títulos, fechas y contenido de páginas web
- Soporta formatos de fecha personalizados con parsing automático vía `dateparser`
- Aplica etiquetas a los posts generados
- Genera archivos markdown compatibles con Jekyll

## Instalación

```bash
git clone https://github.com/fernand0/personalAggregator.git
cd personalAggregator
pip install -r requirements.txt
```

## Configuración

Crea un archivo `rules.json` definiendo las reglas de agregación:

```json
[
  {
    "url": "https://example.com/blog",
    "selector": ".post-item",
    "title_selector": ".post-title a",
    "date_selector": ".post-date",
    "tags": ["blog", "example"]
  }
]
```

## Uso

```bash
python _bin/personalAggregator.py --config-file rules.json --output-dir _posts/
```

## Código

Disponible en [personalAggregator en GitHub](https://github.com/fernand0/personalAggregator)

Licencia: MIT

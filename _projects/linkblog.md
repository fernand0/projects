---
layout: project
title: linkblog
description: Blog Jekyll que genera automáticamente posts diarios con enlaces de Twitter
image: /assets/img/slider/slide1.jpg
order: 5
---

Blog basado en Jekyll que genera automáticamente posts diarios con enlaces curados de Twitter.

## Características

- **Generación automática de posts**: Script Python que obtiene enlaces de Twitter para una fecha dada
- **Automatización diaria**: Script shell que automatiza todo el flujo
- **Deploy en GitHub Pages**: Despliegue automático vía GitHub Actions
- **Soporte para desarrollo local**: Puede servirse con `bundle exec jekyll serve`

## Cómo Funciona

1. **`scripts/list_twitter_links_by_date.py`**: Obtiene enlaces y formatea en Markdown
2. **`scripts/daily_post.sh`**: Automatiza: obtener enlaces, crear post, commit y push

## Instalación

```bash
git clone https://github.com/fernand0/linkblog.git
cd linkblog
pip install -r requirements.txt
```

## Nota

El script Python depende del módulo `socialModules.modulePublicationCache` que no está incluido en el repositorio.

## Código

Disponible en [linkblog en GitHub](https://github.com/fernand0/linkblog)

## Relaciones

Utiliza módulos de [socialModules](socialModules) para obtener los enlaces de Twitter

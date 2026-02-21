---
layout: project
title: another-note-taking-app
description: App de notas CLI con etiquetas, referencias cruzadas y versionado Git automático
image: /assets/img/slider/slide1.jpg
order: 6
---

Aplicación de toma de notas basada en texto con interfaz CLI, soporte para etiquetas, referencias entre notas y versionado automático con Git.

## Características

- **CRUD completo**: Crear, leer, actualizar y eliminar notas
- **Organización**: Añade etiquetas y especifica el origen (fuente) de tus notas
- **Interconectividad**: Referencia otras notas y rastrea referencias inversas
- **Integración con Git**: Commit automático de cambios
- **Búsqueda avanzada**: Universal, por campo específico, y multi-criterio

## Instalación

```bash
git clone https://github.com/fernand0/another-note-taking-app.git
cd another-note-taking-app
pip install -e .
```

## Uso Básico

```bash
# Inicializar
note-taker init

# Crear nota
note-taker create "Mi Nota" --content "Contenido..." --tags tag1

# Leer nota
note-taker read "Mi Nota"

# Listar notas
note-taker list
```

## Código

Disponible en [another-note-taking-app en GitHub](https://github.com/fernand0/another-note-taking-app)

## Relaciones

El plugin [err-notes](errBotPlugins) permite integrar esta aplicación con Errbot

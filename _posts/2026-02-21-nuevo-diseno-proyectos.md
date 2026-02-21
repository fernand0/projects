---
title: "Nuevo diseño y organización de proyectos"
description: "Hemos renovado completamente el sitio para mostrar de forma más clara y organizada todos los proyectos de software desarrollados."
date: 2026-02-21
picture: https://live.staticflickr.com/3037/2282709982_8674b13e0a.jpg

label_default: "meta"
label_primary: "story"
label_success: "blog"
---

El sitio ha sido completamente renovado para ofrecer una mejor experiencia de navegación y presentar de forma más clara todos los proyectos de software que he desarrollado a lo largo de los años.

## Nueva organización con Jekyll Collections

Todos los proyectos ahora están organizados utilizando **Jekyll Collections**, una característica nativa de Jekyll diseñada específicamente para contenido que no son posts del blog. Esto permite:

- **URLs más limpias**: Cada proyecto tiene su propia URL sin fechas (ej: `/botElectrico`)
- **Mejor organización**: Los proyectos están separados del blog
- **Fácil mantenimiento**: Añadir o reordenar proyectos es tan simple como editar un archivo markdown
- **Metadatos estructurados**: Cada proyecto tiene título, descripción, imagen y orden definidos en el front matter

## Proyectos incluidos

En esta primera versión hemos incluido **11 proyectos**:

### Bots y Automatización
- **botElectrico**: Bot que publica información sobre franjas horarias eléctricas
- **Errbot Plugins**: Colección de plugins para el framework Errbot

### Herramientas CLI
- **another-note-taking-app**: Aplicación de notas con CLI, etiquetas y versionado Git
- **manage-agenda**: Extrae eventos de emails y webs usando LLMs para Google Calendar
- **manage-imap**: Gestión de buzones IMAP con filtrado basado en reglas
- **news_manager**: Genera artículos de noticias usando Google Gemini AI
- **web_content_processor**: Extrae texto de páginas web y envía por email

### Integración con Redes Sociales
- **socialModules**: Módulos para publicar en múltiples redes sociales
- **linkblog**: Blog que genera posts automáticos con enlaces de Twitter

### Productividad
- **personalAggregator**: Agrega contenido web y genera posts para Jekyll

### Historia Personal
- **vimblog.vim**: Plugin de Vim para gestionar blogs. **El proyecto que me motivó a crear mi cuenta de GitHub**

## Nuevo diseño

La página principal ahora cuenta con:

- **Hero section**: Un encabezado limpio con el color corporativo #004235 de elmundoesimperfecto.com
- **Sin carrusel de imágenes**: Eliminamos las imágenes genéricas para ir directo al contenido
- **Diseño responsive**: Todos los proyectos se muestran en filas de 3 columnas que se adaptan a móviles

## Mejoras técnicas

- **Ruby 3.3+ compatible**: Actualizado el Gemfile para funcionar con versiones modernas de Ruby
- **Mejor rendimiento**: Las colecciones de Jekyll son más eficientes que las páginas HTML estáticas
- **Fácil extensión**: Añadir nuevos proyectos requiere solo crear un archivo markdown

## Próximas mejoras

En el futuro podríamos:
- Añadir capturas de pantalla o iconos para cada proyecto
- Implementar filtrado por categoría o tecnología
- Añadir búsqueda entre proyectos
- Crear una página de "sobre mí" que explique la historia detrás de estos proyectos

## Código disponible

Todos los proyectos son open source y están disponibles en [GitHub](https://github.com/fernand0?tab=repositories&q=err-). Siéntete libre de explorar el código, hacer fork o contribuir.

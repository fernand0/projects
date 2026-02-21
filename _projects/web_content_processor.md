---
layout: project
title: web_content_processor
description: Extrae texto de páginas web y envía contenido procesado vía email
image: /assets/img/slider/slide1.jpg
order: 10
---

Herramienta CLI que extrae texto legible de páginas web y opcionalmente envía el contenido procesado vía email.

## Características

- **Extracción de Contenido Web**: Extrae texto legible de páginas web
- **Omisión de URLs**: Omite dominios predefinidos (YouTube, Vimeo)
- **Logging de URLs**: Registra URLs procesadas para prevenir duplicación
- **Notificaciones Email**: Envía contenido procesado vía email
- **Manejo de Errores**: Notifica errores de descarga automáticamente

## Instalación

```bash
git clone https://github.com/fernand0/web_content_processor.git
cd web_content_processor
pip install -r requirements.txt
```

## Uso

```bash
python web_content_processor/WebContentProcessor.py <URL> [MODO] [--from-email EMAIL] [--to-email EMAIL]
```

## Modos de Procesamiento

| Modo | Descripción |
|------|-------------|
| `-txt` | Extrae texto plano sin enviar email |
| `-rea` | Extrae texto legible y envía vía email |
| `-reau` | Extrae texto legible y envía (incondicional) |

## Ejemplos

```bash
# Procesar URL y enviar como texto legible
python web_content_processor/WebContentProcessor.py https://example.com -rea --from-email sender@example.com --to-email receiver@example.com

# Procesar URL como texto plano
python web_content_processor/WebContentProcessor.py https://example.com -txt
```

## Código

Disponible en [web_content_processor en GitHub](https://github.com/fernand0/web_content_processor)

Licencia: MIT

## Relaciones

Puede utilizarse junto con [news_manager](news_manager) para procesamiento de contenido web

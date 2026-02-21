---
layout: project
title: Errbot Plugins
description: Plugins desarrollados para mi gestor de información personal basado en Errbot
image: /assets/img/slider/slide1.jpg
order: 3
---

Colección de plugins para [Errbot](https://errbot.readthedocs.io/), el framework de chatbot en Python.

Todos los plugins están desarrollados en Python y disponibles en [github.com/fernand0](https://github.com/fernand0?tab=repositories&q=err-).

## Lista de Plugins

### Comunicación y Mensajería

| Plugin | Descripción | License |
|--------|-------------|---------|
| [err-forward](https://github.com/fernand0/err-forward) | Reenvía mensajes entre instancias de Errbot en diferentes backends | GPL-3.0 |

### Redes Sociales y Contenido

| Plugin | Descripción | License |
|--------|-------------|---------|
| [err-buffer](https://github.com/fernand0/err-buffer) | Gestión de cuentas de redes sociales vía Buffer API | Public Domain |
| [err-social](https://github.com/fernand0/err-social) | Publicación en redes sociales (abandonado) | - |
| [err-numerology](https://github.com/fernand0/err-numerology) | Consulta número de suscriptores de usuarios | - |

### Productividad Personal

| Plugin | Descripción | License |
|--------|-------------|---------|
| [err-pim](https://github.com/fernand0/err-pim) | Gestor de información personal | - |
| [err-calendar](https://github.com/fernand0/err-calendar) | Interacción con Google Calendar | - |
| [err-notes](https://github.com/fernand0/err-notes) | Integración con apps de toma de notas | - |

### Utilidades y Servicios

| Plugin | Descripción | License |
|--------|-------------|---------|
| [err-weather](https://github.com/fernand0/err-weather) | Consulta del tiempo vía OpenWeatherMap | GPL-3.0 |
| [err-camera](https://github.com/fernand0/err-camera) | Toma fotos con webcam vía XMPP | Apache-2.0 |
| [err-home](https://github.com/fernand0/err-home) | Gestión de dispositivos domésticos | GPL-3.0 |
| [err-sensors](https://github.com/fernand0/err-sensors) | Lectura de sensores en Raspberry Pi | GPL-3.0 |

### Instalación

```bash
cd /path/to/errbot/plugins
git clone https://github.com/fernand0/<nombre-plugin>.git
cd <nombre-plugin>
pip install -r requirements.txt
```

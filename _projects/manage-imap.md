---
layout: project
title: manage-imap
description: Gestiona buzones IMAP con sistema de filtrado basado en reglas
image: /assets/img/slider/slide1.jpg
order: 9
---

Herramienta CLI para gestionar y organizar buzones IMAP usando un sistema de filtrado basado en reglas.

## Características

- **Interfaz de Menú Interactivo**: Navegación fácil mediante menús
- **Sistema de Reglas**: Filtrado de emails basado en reglas personalizables
- **Gestión de Carpetas IMAP**: Navegación entre carpetas
- **Organización de Emails**: Mueve emails entre carpetas automáticamente
- **Limpieza de Buzón**: Elimina emails marcados para borrado

## Menú Principal

| Opción | Descripción |
|--------|-------------|
| Purge deleted mails | Eliminar emails marcados para borrado |
| Move mail | Mover email a otra carpeta y crear regla |
| Change current folder | Cambiar de carpeta IMAP |
| List unread messages | Mostrar mensajes no leídos |
| Rules Management | Gestionar reglas de filtrado |

## Instalación

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install .
```

## Uso

```bash
python manage_imap.py
```

## ⚠️ Disclaimer

La lógica del motor de reglas fue migrada desde un programa legacy y **no ha sido formalmente testeada**. Usar con precaución.

## Código

Disponible en [manage-imap en GitHub](https://github.com/fernand0/manage-imap)

Licencia: MIT

## Relaciones

Puede utilizarse junto con [manage-agenda](manage-agenda) para organizar emails antes de extraer eventos

---
layout: project
title: vimblog.vim
description: Plugin de Vim para gestionar blogs. El proyecto que me motivó a crear mi cuenta de GitHub
image: /assets/img/slider/slide1.jpg
order: 11
featured: true
---

Plugin de Vim que permite gestionar posts de blog directamente desde el editor.

## Historia Personal

**Este proyecto fue el que me motivó a crear mi cuenta de GitHub.**

Descubrí vimblog.vim cuando buscaba una forma de gestionar mi blog sin salir de Vim. La simplicidad y elegancia de esta solución me inspiró a comenzar mi propio viaje en el mundo del desarrollo open source.

## Descripción

Para usuarios de Vi, Vim o GVim, hay una forma sencilla de gestionar tus posts de blog. Puedes crear nuevos posts, editar, listar categorías, listar posts antiguos, eliminar posts, y convertir entre Publicado y Borrador.

## Características

- Crear nuevos posts
- Editar posts existentes
- Listar todas las categorías
- Listar posts antiguos
- Eliminar posts
- Toggle Published/Draft
- Soporte WordPress out-of-the-box
- Extensible a Blogger, MovableType, TextPattern

## Requisitos

- VIM compilado con soporte Ruby (`sudo apt-get install vim-ruby`)
- Copiar `vimblog.vim` a tu carpeta `.vim`
- Añadir runtime code a tu `.vimrc`
- Configurar credenciales del blog

## Instalación

```bash
git clone https://github.com/fernand0/vimblog.vim.git
cd vimblog.vim
cp vimblog.vim ~/.vim/plugin/
```

## Código

Disponible en [vimblog.vim en GitHub](https://github.com/fernand0/vimblog.vim)

Licencia: MIT (Copyright © 2007 Pedro MG)

Fork del proyecto original de [pedromg/vimblog.vim](https://github.com/pedromg/vimblog.vim)

## Más Información

[blog.tquadrado.com/vimblog](http://blog.tquadrado.com/?page_id=146) - Documentación original

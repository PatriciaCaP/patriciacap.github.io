---
title: Cómo crear un sitio web con Jekyll y Github Pages
author: Patricia Casas
date: 2023-01-01 11:33:00 +0800
categories: [Blogging, Tutorial]
tags: [Github Pages]
math: true
mermaid: true
---
![Desktop View](/assets/img/title-image.jpg)
## Cómo crear un sitio web con Jekyll y Github Pages

[**GitHub Pages**](https://pages.github.com/) es un servicio que permite a los usuarios de GitHub alojar sitios web estáticos. [**Jekyll**](https://jekyllrb.com/) es un generador de sitios web estáticos que utiliza Markdown y otras plantillas para crear páginas web. Juntos, estos dos servicios proporcionan una plataforma fácil de usar y gratuita para alojar un sitio web personal o profesional.

En esta guía, aprenderás a crear un sitio web con Jekyll y GitHub Pages en unos pocos pasos simples.

<h2 data-toc-skip>Paso 1: Crea un nuevo repositorio en GitHub</h2>

Lo primero que debes hacer es crear un nuevo repositorio en GitHub. Para ello, ve a tu cuenta de GitHub y haz clic en el botón "New" en la esquina superior derecha de la pantalla. Dale un nombre a tu repositorio y haz clic en "Create repository".

<h2 data-toc-skip>Paso 2: Configura tu repositorio para que sea una página de GitHub</h2>

Una vez que hayas creado tu repositorio, debes configurarlo para que sea una página de GitHub. Puedes hacer esto en la pestaña "Settings" de tu repositorio. Desplázate hacia abajo hasta la sección "GitHub Pages" y selecciona "master branch" (o la rama que prefieras) como fuente del sitio.

<h2 data-toc-skip>Paso 3: Descarga o clona el repositorio en tu ordenador</h2>

Descarga o clona el repositorio en tu ordenador. Puedes hacer esto desde la línea de comandos o utilizando la herramienta GitHub Desktop.


<h2 data-toc-skip>Paso 4: Crea un archivo Gemfile en la raíz del proyecto</h2>

Crea un archivo `Gemfile` en la raíz del proyecto. Este archivo especifica las dependencias de Ruby que Jekyll necesita para ejecutarse. Asegúrate de tener instalado Ruby en tu ordenador. El contenido del archivo Gemfile puede ser el siguiente:

```bash
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plu
```

<h2 data-toc-skip>Paso 5: Ejecuta bundle install para instalar las dependencias de Ruby</h2>

Ejecuta `bundle install` en la línea de comandos para instalar las dependencias de Ruby que especificaste en el archivo `Gemfile`.


<h2 data-toc-skip>Paso 6: Crea un archivo de configuración para Jekyll</h2>

Crea un archivo de configuración para Jekyll en la raíz del proyecto. Puedes hacer esto creando un archivo llamado `_config.yml`. El contenido del archivo puede ser el siguiente:

```
title: Mi sitio web
description: Descripción de mi sitio web
theme: jekyll-theme-cayman

```

<h2 data-toc-skip>Paso 7: Crea una página de inicio para tu sitio web</h2>

Crea una página de inicio para tu sitio web. Puedes hacer esto creando un archivo llamado `index.md` en la carpeta raíz del proyecto. El contenido del archivo puede ser el siguiente:

```bash
---
layout: default
---

# Bienvenidos a mi sitio web

¡Hola a todos! Este es mi sitio web creado con Jekyll y GitHub Pages.
```

<h2 data-toc-skip>Paso 8: Agrega y haz un commit de los cambios en tu repositorio</h2>

Agrega y haz un commit de los cambios en tu repositorio:

```bash
$ git add .
$ git commit -m "Agrega archivo de configuración de Jekyll y página de inicio"
$ git push origin master
```
Espera unos minutos a que GitHub procese los cambios y cree el sitio web. Puedes acceder a la página de inicio de tu sitio web visitando la URL `[index.md](https://tu-nombre-de-usuario.github.io/nombre-del-repositorio.)`

## Video

{% include embed/youtube.html id='sLTNgxxSBR4' %}


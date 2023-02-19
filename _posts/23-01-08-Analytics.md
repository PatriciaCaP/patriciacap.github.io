---
title: Cómo crear una cuenta de Google Analytics y enlazarla con tu sitio web en GitHub Pages con Jekyll
author: true
date: 2023-01-08 11:33:00 +0800
categories: [Blogging, Tutorial]
tags: [google analitycs]

---
![Desktop View](/assets/img/google-analytics-logo.png)

Google Analytics es una herramienta gratuita de seguimiento de estadísticas que te permite obtener información sobre el tráfico de tu sitio web. En este tutorial, aprenderás cómo crear una cuenta de Google Analytics y enlazarla con tu sitio web en GitHub Pages con Jekyll.

##  Cómo crear una cuenta de Google Analytics y enlazarla con tu sitio web en GitHub Pages con Jekyll

<h2 data-toc-skip>Paso 1: Crear una cuenta de Google Analytics</h2>

Si aún no tienes una cuenta de Google Analytics, ve a  [**Google Analytics**](https://analytics.google.com/analytics/web/provision/#/provision) y crea una cuenta. Si ya tienes una cuenta, inicia sesión.

<h2 data-toc-skip>Paso 2: Crea un ID de seguimiento</h2>

Una vez que hayas iniciado sesión en tu cuenta de Google Analytics, crea un nuevo ID de seguimiento para tu sitio web. Para hacer esto, sigue estos pasos:

1. Haz clic en el botón "Administrar" en la parte inferior izquierda de la pantalla

2. Selecciona la cuenta en la que deseas agregar el ID de seguimiento.

3. Haz clic en "Crear una propiedad" y sigue las instrucciones para agregar la información de tu sitio web.

4. Copia el ID de seguimiento que se te proporciona.

<h2 data-toc-skip>Paso 3: Agrega el ID de seguimiento a tu sitio we</h2>

Abre tu proyecto de sitio web en Jekyll. Abre el archivo`_config.yml` y agrega lo siguiente en la parte superior del archivo:

```
google_analytics: TU-ID-DE-SEGUIMIENTO-DE-GOOGLE-ANALYTICS

```
<h2 data-toc-skip>Paso 4: Comprueba que tu sitio web está enlazado</h2>

Guarda los cambios en `_config.yml`l y luego genera tu sitio web Jekyll. Abre tu sitio web en el navegador y asegúrate de que la barra de estado en la parte inferior de la ventana del navegador muestre el nombre de tu sitio web y el ID de seguimiento de Google Analytics.


<h2 data-toc-skip>Paso 5: Verifica los datos de seguimiento en Google Analytics</h2>

Después de esperar unas horas o un día, regresa a tu cuenta de Google Analytics y asegúrate de que los datos de seguimiento se estén registrando correctamente. Si todo se configuró correctamente, verás información sobre el tráfico en tu sitio web.

## Mi Google Analytics

![Desktop View](/assets/img/Screenshot_5.png)

![Desktop View](/assets/img/Screenshot_6.png)

## Aprende más

Para mas información sobre Google Analytics, visita  [Analytics Academy](https://analytics.google.com/analytics/academy/course/6).

------------------
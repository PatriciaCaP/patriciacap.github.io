---
title: Cómo configurar la paginación para tus publicaciones en Github Pages
author: Patricia Casas
date: 2023-02-09 11:33:00 +0800
categories: [Blogging, Tutorial]
tags: [pagination]
math: true
mermaid: true
comments: true

---

## configurar la paginación para tus publicaciones en Github Pages

<h2 data-toc-skip>Paso 1:  Crear una variable paginate en _config.yml</h2>

En primer lugar, debes crear una variable paginate `paginate` en el archivo `_config.yml` de tu sitio. Esta variable indica cuántas publicaciones deseas mostrar en cada página.

Aquí tienes un ejemplo de cómo se vería la variable en `_config.yml`:

```
paginate: 10

```
En este ejemplo, se mostrarían 10 publicaciones por página.




{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://https-patriciacap-github-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
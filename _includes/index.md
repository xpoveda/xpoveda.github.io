xpoveda.github.io
=================

## Introducción

En esta web utilizamos conjuntamente [Bootstrap](http://getbootstrap.com/) y [Jekyll](https://jekyllrb.com/) como motor de renderizado de página.

Con Bootstrap nuestra web puede ser responsive y dotarla de gran funcionalidad con los css y js y nos proporciona.

Con Jekyll podemos escribir directamente parte del contenido de nuestra página en [Markdown](https://daringfireball.net/projects/markdown/), cosa que simplifica el trabajo de escritura
y nos proporciona la información de forma muy clara.

Hemos importado de otro proyecto un `markdown.css` para poder renderizar las páginas de la forma mas "bonita" posible.
No es posible utilizar directamente los css que utiliza Github ya que entran en conflicto con los de Bootstrap.

Puedes ver un [ejemplo de renderizado directo con markdown](https://xpoveda.github.io/articulo1) en otra de las páginas de esta web.

## Como es la estructura de esta página

El código seria el siguiente:
```bash
ubuntu@ubuntu:~/misproyectos/xpoveda.github.io$ tree
.
├── index.html
├── articulo1.html
├── _config.yml
├── _includes
│   ├── articulo1.md
│   └── index.md
├── _layouts
│   └── default.html
├── css
│   └── markdown.css
└── git_sube.sh
```

---

*Nota 1, Si quieres más información la puedes encontrar en:*

[Smashing magazine - Build blog jekyll github pages](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)

*Nota 2, Recuerda borrar cache de navegador si realizas alguna modificación por Github pages tiene problemas de refresco*

*Nota 3, En "Settings" del repo de github podrás ver si se ha producido algún error al compilarse las páginas Jekyll*

---

![octojekyll-opt](https://user-images.githubusercontent.com/13355927/30377816-736912b2-9891-11e7-8690-2b3113ebaef2.jpg)


xpoveda.github.io
=================

En esta página utilizamos bootstrap como estructura de página así como el motor de plantillas jekill.
Aprovechamos jekill para poder escribir directamente nuestras páginas en markdown, aunque tambien se podrian escribir directamente en html.
Hemos importado de otro proyecto un markdown.css para poder renderizar las páginas de la forma mas "bonita" posible.
No es posible utilizar directamente los css que utiliza github ya que entran en conflicto con los de bootstrap.

[Aquí](https://xpoveda.github.io/articulo1) puedes ver un ejemplo de renderizado directo con markdown.

El código seria el siguiente:
```bash
ubuntu@ubuntu:~/misproyectos/xpoveda.github.io$ tree
.
├── articulo1.html
├── _config.yml
├── css
│   ├── github-markdown.css
│   ├── main.css
│   └── markdown.css
├── git_sube.sh
├── _includes
│   ├── articulo1.md
│   └── index.md
├── index.html
├── _layouts
│   └── default.html
└── traspasa.sh
```

---

*Si quieres más información la puedes encontrar en:*
[Smashing magazine - Build blog jekyll github pages](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)
---

![octojekyll-opt](https://user-images.githubusercontent.com/13355927/30377816-736912b2-9891-11e7-8690-2b3113ebaef2.jpg)

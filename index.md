### [Novedades](./) [Programa](programa)  [Prácticas](practicas)  [Docentes](docentes)  [Bibliografía](bibliografia)

## Novedades

{% for post in site.posts %}
### {{ post.title }}
   
{{ post.date | date: "%Y-%m-%d" }}
{{ post.excerpt }}
[Leer más]({{ post.url | prepend: site.baseurl }})
{% endfor %}

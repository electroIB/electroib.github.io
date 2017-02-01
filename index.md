### [Novedades](./) [Programa](programa)  [Prácticas](practicas)  [Docentes](docentes)  [Bibliografía](bibliografia)

## Novedades

{% for post in site.posts %}
### {{ post.date | date: "%d-%m-%Y" }} {{ post.title }} 
{{ post.excerpt }}
[Leer más]({{ post.url | prepend: site.baseurl }})
{% endfor %}

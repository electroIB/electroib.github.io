### [Novedades](./) [Programa](programa)  [Prácticas](practicas)  [Docentes](docentes)  [Bibliografía](bibliografia)

{% for post in site.posts %}
## {{ post.title }}
   
{{ post.date | date: "%Y-%m-%d" }}
{{ post.excerpt }}
[READ MORE]({{ post.url | prepend: site.baseurl }})
{% endfor %}

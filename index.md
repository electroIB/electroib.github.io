### [Programa](programa) [Prácticas](practicas)[Docentes](docentes)[Bibliografía](bibliografia)

# Bienvenidos!

{% for post in site.posts %}
## {{ post.title }}
   
{{ post.date | date: "%Y-%m-%d" }}
{{ post.excerpt }}
[READ MORE]({{ post.url | prepend: site.baseurl }})
{% endfor %}

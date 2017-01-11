# [Other](other) | [Contact](contact) | [About](about)

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/canteroe/hello-world/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

# Blog
{% for post in site.posts %}
    ## {{ post.title }}
    
    {{ post.date | date: "%Y-%m-%d" }}
    {{ post.excerpt }}
    [READ MORE]({{ post.url | prepend: site.baseurl }})
{% endfor %}

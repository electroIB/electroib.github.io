# [Other](other) | [Contact](contact) | [About](about)

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/canteroe/hello-world/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

<h1>Blog</h1>
{% for post in site.posts %}
    <h2>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
    <span><strong>{{ post.date | date: "%Y-%m-%d" }}</strong></span>
    {{ post.excerpt }}
    <p><a href="{{ post.url | prepend: site.baseurl }}">READ MORE</a></p>
{% endfor %}

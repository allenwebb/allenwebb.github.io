# Webb.fyi

Welcome to my blog.

## Pages

{% for page in site.pages %}
- [{{ page.title }}]({{ page.url }})
{% endfor %}

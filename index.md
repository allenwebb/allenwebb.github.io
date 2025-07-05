# Webb.fyi

Welcome to my blog.

## Pages

{% for page in site.pages %}
{%   if page.url == '/index.html' %}
{%     continue %}
{%   endif %}
- [{{ page.title }}]({{ page.url }})
{% endfor %}

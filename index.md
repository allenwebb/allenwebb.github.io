# Webb.fyi

Welcome to my blog.

## Pages

{% for page in site.pages %}
{%   if page.title == 'Webb.fyi' or page.title == '' %}
{%     continue %}
{%   endif %}
- [{{ page.title }}]({{ page.url }})
{% endfor %}

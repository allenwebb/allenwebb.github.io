# Webb.fyi

Welcome to my blog.

## Pages

{% liquid
   for page in site.pages
     if page.url == '/index.html'
       continue
     endif
%}
- [{{ page.title }}]({{ page.url }})
{% endfor %}

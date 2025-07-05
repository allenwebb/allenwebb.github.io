---
layout: page
title: Recipes
tags: index
blurb: Links to recipes I found manageable.
---

# Recipes

Note that some of these (especially the ones published by food companies) call
for specific brands of ingredients, but buying specific brands is not necessary.

- [(external) Green bean casserole](https://www.mccormick.com/blogs/frenchs-recipes/green-bean-casserole)
{% for page in site.tags["recipes"] %}
{%   if page.title == 'Webb.fyi' or page.title == '' %}
{%     continue %}
{%   endif %}
{%   if page.title and page.url and page.blurb %}
- [{{ page.title }}]({{ page.url }}): {{ page.blurb }}
{%   endif %}
{% endfor %}

---
layout: page
title: Recipes
tags: index
blurb: Links to recipes I found manageable.
---

# Recipes

Note that some of these (especially the ones published by food companies) call
for specific brands of ingredients, but buying specific brands is not necessary.

{% for page in site.tags["recipes"] %}
{%   if page.title == 'Webb.fyi' or page.title == '' %}
{%     continue %}
{%   endif %}
{%   if page.title and page.url and page.blurb %}
* [{{ page.title }}]({{ page.url }}): {{ page.blurb }}
{%   endif %}
{% endfor %}

## Vegetable Dishes

* [(external) Green bean casserole](https://www.mccormick.com/blogs/frenchs-recipes/green-bean-casserole): 4 main ingredients (or three if omitting the black pepper). This recipe is fairly low effort to prepare and it keeps well in the refrigerator.
* (TODO) Roasted vegetables (brussel sprouts, carrots)
* (TODO) Boiled vegetables (broccoli, carrots)

## Meat Recipes

* [(external) BBQ country style ribs](https://www.food.com/recipe/the-most-tender-country-style-honey-bbq-ribs-501742): The amount of ribs isn't super important and the additional spices and seasoning can be omitted so that it is just the barbecue sauce and ribs. Note that country style ribs aren't really ribs but are a cut of meat that mimics ribs.
* (TODO) Garlic brined pork chops
* (TODO) Instant pot pulled beef BBQ
* (TODO) Reverse searing steak

## Starches

* (TODO) Instant pot mashed potatoes
* (TODO) Instant pot rice

## Mixed Entres

* (TODO) Basic pasta
* (TODO) Pigs in a blanket
* (TODO) Breakfast Burritos
* (TODO) Shepherd's pie
* (TODO) Hatch green chile enchiladas
* (TODO) Nacho Cheese / Queso / Mac & Cheese
* (TODO) Grilled cheese sandwiches
* (TODO) Pasta Bake

## Desserts

* (TODO) Banana bread
* (TODO) Chocolate chip cookies
* (TODO) Ginger crinkles
* (TODO) Lime pie (without key limes)
* (TODO) Crepes
* (TODO) Dark Chocolate & Oat clusters
* (TODO) New york-style cheesecake with strawberry topping
* (TODO) Fudge

© 2025 Webb.fyi

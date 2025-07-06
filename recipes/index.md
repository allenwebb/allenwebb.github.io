---
layout: page
title: Recipes
tags: index
blurb: Links to recipes I found to be manageable.
---

# Recipes

Note that some of these (especially the ones published by food companies) call for specific brands of ingredients, but buying specific brands is not necessary. For me cooking is a balancing act between the effort required and how much I enjoy the outcome, so I tend to gravitate toward recipes that either aren't super involved or taste really good when they are done. This also means I tend to cut out some of the steps if they don't really add much in my opinion so I am more likely to make them again later.

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
* (TODO) Brussel sprouts
* (TODO) Boiled vegetables (broccoli, carrots)


## Meat Recipes



* [(external) BBQ country style ribs](https://www.food.com/recipe/the-most-tender-country-style-honey-bbq-ribs-501742): The amount of ribs isn't super important and the additional spices and seasoning can be omitted so that it is just the barbecue sauce and ribs. Note that country style ribs aren't really ribs but are a cut of meat that mimics ribs.
* (TODO) Garlic brined pork chops
* [(external) Instant pot pulled beef BBQ](https://www.simplyhappyfoodie.com/instant-pot-barbecue-beef/#wprm-recipe-container-4735): Much of this recipe can be omitted and different cuts of meat can be substituted. The primary parts are cutting the beef into small enough pieces to cook properly (these are actually fairly large pieces). Since the meat will be shredded after it is cooked, ideally the meat fibers are shorter to make shredding and eating easier. To do this, figure out the grain of the meat and cut it against the grain (to shorten the meat fibers with each cut).
* (TODO) Reverse searing steak


## Starches



* (TODO) Instant pot mashed potatoes
* (TODO) Instant pot rice


## Mixed Entrees



* (TODO) Basic pasta
* (TODO) Pigs in a blanket
* (TODO) Breakfast Burritos
* (TODO) Shepherd's pie
* (TODO) Hatch green chile enchiladas
* [(external) Nacho Cheese / Queso / Mac & Cheese](https://www.budgetbytes.com/5-minute-nacho-cheese-sauce/): I typically add a can of rotel tomatoes to turn this into queso. I have also directly put it on pasta noodles to make mac and cheese before which worked out well.
* (TODO) Grilled cheese sandwiches
* (TODO) Pasta Bake


## Desserts



* [(external) Banana bread](https://itsbellmade.com/recipe-easy-banana-bread/): I normally try to double this recipe since it leaves the oven running for about an hour and adding an extra loaf doesn't noticeably impact the prep and cooking time.
* [(external) Chocolate chip cookies](https://www.nestle.com/stories/timeless-discovery-toll-house-chocolate-chip-cookie-recipe): This is the Nestle recipe.
* (TODO) Ginger crinkles
* [(external) Lime pie (without key limes)](https://www.onceuponachef.com/recipes/key-lime-pie.html): I omitted the whipped topping when I made this recipe and it was still really good.
* [(external) Crepes](https://www.allrecipes.com/recipe/19037/dessert-crepes/): I often get whipped cream and some kind of berries to serve with this, but Nutella and or chocolate ships are also a good option.
* [(external) Dark Chocolate & Oat clusters](https://recipes.sparkpeople.com/recipe-detail.asp?recipe=1979205): I found the batch size of this recipe to be way too small so I normally up it to
    * 1 cup of peanut butter,
    * 1 cup of milk
    * 1 12oz bag of chocolate chips
    * 3 cups of rolled oats

    I also tend to make larger bars and spread them on wax paper over a baking sheet with edges to catch any debris.

* [(external) New york-style cheesecake with strawberry topping](https://groups.io/g/strawpinerecipes/topic/new_york_style_cheesecake/1792758): The original source of this recipe was updated to something different so the link is to a copy of the original version.
* (TODO) Fudge

© 2025 Webb.fyi

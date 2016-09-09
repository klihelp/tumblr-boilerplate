tumblr-boilerplate
==================

A clean starter theme to build yours. This boilerplate is designed so it becomes easy to create a new working theme for a Tumblr blog.

# Ressources

+ [Tumblr custom theme documentation](https://www.tumblr.com/docs/en/custom_themes)

# Features

+ All Tumblr post types supported (Text, Images, Audio...)
+ basic layout variables (colors, font, cover image)
+ [SUIT CSS naming convention](https://github.com/suitcss/suit/blob/master/doc/naming-conventions.md)
+ [Normalize.css](https://necolas.github.io/normalize.css/)
+ JavaScript / jQuery prototype setup

# Optional features

Those are already setup but can easily be activated/deactivated
+ [infinite-scroll](https://github.com/infinite-scroll/infinite-scroll) (optional)
+ [Masonry.js](http://desandro.github.io/masonry/) easy setup (optional)
+ [Disqus](https://disqus.com/admin/tumblr/), for comments (optional)
+ [Google Analytics](http://www.google.com/analytics/) (optional)

# Getting started

To use the theme you will have to:

1. create a blog with any theme
2. go to its [customize page](http://www.tumblr.com/customize)
3. click on 'Edit HTML' link beneath the title
4. replace all markup with the one from this project's [`index.html`](https://raw.githubusercontent.com/hugovieilledent/tumblr-boilerplate/master/index.html).
5. Save it

That's it! You now have a beautiful, functional base to build whatever you want.

## Infinite scrolling

Infinite scrolling is activated by default. To deactivate it you have to change one line in the JavaScript found at the bottom of `index.html`. Comment out the 'this.infiniteScrolling();' line in the `init` method.

## Masonry

To deactivate Masonry, toggle off the switch `Grid Layout` on the customize page of your blog (not the markup, but the registered variables before clicking "edit HTML")

## Google Analytics

Go the [customize page](http://www.tumblr.com/customize) of your blog and fill in your website's `Google analytics ID`.

## Disqus

Go the [customize page](http://www.tumblr.com/customize) of your blog and fill in your [Disqus Shortname](https://disqus.com/admin/signup/?utm_source=New-Site).

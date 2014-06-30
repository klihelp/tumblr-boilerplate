tumblr-boilerplate
==================

A clean starter theme.

# Features

+ Contemporary HTML5 markup
+ Basic tumblr variables
+ [Normalize.css](https://necolas.github.io/normalize.css/)
+ Infinite scrolling (optional)
+ Easy Google Analytics (optional)
+ Masonry.js easy setup (optional)
+ Support for comments with Disqus
+ JavaScript / jQuery prototype setup
+ [Naming convention from Suit CSS](https://github.com/suitcss/suit/blob/master/doc/naming-conventions.md)

# Files

+ Index.html

# Getting started

To use the theme you will have to customize any (free) theme. Go to the [Customize page](http://www.tumblr.com/customize), choose any (free) theme and use it. There will be an 'Edit HTML' link beneath the title.

You have to replace all the HTML with the raw content of [`index.html`](https://raw.githubusercontent.com/hugovieilledent/tumblr-boilerplate/master/index.html).

Save it and that's it! You now have a beautiful, functional base to build whatever you want.

# Theme Options: customisation for the final user

By including special meta tags in your theme, users can easily tweak features as colors, custom texts, fonts etc. on the [customize page](http://www.tumblr.com/customize). If you want to know more, please see the [Tumblr theme options](http://www.tumblr.com/docs/en/custom_themes#theme-options).

## Customize colors

+ Background color
+ Text color

## Customize elements

+ Show and hide the footer
+ Show and hide the social sharing features: Tumblr (like and reblog), Facebook, Twitter

## Infinite scrolling

Infinite scrolling is activated by default. To deactivate it you have to change one line in the JavaScript found at the bottom of `index.html`. Comment out the 'this.infiniteScrolling();' line in the `init` method.

## Masonry

To activate Masonry you only have to add the class `is-grid` to the `body` element. To only have masonry on the index page, you should add this code as class to the body `{block:IndexPage}is-grid{/block:IndexPage}`

## Google Analytics

Go the [customize page](http://www.tumblr.com/customize) of your blog and fill in your website's `Google analytics ID`.

## Disqus

Go the [customize page](http://www.tumblr.com/customize) of your blog and fill in your [Disqus Shortname](https://disqus.com/admin/signup/?utm_source=New-Site).

# Browser support

+ Internet Explorer > 8 (doesn't support HTML5 elements, among other things)
+ All the rest

# To-do

+ [https://schema.org](https://schema.org)
+ Microformats

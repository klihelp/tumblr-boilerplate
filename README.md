tumblr-boilerplate
==================

tumblr boilerplate - clean starter theme

# Features

+ contemporary HTML5 markup
+ javascript / jquery prototype setup
+ masonry.js + infite scrolling setup
+ basic tumblr variables
+ google analytics setup
+ disqus setup
+ [normalize.css](https://necolas.github.io/normalize.css/)


# Files

+ index.html 
+ normalize.css


# Get started

+ copy paste the content from index.html to your tumblr blog by going on the customize page and replacing the whole content
+ upload [normalize.css](https://necolas.github.io/normalize.css/) to your assets
+ add your own css, inside the `<style>` tags or by using the `<link rel="stylesheet" href="link_to_normalize_asset">` and replacing the value of `href` by the url to the `style.css` file you uploaded to the assets.
+ save


# Theme Options: customisation for the final user 

By including special meta tags in your theme, users can easily tweak some features using the [Customize page](http://www.tumblr.com/customize). It can be colors, custom texts, fonts etc.
If you want to know more about Tumblr "Theme Options" you should read their [documentation](http://www.tumblr.com/docs/en/custom_themes#theme-options)

## Customize colors

+ Background color
+ Text color

## Customize elements

+ Show and hide the footer
+ Show and hide the social sharing features: Tumblr (like and reblog), Facebook, Twitter


# Built-in pluggins and services

Infite scrolling and Masonry are the two build-in pluggins of this starter theme. They work well together, Infinte scrolling is activated by default, Masonry is not. You can choose to desactivate one of them or both.

Google Analytics and Discus are the two build-in services of this starter theme.

## Infinite scrolling

Infinite scrolling is activated by default.
If you want to desactivate it, find the javascript at the bottom of the page and comment out the 'this.infiniteScrolling();' line in the `init` method.

## Masonry

Masonry is desactivated by default.
In order to activate masonry you have to add the class `is-grid` to the `body`.
If you want Masonry to be activated only on the index page you should add this code as class to the body `{block:IndexPage}is-grid{/block:IndexPage}`

## Google Analytics

Go the [Customize page](http://www.tumblr.com/customize) of your blog and fill in your website's `Google analytics ID`

## Discus
Go the [Customize page](http://www.tumblr.com/customize) of your blog and fill in your [Disqus Shortname](https://disqus.com/admin/signup/?utm_source=New-Site)


# Browser support

+ All browsers
+ Internet Explorer > 8, some html5 semantic markup used here is not supported

# todo

+ microformats
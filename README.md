# [![Web Starter Kit](https://cloud.githubusercontent.com/assets/170270/3343034/ceef6e92-f899-11e3-96b9-5d9d69d97a00.png)](https://github.com/google/web-starter-kit/releases)


## Overview

[Web Starter Kit](http://developers.google.com/web/starter-kit) is a starting point for multi-screen web development. It encompasses opinionated recommendations on boilerplate and tooling for building an experience that works great across multiple devices. We help you stay productive and aligned with the best practices outlined in Google's [Web Fundamentals](http://developers.google.com/web/fundamentals).

[![](https://cloud.githubusercontent.com/assets/170270/3343033/ceee251e-f899-11e3-9dd9-e313cf2522ec.png)](https://developers.google.com/web/starter-kit/ 'Features')


## Quickstart

[Download](https://github.com/google/web-starter-kit/releases) the kit or clone this repository and build on what we include in the `app` directory.

We provide 2 HTML starting points, from which you can choose:

- `index.html` - the default starting point, containing layout and a slide-out menu
- `basic.html` - includes no layout

## Tooling

If you would like to use the optional tooling we provide, make sure your system has [Node.js](http://nodejs.org), [Ruby](https://www.ruby-lang.org/), [gulp.js](http://gulpjs.com) and [Sass](http://sass-lang.com/install) installed.

### Node

Let's check to see if you already have Node installed. Bring up a terminal and type `node --version`. If Node responds, and if it shows a version at or above v0.10.x, proceed to checking if you have Ruby installed too. If you require Node, go to [nodejs.org](http://nodejs.org/) and click on the big green Install button.

### Ruby

Bring up a terminal and type `ruby --version`. If Ruby responds, and if it shows a version number at or above 1.8.7 then type `gem --version`. If you don't see any errors, proceed to installing the Sass gem. If you require Ruby, it can be installed from the [Ruby downloads](https://www.ruby-lang.org/en/downloads/) page.

### Sass

Bring up a terminal and type `sass --version`. If Sass is installed it should return a version number at or above 3.3.x. If you don't see any errors, proceed to the Gulp installation. If you need to install Sass, see the command-line instructions on the [Sass installation](http://sass-lang.com/install) page.

### Gulp

Bring up a terminal and type `gulp --version`. If Gulp is installed it should return a version number at or above 3.5.x. If you don't see any errors, proceed to the Gulp commands section. If you need to install Gulp, open up a terminal and type in the following:

```sh
$ npm install --global gulp
```

This will install Gulp globally. Depending on your user account, you may need to gain elevated permissions using `sudo` (i.e `sudo npm install --global gulp`). Next, install the local dependencies Web Starter Kit requires:

```sh
$ npm install
```

That's it! You should now have everything needed to use the Gulp tools in Web Starter Kit.

### Gulp Commands

You can now use Gulp with the following commands to stay productive during development:

#### Watch For Changes & Automatically Refresh Across Devices

```sh
$ gulp serve
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

### Build & Optimize

```sh
$ gulp
```

Build and optimize the current project, ready for deployment. This includes linting as well as image, script, stylesheet and HTML optimization and minification.

#### Performance Insights

```sh
$ gulp pagespeed
```

Runs the deployed (public) version of your site against the [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) API to help you stay on top of where you can improve.

## Web Performance

Web Starter Kit strives to give you a high performance starting point out of the box and we actively work on delivering the best [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) score and frame-rate possible.

In terms of CSS, opting to just use the minimal layout (main.css, h5bp.css) weighs in at ~7KB before modifications are made. Opting to use the Style Guide styles (the default) will take this up to ~39KB. It is your choice which path makes the most sense for your project, however notes on excluding Style Guide styles are in our gulpfile.

## Browser Support

At present, we officially aim to support the following browsers:

* IE10, IE11, IE Mobile 10
* FF 30, 31
* Chrome 34, 35
* Safari 7, 8
* Opera 23, 24
* iOS Safari 7, 8
* Opera Coast
* Android / Chrome 4.4, 4.4.3
* BlackBerry 10

This is not to say that Web Starter Kit cannot be used in browsers older than those reflected, but merely that our focus will be on ensuring our layouts work great in the above.

## Troubleshooting

If you find yourself running into issues during installation or running the tools, please check our [Troubleshooting](https://github.com/google/web-starter-kit/wiki/Troubleshooting) guide and then open an [issue](https://github.com/google/web-starter-kit/issues). We would be happy to discuss how they can be solved.

## A Boilerplate-only Option

If you would prefer not to use any of our tooling, delete the following files from the project: `package.json`, `gulpfile.js`, `.jshintrc` and `.travis.yml`. You can now safely use the boilerplate with an alternative build-system or no build-system at all if you choose.

## Inspiration

Web Starter Kit is inspired by [Mobile HTML5 Boilerplate](http://html5boilerplate.com/mobile/) and Yeoman's [generator-gulp-webapp](https://github.com/yeoman/generator-gulp-webapp), having taken input from contributors to both projects during development. Our [FAQs](https://github.com/google/web-starter-kit/wiki/FAQ) attempt to answer commonly asked questions about the project.

## Contributing

Contributions, questions and comments are all welcome and encouraged. For code contributions to Web Starter Kit, please see our [Contribution guide](CONTRIBUTING.md) before submitting a pull request. [Website](https://developers.google.com/web/starter-kit/) related issues should be filed on the [Web Fundamentals](https://github.com/google/WebFundamentals/issues/new) issue tracker.

## License

Apache 2.0  
Copyright 2014 Google Inc


# So Simple Theme

Looking for a simple, responsive, theme for your Jekyll powered blog? Well look no further. Here be **So Simple Theme**, the followup to [**Minimal Mistakes**](http://mmistakes.github.io/minimal-mistakes/) -- by designer slash illustrator [Michael Rose](http://mademistakes.com).

## So Simple Theme is all about:

* Responsive templates. Looking good on mobile, tablet, and desktop.
* Readable typography to make your words shine.
* Gracefully degrading in older browsers. Compatible with Internet Explorer 9+ and all modern browsers.
* Minimal embellishments and subtle animations.
* Support for large images to call out your favorite posts.
* Disqus comments if you choose to enable.
* Tags for [Open Graph](https://developers.facebook.com/docs/opengraph/) and [Twitter Cards](https://dev.twitter.com/docs/cards) for a better social sharing experience.
* Vanilla [custom 404 page]({{ site.url }}/404.html) to get you started.
* Stylesheets for Pygments and Coderay [syntax highlighting](http://mmistakes.github.io/articles/so-simple-theme/code-highlighting-post/) to make your code examples look snazzy.
* Simple search that overlays results based on post title.
* Grunt build script for easier theme development.
* [Sitemap](https://github.com/mmistakes/so-simple-theme/blob/master/sitemap.xml) for search engines

![screenshot of So Simple Theme](http://mmistakes.github.io/so-simple-theme/images/so-simple-theme-preview.jpg)

General notes and suggestions for customizing So Simple Theme.

---

## Basic Setup for new Jekyll site

1. [Install Bundler](http://bundler.io) `gem install bundler` and then install [Jekyll](http://jekyllrb.com) and all dependencies `bundle install`.
2. Fork the [So Simple Theme repo](https://github.com/mmistakes/so-simple-theme/fork).
3. Clone the repo you just forked and rename it.
4. Edit `_config.yml` to personalize your site.
5. Check out the sample posts in `_posts` to see examples for pulling in large feature images, assigning categories and tags, and other YAML data.
6. Read the documentation below for further customization pointers and documentation.

[Demo the Theme](http://mmistakes.github.io/so-simple-theme/)

**Pro-tip:** Remove the sample posts in `_posts` and the `gh-pages` branch after cloning. There is a bunch of garbage in the `gh-pages` branch used for the theme's demo site.

---

## Setup for Existing Jekyll site

1. Clone the following folders: `_includes`, `_layouts`, `assets`, and `images`.
2. Clone the following files and personalize content as need: `about.md`, `articles.html`, `index.html`, `tags.html`, `feed.xml`, and `sitemap.xml`.
3. Set the following variables in your `config.yml` file:

``` yaml
title:            Site Title
description:      Site description for the metas.
logo:             site-logo.png
disqus_shortname: shortname
search:           true
# Your site's domain goes here. When working locally use localhost server leave blank
# PS. If you set this wrong stylesheets and scripts won't load and most links will break.
# PPS. If you leave it blank for local testing home links won't work, they'll be fine for live domains though.
url:              http://localhost:4000

# Owner/author information
owner:
  name:           Your Name
  avatar:         your-photo.jpg
  email:          your@email.com
  # Social networking links used in footer. Update and remove as you like.
  twitter:
  facebook:
  github:
  linkedin:
  instagram:
  tumblr:
  # For Google Authorship https://plus.google.com/authorship
  google_plus:    "http://plus.google.com/123123123123132123"

# Analytics and webmaster tools stuff goes here
google_analytics:
google_verify:
# https://ssl.bing.com/webmaster/configure/verify/ownership Option 2 content= goes here
bing_verify:

# Links to include in top navigation
# For external links add external: true
links:
  - title: About
    url: /about
  - title: Articles
    url: /articles
  - title: Google
    url: http://google.com
    external: true

# http://en.wikipedia.org/wiki/List_of_tz_database_time_zones
timezone:    America/New_York
pygments:    true
markdown:    kramdown

# https://github.com/mojombo/jekyll/wiki/Permalinks
permalink:   /:categories/:title/
```

---

## Folder Structure

``` bash
so-simple-theme/
├── _includes/
|    ├── browser-upgrade.html  #prompt to upgrade browser on < IE8
|    ├── footer.html  #site footer
|    ├── head.html  #site head
|    ├── navigation.html #site navigation and masthead
|    └── scripts.html  #jQuery, plugins, GA, etc.
├── _layouts/
|    ├── page.html  #page layout
|    └── post.html  #post layout
├── _posts/
├── assets/
|    ├── css/  #preprocessed less styles
|    ├── fonts/  #icon webfonts
|    ├── js/
|    |   ├── _main.js  #main JavaScript file, plugin settings, etc
|    |   ├── plugins  #jQuery plugins
|    |   └── vendor/  #jQuery and Modernizr
|    └── less/
├── images  #images for posts and pages
├── _config.yml  #Jekyll site options
├── about.md  #about page
├── articles.html  #lists all posts from latest to oldest
├── index.html  #homepage. lists 10 latest posts
├── tags.html  #lists all posts sorted by tag
└── sitemap.xml  #autogenerated sitemap for search engines
```

---

## Customization

For full customization details and more information on the theme check out the [So Simple theme setup guide](http://mmistakes.github.io/so-simple-theme/theme-setup/).

---

## Questions?

Having a problem getting something to work or want to know why I setup something in a certain way? Ping me on Twitter [@mmistakes](http://twitter.com/mmistakes) or [file a GitHub Issue](https://github.com/mmistakes/so-simple-theme/issues/new).

---

## License

This theme is free and open source software, distributed under the [GNU General Public License](LICENSE) version 2 or later. So feel free to to modify this theme to suit your needs.

If you'd like to give me credit somewhere on your blog or tweet a shout out to [@mmistakes](https://twitter.com/mmistakes), that would be pretty sweet.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/mmistakes/so-simple-theme/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

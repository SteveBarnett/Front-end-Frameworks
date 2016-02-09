
# Front-end frameworks

Write your own. Find a site you look, and use your browser's Developer Tools to see what CSS was used.

Try and avoid using W3Schools as it is not the most reputable source, and has been known to contain incorrect or misleading information (despite appearing at the top of search results). Instead, use [Web Platform dot org](http://www.webplatform.org/). It's [backed by a lot of big names](https://www.webplatform.org/stewards/), including the World Wide Web Consortium (W3C) itself.

If you're looking for some small and specific, try searching on [CodePen](http://codepen.io/), but bear in mind that code there tends to be experimental.

There are [a lot of frameworks](http://usablica.github.io/front-end-frameworks/compare.html) or various sizes and for various use cases.

## Styles of writing CSS

* [SMACSS](https://smacss.com/) (Scalable and Modular Architecture for CSS)
* [OOCSS](http://oocss.org/) (Object-Oriented CSS)
* [BEM](https://en.bem.info/) (Block Element Modifier)

## Styles of writing JS

* [JSCS](http://jscs.info/) (JavaScript Code Style: enforcing a style guide)
* [JS Hint](http://jshint.com/) (detect errors and potential problems)

## Simple things / smaller helpers

### HTML

* [h5bp / HTML5 Boilerplate](https://html5boilerplate.com/).

### CSS

* [Normalise](https://necolas.github.io/normalize.css/). More consistent rendering, without using a reset.
* Just typography: [TypePlate](http://typeplate.com/)

## Grid systems

* [Ungrid](http://chrisnager.github.io/ungrid/)
* [Susy](http://susy.oddbird.net/) (needs Sass)

## Small CSS frameworks - need to split these up? What's Sass / Less?

* [Picnic CSS](http://www.picnicss.com/)
* [Bulma](http://bulma.io/)
* [Milligram](http://milligram.github.io/)
* [Corpus](http://corpuscss.com/)
* [Sky Blue](http://stanko.github.io/skyblue/)
* [Furtive](http://furtive.co/)
* [Basscss](http://www.basscss.com/)
* [Crumpet](http://suitedpixel.com/crumpet/)
* [Pure](http://purecss.io/)
* [Semantic UI](http://semantic-ui.com/)
* [Skeleton](http://getskeleton.com/)
*


## Pre-processors



## Mixin libraries

* [Bourbon](http://bourbon.io/) is a library of Sass mixins for things like vendor prefixes, typographic scale, animation. Pairs well with [Bourbon Neat for grids](http://neat.bourbon.io/).
* [Bitters](http://bitters.bourbon.io/) provides scaffolding for Bourbon projects, and [Refills](http://refills.bourbon.io/) helps build components and patterns for Bourbon and Neat projects.
* [Rucksack](http://simplaio.github.io/rucksack/)
* [Concise](http://concisecss.com/)

## Starter Kits / Boilerplates

[Google's Web Start Kit](https://developers.google.com/web/tools/starter-kit/) is full of modern front-end best practices, but makes a lot of assumptions: gulp, sass, concatenation and minification of CSS, concatenation and minification of JS, babel, browsersync, PageSpeed, Service Workers, npm.



## Full-on frameworks

You use these by adding a `<link>` for the CSS at the top, and a `<script>` for the JS at the bottom your HTML pages.

Twitter's [Bootstrap](http://getbootstrap.com/) is one of the most widely known and widely used HTML, CSS, and JS frameworks. It's easiest to use all of Bootstrap. When you try and use pieces, or try and add extra bits to it, things get tricky. That means that it can be a bit heavy, depending on your needs.

The other famous one is [Zurb's Foundation](http://foundation.zurb.com/). It has pretty much the same ups and down as Bootstrap.

Both of these are great for doing prototypes. They let you put things together very quickly. They're not necessarily the best choice for your production application, though.

A lighter alternative is [Material Design Lite](http://www.getmdl.io/).

There's also [Solid](http://solid.buzzfeed.com/).

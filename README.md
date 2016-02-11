
# Front-end frameworks

Taking an off-the-shelf front-end framework can greatly speed up your development time. Using them can come with a heavy cost, though. These frameworks are developed by teams to meet their needs at the time they built them. Their frameworks are built using their processes and are an expression of their opinions about the best ways to do things. These might not match yours. If they match yours now, they might not in a few months time.

Think about the cost of using a framework against the benefits it provides. Consider the cost to your users. Using a framework may add a lot of developer convenience, but does it improve the users' experience?

Prefer smaller frameworks, or ones that are modular. That way you can pick and choose the pieces that you want to use.

The best way to have a tool that works for you is to write your own. For small things, find a site you like, and use your browser's Developer Tools to see how they built it.

## Learning resources

Try and avoid using W3Schools as it is not the most reputable source, and has been known to contain incorrect or misleading information (despite appearing at the top of search results). Instead, use [Web Platform dot org](http://www.webplatform.org/). It's [backed by a lot of big names](https://www.webplatform.org/stewards/), including the World Wide Web Consortium (W3C) itself.

If you're looking for some small and specific, try searching on [CodePen](http://codepen.io/), but bear in mind that code there tends to be experimental.

There are [a lot of frameworks](http://usablica.github.io/front-end-frameworks/compare.html) of various sizes and for various use cases.

## Styles of writing code

When writing code, it can be helpful to have an agreed upon style. Where do spaces go, and how many? Do you line break after the bracket or before it? Having a code style guide means it's easier to work as a team, and with future you.

For CSS, the big ones are [SMACSS](https://smacss.com/) (Scalable and Modular Architecture for CSS); [OOCSS](http://oocss.org/) (Object-Oriented CSS); [BEM](https://en.bem.info/) (Block Element Modifier). Each is a different take on how to write classes and organise your CSS. There's no right or wrong way: just the way that makes sense to you and your team.

For JavaScript, there are two main things to do: run [JS Hint](http://jshint.com/) to detect errors and potential problems; run [JSCS](http://jscs.info/) to enforce a style guide.

## Boilerplates and helpers

A great starting point for a new web page is the [HTML5 Boilerplate](https://html5boilerplate.com/). Take some time to look through [the documentation](https://github.com/h5bp/html5-boilerplate/blob/5.3.0/dist/doc/TOC.md): every decision has solid reasoning behind, which they explain in detail.

A good CSS baseline to start from is [Normalise](https://necolas.github.io/normalize.css/). It gives you more consistent rendering across a variety of browsers without resetting everything to zero. If you're particularly interested in typography, have a look at [TypePlate](http://typeplate.com/).

## Grid systems

If you just want some help putting together a solid grid, you can use [Gridly](http://ionicabizau.github.io/gridly/example/), a minimal grid system.

If you use [Sass](http://sass-lang.com/), [Susy](http://susy.oddbird.net/) is very handy. It's a set of tools for creating powerful custom grid layouts.

## Small frameworks

[Milligram](http://milligram.github.io/) is a minimalist CSS framework. It's very light, but has few features. [Skeleton](http://getskeleton.com/) A dead simple, responsive boilerplate.

If you want something with a bit more, try [Bulma](http://bulma.io/) (has more character) or [Furtive](http://furtive.co/) (more opinionated, designed more as a starting point).

If you want to pick and choose what things you're going to use, checl out [Pure](http://purecss.io/). It's a set of small, responsive CSS modules.

If you need some JavaScript, check out [MicroJS](http://microjs.com/) and [You Might Not Need jQuery](http://youmightnotneedjquery.com/).

## Preprocessors

There are a couple of well-known preprocessors: [Sass](http://sass-lang.com/), [Less](http://lesscss.org/), and [Stylus](http://stylus-lang.com/).

They all have similar features, but Sass seems to be one of the most widely adopted. You don't have to use a preprocessor, but there are a couple of features that might make it worthwhile.

**Variables** are very handy, **Nesting** selectors makes for much better readability (but don't nest too deeply), better use of **Media Queries** (write them inside a selector, rather than in big blocks by themselves). **Partials** let you write your CSS in a modular way, but compile them into one file at the end. You can also set an option to minify the final file.


## Preprocessor mixin libraries

If you are using a preprocessor there are a couple of mixin libraries that could be useful.

* [Bourbon](http://bourbon.io/) is a library of Sass mixins for things like vendor prefixes, typographic scale, animation. Pairs well with [Bourbon Neat for grids](http://neat.bourbon.io/).
* [Bitters](http://bitters.bourbon.io/) provides scaffolding for Bourbon projects, and [Refills](http://refills.bourbon.io/) helps build components and patterns for Bourbon and Neat projects.
* [Rucksack](http://simplaio.github.io/rucksack/)
* [Concise](http://concisecss.com/)

## Starter Kits / Boilerplates

[Google's Web Start Kit](https://developers.google.com/web/tools/starter-kit/) is full of modern front-end best practices, but makes a lot of assumptions: gulp, sass, concatenation and minification of CSS, concatenation and minification of JS, babel, browsersync, PageSpeed, Service Workers, npm.

## Full-on frameworks

If you do decide to use a big, off-the-shelf, Front-end framework, you use them by adding the appropriate `<link>` for the CSS at the top, and `<script>` for the JS at the bottom your HTML pages.

Twitter's [Bootstrap](http://getbootstrap.com/) is one of the most widely known and widely used HTML, CSS, and JS frameworks. It's easiest to use all of Bootstrap, not pieces of it. When you try and use pieces, or try and add extra bits to it, things get tricky. It can be a bit heavy, depending on your needs.

The other famous one is [Zurb's Foundation](http://foundation.zurb.com/). It has pretty much the same ups and down as Bootstrap.

Both of these are great for doing prototypes: they let you put things together very quickly. They're not necessarily the best choice for your final application, though.

A slightly lighter alternative is [Material Design Lite](http://www.getmdl.io/), based on Google's Material Design.

Like Bootstrap and Foundation, it's quite opinionated about the visual design, and trying to stray from that will be difficult.

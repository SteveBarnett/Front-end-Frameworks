---
layout: default
title: Styles of writing code
---

## Styles of writing code

[![](img/smacss.png)](https://smacss.com/) [![](img/bem.png)](https://en.bem.info/) [![](img/maintainablecss.png)](http://maintainablecss.com/)

When writing code, it can be helpful to have an agreed upon style. Where do spaces go, and how many? Do you line break after the bracket or before it? Having a code style guide means it's easier to work as a team, and with future you.

For CSS, the big ones are [SMACSS](https://smacss.com/) (Scalable and Modular Architecture for CSS); [OOCSS](http://oocss.org/) (Object-Oriented CSS); [BEM](https://en.bem.info/) (Block Element Modifier). Each is a different take on how to write classes and organise your CSS. There's no right or wrong way: just the way that makes sense to you and your team. Along similar lines there's also [Maintainable CSS](http://maintainablecss.com/).

For JavaScript, there are two main things to do: run [JS Hint](http://jshint.com/) to detect errors and potential problems; run [JSCS](http://jscs.info/) to enforce a style guide.

## Preprocessors

[![](img/sass.png)](http://sass-lang.com/) [![](img/less.png)](http://lesscss.org/) [![](img/stylus.png)](http://stylus-lang.com/)

There are a couple of well-known preprocessors: [Sass](http://sass-lang.com/), [Less](http://lesscss.org/), and [Stylus](http://stylus-lang.com/).

They all have similar features, but Sass seems to be one of the most widely adopted. You don't have to use a preprocessor, but there are a couple of features that might make it worthwhile.

**Variables** are very handy, **Nesting** selectors makes for much better readability (but don't nest too deeply), better use of **Media Queries** (write them inside a selector, rather than in big blocks by themselves). **Partials** let you write your CSS in a modular way, but compile them into one file at the end. You can also set an option to minify the final file.

---

Next: [frameworks](./frameworks.html) Boilerplates and helpers.

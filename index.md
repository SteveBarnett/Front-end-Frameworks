---
layout: default
title: Front-end Frameworks
---

# Front-end frameworks

![](img/fef.jpg)

Taking an off-the-shelf front-end framework comes with a set of pros and cons. Some of the main things about a framework to consider are: how light or heavy it is for your users; how maintainable it will be to use; how closely it's values and choices match yours.

## Pros

Once you're learned how things work, using a framework can **speed up your development time**. A framework comes with **built-in design choices**, so the responsibility for that is taken off of you and your team. There's also a **clear set of rules** or way of doing things, and that can make communication about components easier.

## Cons

Frameworks can have a **steep initial learning curve**, since they're solving a large set of problems.

Although most are customisable they tend to have a recognisable look which can mean **your site can have a generic look to it**. These frameworks are developed by teams to meet their needs at the time they built them.

Despite being developed by big names in the industry, they sometimes **don't follow best practices** for HTML (such as using unsemantic elements, being overly verbose, or not baking in accessibilty) and CSS (like selector usage, rule usage, and size of stylesheet).

Since the framework is designed to be a catch-all solution it can get large, which means large CSS and JS files. That means **slower loading pages and higher data usage** for your users.

Your project probably won't use all the features of the framework, which means **your users end up downloading CSS and JS that they don't need**.

Their frameworks are built using their processes and are an expression of their opinions about the best ways to do things. **These opinions might not match yours**. If they match yours now, they might not in a few months time.

Changes to the framework are also out of your control, and **upgrading has the potential to introduce breaking changes**. This is made worse if you've customised the framework to more closely fit your needs.

## Summary

Think carefully about the cost of using a framework against the benefits it provides, especially the cost to your users. The best way to have a tool that works for you is to write your own custom framework. This can be made small and modular so it will be fast for you to use and light for your users. Since it will match your opinions and processes, it will be more maintainable.

If you really can't, then prefer smaller frameworks that are built in a modular fashion: that way you can pick and choose the pieces that you want to use.

For small pieces of UI find a site you like and use your browser's Developer Tools to see how it's built. Eventually, you'll want to build up something like a [Style Guide](http://styleguides.io/) (more on that later).

## Learning resources

Try and avoid using W3Schools as it is not the most reputable source, and has been known to contain incorrect or misleading information (despite appearing at the top of search results). Instead, use [Web Platform dot org](http://www.webplatform.org/). It's [backed by a lot of big names](https://www.webplatform.org/stewards/), including the World Wide Web Consortium (W3C) itself.

If you're looking for some small and specific, try searching on [CodePen](http://codepen.io/), but bear in mind that code there tends to be experimental.

There are [a lot of frameworks](http://usablica.github.io/front-end-frameworks/compare.html) of various sizes and for various use cases.

---

Next: [meta stuff](./meta-stuff.html). Styles of writing code and preprocessors.

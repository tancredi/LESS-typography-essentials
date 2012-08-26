LESS-typography-essentials
==========================

A small LESS file that sets up typography primitives.

This repo contains:

* `styles/main.less`: Contains variables, configuration and imports, ideally the only file needs working on for core changes.
* `styles/typography.less`: Contains the styling for most typography primitive elements, plus a few little utils.
* `styles/layout.less`: Just styling the page for display purposes.
* `styleguide.html`: A small HTML styleguide, useful to test your style while editing. Uses less.js to work, so will need running from a server/localhost configuration.

##Styles in typography.less

This is a list of the main styles and mixins contained in `typography.less`

* `.type-size`, `.type-margin`, `.type-padding`, .. mixins: Used across the whole file to apply rems sizes with px fallback.
* `h1, h2, h3, h4, h5, h6`
* `a`
* `hr`
* `p`
* `.boxed` class: For boxed elements. E.g. blockquotes and code tags.
* `.ruled` class: For ruled elements. Useful for headings and paragraphs. Reduces the use of `hr`.
* `ol`, `ul`
* `blockquote`
* `pre`
* `code`

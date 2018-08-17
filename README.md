accents
=======

Hi. I'm a starter theme called accents. I'm a fork of [\_s (underscores)](https://github.com/Automattic/_s) with all unnecessary cruft removed to provide the simplest starting point for WordPress theme development.

CSS Grid and Flexbox standards change everything we know about web design. The days of design hacks to accomplish layout are long gone, but WordPress seems to be the slowest in recognising this fact. Why are we still using floats and clearfixes? Why are we still packing our semantic markup inside containers, and those containers into other containers?

Beyond that, why are we injecting a style guide into a design skeleton before anything else? The standards of web design have evolved since 2015, and the tools we use should reflect that. That's where `accents` comes in. It doesn't make any assumptions; other than [Normalize.css](https://necolas.github.io/normalize.css/) and the simplest utility styles for screen reader links, it leaves the design as a blank slate to be decided for the site you intend to design. There are no unnecessary containers; only semantic HTML marks up each component, leaving it to you to decide if you need to add any wrappers or additional markup.

Compiling
---------

`accents` relies upon [Sass](https://github.com/sass/node-sass/) and [PostCSS](https://github.com/postcss/postcss) to produce `style.css` and `woocommerce.css`. To build these files, you can use the following command:

```bash
npm run build:css
```

If you only need `style.css`, you can use `npm run build:css:style`; likewise, if you only want to compile `woocommerce.css` you would use `npm run build:css:woocommerce`.

License
-------

\_s, and thereby accents, are developed under the [GNU GPL v2.0](https://github.com/sevvie/accents/tree/master/LICENSE).

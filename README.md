# Aglio Custom Theme fork from olio

This is *Olio-attributes*, the custom theme engine for [Aglio](https://github.com/danielgtaylor/aglio). It takes an [API Blueprint](http://apiblueprint.org/) AST and renders it into static HTML. Example use:

```bash
$ sudo npm install -g aglio
$ sudo npm install -g aglio-theme-olio-attributes
$ aglio -t olio-attributes -i blueprint.apib -o MyAPI.html
```

Theme engines for Aglio are described in more detail in the [Aglio documentation](https://github.com/danielgtaylor/aglio#customizing-output).

## Design Philosophy
Olio is designed from the ground up to be both **fast** and **extensible** while maintaining backward compatibility with most of the original Aglio theme. It uses the following technologies:

* [Less](http://lesscss.org/) to produce CSS
* [Markdown-it](https://github.com/markdown-it/markdown-it#readme) to render Markdown
* [Jade](http://jade-lang.com/) to produce HTML
* [Highlight.js](https://highlightjs.org/) to highlight code snippets

For backward compatibility, Jade templates can continue to use inline Stylus and CoffeeScript.

Original License
=======
Aglio[https://github.com/danielgtaylor/aglio]

Copyright &copy; 2016 Daniel G. Taylor

http://dgt.mit-license.org/

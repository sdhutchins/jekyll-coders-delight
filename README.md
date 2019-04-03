# jekyll-coders-delight

:warning: This theme is currently a work in progress! 

`jekyll-coders-delight` is a jekyll theme built for coders or programmers who want a minimal, code-friendly, and sleek blog design.

It is built on top of the [`contrast`](https://github.com/niklasbuschmann/contrast) jekyll theme, which was created by [@niklasbuschmann](https://github.com/niklasbuschmann).

## Installation (recommended)

Just fork the repo and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/), and your page is done.

*Note:* If you want to use this theme in a subfolder, then you need to create a `gh-pages` branch in your repo.

## Installation (jekyll-remote-theme method)

You can also create an empty repo, add `index.md` and `archive.md` files, which can be empty but need to contain front matter, and add this to your `_config.yml`:

```yaml
remote_theme: sdhutchins/jekyll-coders-delight

plugins:
  - jekyll-remote-theme
```

For an example repository, you can look at the [demo](https://shaurita.codes/) of this theme.

## Features

 - supports dark mode on macOS Mojave
 - MathJax support
 - no external ressources
 - included archive page
 - supports pagination
 - feed generation
 - responsive
 - syntax highlighting
 - supports comments via [disqus](https://disqus.com/) or [isso](http://posativ.org/isso/)
 - supports SEO
 - supports Google Analytics

## Based on

- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)
- [Contrast](https://github.com/jekyll/contrast)

## License

[public domain](http://unlicense.org/)


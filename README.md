# Comic Mono
A legible monospace font... the very typeface you’ve been trained to recognize since childhood. This font is a fork of [Shannon Miwa](https://github.com/shannpersand)’s [Comic Shanns](https://github.com/shannpersand/comic-shanns).

<p class="website-hidden">
  <a href="https://dtinth.github.io/comic-mono-font/">
    <img src="https://repository-images.githubusercontent.com/164606802/cd83d680-894c-11e9-83f7-c353c70df1cb" alt="Screenshot">
  </a>
</p>

## Download
- [ComicMono.ttf](https://dtinth.github.io/comic-mono-font/ComicMono.ttf)
- [ComicMono-Bold.ttf](https://dtinth.github.io/comic-mono-font/ComicMono-Bold.ttf)

## Differences from Comic Shanns
1. All glyphs have been adjusted to have exactly the same width (using code based on [monospacifier](https://github.com/cpitclaudel/monospacifier)).
2. The glyph metrics have been adjusted to make it display better alongside system font, based on [Cousine](https://fonts.google.com/specimen/Cousine)’s metrics.
3. The name is changed to `Comic Mono`.
4. A bold version of the font is generated using [FontForge’s Embolden](https://fontforge.github.io/Styles.html#Embolden) operation.

I have no font creation skills; I’m just a software developer. This font family is created by patching the original font, [Comic Shanns](https://github.com/shannpersand/comic-shanns), using a Python script, [`generate.py`](generate.py).

## What does it look like?
<p class="website-hidden">
  <a href="https://dtinth.github.io/comic-mono-font/#what-does-it-look-like">
    Check it out!
  </a>
</p>

```python
{% include_relative generate.py %}
```

## CDN
You can use this font in your web pages by including the stylesheet. CDN is provided by [jsDelivr](https://www.jsdelivr.com/package/npm/comic-mono).
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/comic-mono@0.0.1/index.css">
```

## npm Package
This package is [published to npm](https://www.npmjs.com/package/comic-mono).

## Packages published by third parties
- Arch Linux AUR: [ttf-comic-mono-git](https://aur.archlinux.org/packages/ttf-comic-mono-git/) (maintained by DBourgeoisat)

## License
It is licensed under the [MIT License](LICENSE).

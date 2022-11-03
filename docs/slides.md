---
theme: signalwerk
title: The new color vector fonts
---

```fm
style: negative
background: true
```

## Hello _👋_

# {{process.content.frontmatter.title}}

_What can we do with COLRv1 fonts?_

<footer>

2022 · Zurich · Stefan Huber

</footer>

--s--

```fm
style: image
background:
  image: https://portrait.signalwerk.ch/illustration/2020/rgb/w4000/stefan-huber.jpg
  position: 50% 40%
```

## Stefan

<div class="box box--w40p box--bottom box--white box--padding small">

- Developer
- ❦ Type Designer
<!-- <small>U+2766 ❦ FLORAL HEART</small> -->

</div>

<footer class="footer--right">

Illustration by [Benjamin Güdel](http://www.guedel.biz/) · 2020

</footer>

--s--

```fm
style: negative
background: true
```

## Naming

# _Color Fonts_

- multicolored fonts
- chromatic fonts

--s--

## What is it?

# Has multiple colors <br>_within_ a glyph

<footer>

History: In 1984 the PostScript Type 3 font specification was first released by Adobe. <br>These fonts were able to contain multiple color in a glyph.

</footer>

--s--

## Example

<div class="box--w80p box--ratio-16-9">
<iframe
  className="iframe--fill"
  src="https://player.vimeo.com/video/213887934?title=0&byline=0&portrait=0vz#t=0m25s">
</iframe>
</div>

<footer>

Source: [Fontself · Gilbert Color Bold ](https://www.fontself.com/blog/type-with-pride-a-color-font-chronicle)

</footer>

--s--

```fm
style: negative
background: true
```

## Question?

# Did you ever use a color font?

--s--

## Emoji

# <span style="font-size:3em">🤔</span>

<footer>

Japanese: e – 絵 picture | moji – 文字 character (Schriftzeichen)

</footer>

--s--

## Emoji · System-Font

# <span style="font-size:3em;font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',Roboto, Oxygen-Sans, Ubuntu,Cantarell,'Helvetica Neue', sans-serif;">🤔</span>

--s--

```fm
style: negative
background: true
class: code--background
```

## No pictures anymore

# Emojis are text

- technically `a` and `🤔` are (almost) the same for a computer

--s--

## Unicode · Encoding

# Exchang of emoji

- Unicode 6.0 – standardises 722 Emoji (October 2010)
- Wrong encodings: Wörter → Wˆrter <br><small>Encoding «Windows Latin 1» interpreted as «Mac OS Roman»</small>

--s--

## Demand for emoji

- Apple iOS 5.0 – 2011 <small>(2008 Japan only)</small>
- Apple Mac OS X Lion – 2011
- Google Android 4.4 – 2013
- Microsoft Windows 8.1 – 2013

<footer>

See also: [History of Emoji · Shady Characters](https://shadycharacters.co.uk/series/emoji/)

</footer>

--s--

## Colors stored in fonts

# OpenType Version 1.7 · 2020

- Microsoft (`COLR`/`CPAL`) <small>· Vector</small>
- Apple (`SBIX`) <small>· Bitmaps (multiple sizes)</small>
- Google (`CBDT`/`CBLC`) <small>· Bitmaps (one size)</small>
- Adobe/Mozilla (`SVG`) <small>· Vector</small>

--s--

```fm
style: negative
background: true
```

## Problem

# Color-Fonts were <br>_not one standard_ – <br>there are <br>**four standards**

--s--

## New Format!

## OpenType Version 1.9 · December 2021

- Wide support for `COLRv1`
  - Chrome v98+ · 2022-02-01
  - Firefox v107+ · 2022-11-15
  - Safari · ❌

<footer>

Source: [caniuse.com](https://caniuse.com/colr-v1)

</footer>

--s--

## What is now new?

# OpenType fonts with `COLRv1`

- Variable fonts with colors
- Gradients can be used

--s--

## Example arabic

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Amiri+Quran&display=swap" rel="stylesheet">

<h1 class="h1--amiri" >Hello</h1>

<h1 class="h1--amiri" style="direction: rtl; text-align: start;     letter-spacing: 0; font-family: 'Amiri Quran', serif;    font-feature-settings: normal;">

لمّا كان الاعتراف بالكرامة المتأصلة في جميع

</h1>
<br>

<style data-lt-active="false" spellcheck=false contenteditable style="font-size: .45em; line-height: 1.2; font-family: 'IBM Plex Mono', monospace;display: block;white-space: pre;"
>/* code demo */

.h1--amiri {
  color: red;
  font-palette: --test-palette;
}

@font-palette-values --test-palette {
  font-family: "Amiri Quran";
  override-colors: 0 red, 2 red;
}
</style>

<style >

style:focus {
    outline: 0 !important;
}

</style>

<footer>

Source: [Google Fonts · Amiri Quran](https://fonts.google.com/specimen/Amiri+Quran?query=amiri#styles)

</footer>

--s--

## UI · Change specific colors

<div class="box--w80p box--ratio-16-9">
<iframe
  className="iframe--fill"
  src="https://glitch.com/embed/#!/embed/duck-color?path=index.html&amp;previewSize=100&amp;attributionHidden=true">
</iframe>
</div>

<footer>

Source: [Google Developer · Updates to Emoji](https://developers.googleblog.com/2022/09/updates-to-emoji-new-characters-animation-colors-and-more.html)

</footer>

--s--

## Variable font

<div class="box--w90p box--ratio-16-9">
<iframe
  className="iframe--fill"
  src="./nabla-fonts/specimen.html">
</iframe>
</div>

<footer>

Source: [Nabla Font](https://github.com/justvanrossum/nabla)

</footer>

--s--

```fm
style: negative
background: true
```

## exit 0; thx

# Questions?

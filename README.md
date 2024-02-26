<!-- Copyright (C) 2021-2024 by Jinwen XU -->

# `colorist` bundle: write you documents in a colorful way

> **New documentations are still being written. For now, only the core code is included in TeX Live 2024 and MiKTeX (old documentations have been removed from the distribution).**

## Introduction

`colorist` is a collection of styles and classes that helps you to typeset articles and books with a colorful design.

> Package dependencies: [`amsfonts`](https://ctan.org/pkg/amsfonts), [`amsthm`](https://ctan.org/pkg/amsthm), [`anyfontsize`](https://ctan.org/pkg/anyfontsize), [`bookmark`](https://ctan.org/pkg/bookmark), [`caption`](https://ctan.org/pkg/caption), [*`draftwatermark`*](https://ctan.org/pkg/draftwatermark), [`embrac`](https://ctan.org/pkg/embrac), [`enumitem`](https://ctan.org/pkg/enumitem), [`extramarks`](https://ctan.org/pkg/extramarks), [`fancyhdr`](https://ctan.org/pkg/fancyhdr), [`float`](https://ctan.org/pkg/float), [*`fontspec`*](https://ctan.org/pkg/fontspec), [`geometry`](https://ctan.org/pkg/geometry), [`graphicx`](https://ctan.org/pkg/graphicx), [`hyperref`](https://ctan.org/pkg/hyperref), [`ifoddpage`](https://ctan.org/pkg/ifoddpage), [`iftex`](https://ctan.org/pkg/iftex), [`imakeidx`](https://ctan.org/pkg/imakeidx), [*`lua-widow-control`*](https://ctan.org/pkg/lua-widow-control), [`indentfirst`](https://ctan.org/pkg/indentfirst), [`marginnote`](https://ctan.org/pkg/marginnote), [*`mathpazo`*](https://ctan.org/pkg/mathpazo), [`mathtools`](https://ctan.org/pkg/mathtools), [*`newpx`*](https://ctan.org/pkg/newpx), [*`nowidow`*](https://ctan.org/pkg/nowidow), [`parskip`](https://ctan.org/pkg/parskip), [`pgf`](https://ctan.org/pkg/pgf), [`projlib`](https://ctan.org/pkg/projlib), [`regexpatch`](https://ctan.org/pkg/regexpatch), [`relsize`](https://ctan.org/pkg/relsize), [`silence`](https://ctan.org/pkg/silence), [`tcolorbox`](https://ctan.org/pkg/tcolorbox), [`tikzpagenodes`](https://ctan.org/pkg/tikzpagenodes), [`titlesec`](https://ctan.org/pkg/titlesec), [`titletoc`](https://ctan.org/pkg/titletoc), [`wrapfig2`](https://ctan.org/pkg/wrapfig2), [`ulem`](https://ctan.org/pkg/ulem).

It mainly consists of two parts.

- Main part:
    - `colorist.sty` : interface of the main style
        - `colorist-fancy.sty` : the style "fancy"
        - ... and more styles to come (currently on schedule: "plain", "classical", "modern", "simple", "elegant", "flow", "stream")
    - `colorart.cls` : class for typesetting articles
    - `colorbook.cls` : class for typesetting books

    They can be used with any major TeX engine. Currently they have native
    support to English, French, German, Italian, Portuguese
    (European and Brazilian) and Spanish typesetting.


- Derivative part:
    - `lebhart.cls` : enhanced version of `colorart`
    - `beaulivre.cls` : enhanced version of `colorbook`

    They are similar to the main classes, but have Unicode support, thus can
    only be used with either XeLaTeX or LuaLaTeX. Currently, they have native
    support to Chinese (simplified and traditional), English, French, German,
    Italian, Japanese, Portuguese (European and Brazilian), Russian and Spanish
    typesetting, and also use more beautiful fonts.

### How to get these files
You can get the `.sty` and `.cls` files mentioned above by compiling
`colorist.ins`:
```
latex colorist.ins
```
<!--
To get the `.tex` source files of the documentation, compile `colorist-doc.ins`:
```
latex colorist-doc.ins
```
-->

## Features

Compared with usual document classes, it has the following features:

- Several carefully designed styles.
- Native multilingual support: Chinese (simplified and traditional), English, French, German, Italian, Japanese, Portuguese (European and Brazilian), Russian and Spanish.
    > In particular, for simplified Chinese, traditional Chinese and Japanese, the fonts of the corresponding glyphs can be automatically switched.
- Ready-to-use theorem-type environments, with clever referencing supported.
- Support both the standard and the AMS writing fashion.
- ... and much more...


# License

This work is released under the LaTeX Project Public License, v1.3c or later.

slides
======

Written in $\LaTeX$ with beamer.

## Dependencies

Install $\LaTeX$. As for needed packages, if you're using _TeX Live_ then run:
```sh
$ tlmgr install beamer etoolbox pgf xcolor translator datetime2 tracklang xkeyval forest adjustbox pgfgantt pgfopts elocalloc environ trimspaces inlinedef collectbox helvetic
```

## Build

```sh
latexmk -pdf slides.tex
```

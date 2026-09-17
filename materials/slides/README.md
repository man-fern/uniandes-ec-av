# Diapositivas magistrales

This directory contains the selected public lecture decks for Econometría Avanzada:

- `s1` through `s13` in both TeX and PDF format;
- the shared preamble in `preambulo/`;
- `references.bib`; and
- only the figures used by these thirteen decks, in `Figuras/`.

The files preserve their paths from the private Overleaf project so each deck can be compiled from this directory. For example:

```bash
latexmk -cd -pdf -interaction=nonstopmode -file-line-error \
  -outdir=. -auxdir=build s1_programa.tex
```

Generated files under `build/` are not part of the public source set.

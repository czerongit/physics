# [A Geometric View of Einstein–Yang–Mills Energy and Stress](a-geometric-view-of-einstein-yang-mills-energy-and-stress.pdf)

**Author:** Sina Montazeri

**Date:** November 16, 2026

## Citation

```bibtex
@misc{Montazeri:A-Geometric-View-of-Einstein-Yang-Mills-Energy-and-Stress-November-16-2026,
  author = {Montazeri, Sina},
  title = {{A Geometric View of Einstein--Yang--Mills Energy and Stress}},
  howpublished = {Physics for Humanity preprint
                  \href{https://github.com/czerongit/physics/blob/main/preprints/A-Geometric-View-of-Einstein-Yang-Mills-Energy-and-Stress-November-16-2026/a-geometric-view-of-einstein-yang-mills-energy-and-stress.pdf}{Montazeri:A-Geometric-View-of-Einstein-Yang-Mills-Energy-and-Stress-November-16-2026}},
  year = {2026}
}
```

## Version

First dated edition in this collection. This package preserves the supplied manuscript PDF and its accompanying sources as of November 16, 2026.

## Source and Build

[LaTeX source](build/main.tex), [bibliography](build/references.bib) and [supplementary exact data](retained-source-exact-data.json) accompany the manuscript. The supplementary data are also included in `build/` for the relative link in a rebuilt PDF.

With a TeX installation providing pdfLaTeX, BibTeX, TikZ and the packages specified in `main.tex`, run the following commands from `build/`.

```sh
pdflatex -interaction=nonstopmode -halt-on-error main.tex
bibtex main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

The output is `build/main.pdf`.

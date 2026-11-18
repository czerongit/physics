# [A Geometric View of Einstein–Yang–Mills Energy and Stress](a-geometric-view-of-einstein-yang-mills-energy-and-stress.pdf)

**Author:** Sina Montazeri

**Date:** November 18, 2026

## Citation

```bibtex
@misc{Montazeri:A-Geometric-View-of-Einstein-Yang-Mills-Energy-and-Stress-November-18-2026,
  author = {Montazeri, Sina},
  title = {{A Geometric View of Einstein--Yang--Mills Energy and Stress}},
  howpublished = {Physics for Humanity preprint
                  \href{https://github.com/czerongit/physics/blob/main/preprints/A-Geometric-View-of-Einstein-Yang-Mills-Energy-and-Stress-November-18-2026/a-geometric-view-of-einstein-yang-mills-energy-and-stress.pdf}{Montazeri:A-Geometric-View-of-Einstein-Yang-Mills-Energy-and-Stress-November-18-2026}},
  year = {2026}
}
```

## Version

Second dated edition, following the [November 16 edition](../A-Geometric-View-of-Einstein-Yang-Mills-Energy-and-Stress-November-16-2026/). This revision adds “Mass and the excitation spectrum,” including the lattice extraction of a glueball rest mass and the relation between stress and curvature correlations. It also revises the title-page caption and adds a conclusion.

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

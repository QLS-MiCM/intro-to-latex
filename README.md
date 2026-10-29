# Intro to Latex Workshop

## Overview
A hands-on, modular introductory workshop on **LaTeX** designed for beginners and intermediate users. This repository contains presentation slides, progressive coding exercises, standalone TikZ/figure examples, and reference templates.


**Key Topics Covered:**
* **Document Architecture:** Basic syntax, structural units, columns, and minipages.
* **Localization:** Multilingual support (e.g., French language settings).
* **Citations & References:** Managing bibliographies using BibTeX and auxiliary tools.
* **Graphics & Figures:** Single images, multi-panel figures, and annotated panels.
* **Vector Graphics:** Drawing directly in LaTeX using TikZ and standalone figures.


## Requirements
No installation required. Sign up for a free account on overleaf.
* [Overleaf](https://www.overleaf.com/register) account

## Sofware
(Not recommended for beginners)
If you prefer working offline on your local machine, install a TeX distribution and an editor:
.
**LaTeX Distribution:**
   * **Windows:** [MiKTeX](https://miktex.org/download)
   * **macOS:** [MacTeX](https://www.tug.org/mactex/)
   * **Linux:** [TeX Live](https://www.tug.org/texlive/acquire-netinstall.html) (`sudo apt install texlive-full`)

**LaTeX Editor:**
   * [TeXmaker](https://www.xm1math.net/texmaker/download.html) *(Beginner-friendly)*
   * [VS Code](https://code.visualstudio.com/) + **LaTeX Workshop Extension** 
   * [TeXstudio](https://www.texstudio.org/)


## Material Outline
```
├── Exercises/        # Hands-on exercise 
│   └── Solutions/     
|   └── data/images
|   ├── 001-SimpleText.tex
│   ├── 002-StructuredDocument.tex
│   ├── 003-FrenchDocuments.tex
│   ├── 004-AddingReferences.tex
│   ├── 100-SingleImages.tex
│   ├── 101-ImageGrid.tex
│   ├── 102-TikzDrawings.tex
│   └── 103-StandaloneAnnotatedFigure.tex
├── Slides/
│   ├── images/       # Images used in presentation
│   └── slides.tex    # Main presentation
├── Outline
|   └── Workshop Outline.tex  
└── README.md
```
## Getting Started

**Clone the repository:**
   ```bash
   git clone git@github.com:QLS-MiCM/intro-to-latex.git
   cd into-to-latex
   ```
**Follow the Slides:**
 Open `Slides/slides.pdf` or compile `Slides/slides.tex` to PDF to view the presentation.

**Run the Exercises:**
 Navigate into `Exercises/` and upload the `.tex` files to overleaf and go over the examples in numeric order.

## Recommended Resources
* [Overleaf Tutorial](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
* [Tikz Tutorial](https://latex-graphics.com/)
* [LaTeX Stack Exchange](https://tex.stackexchange.com/)
* [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)

*Workshop created as part of the McGill Initiative in Computational Medicine*

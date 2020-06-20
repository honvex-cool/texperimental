# TeXperimental
A set of LaTeX packages for taking notes and writing math texts

# Installation
To install, put the `.sty` files into `~/texmf/tex/latex` (create this directory structure, if it doesn't exist) and run `texhash ~/texmf`.

# Usage

 - `\usepackage{texperimental-math}` for texts containing math and physics
 - `\usepackage{texperimental-notes}` for taking notes and enumerating things
 - `\usepackage{texperimental-drawings}` for drawing with the `tikz` package
 - `\usepackage{texperimental-plots}` for plotting functions with the `pgfplots` package (not very functional at the moment, but it will be extended)

`\usepackage{texperimental}` loads both `\usepackage{texperimental-notes}` and `\usepackage{texperimental-math}`.

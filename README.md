# ⚠ This repository is not maintained any more. Please move on to <https://github.com/PhelypeOleinik/lipsum> ⚠

# lipsum
150 paragraphs of Lorem ipsum dummy text for LaTeX.

## Install
In most cases it is not requried to install this package manually, it is
included in the major tex-distributions. If, for some reason, you want install
it manually, run lipsum.ins through (pdf)latex to generate the style file. To
generate the documentation, run lispum.dtx through a latex program that
understands utf8 input (XeLaTeX or lualatex).

## Usage

See the documentation.

## Quick'n'dirty
```
\documentclass{article}
\usepackage{lipsum}

\begin{document}
\lipsum
\end {document}
```

# latex-templates

Research-grade LaTeX structures used in my own papers, posters, and presentations. These are authentic working templates, not didactic examples — for educational TikZ and PGFPlots content see [Ars Mathematica](https://ro-smtz.github.io/ars-mathematica/).

## Structure

```text
latex-templates/
├── figures/        # Standalone TikZ and PGFPlots figures
├── beamer/         # Presentation themes and slide templates
└── paper/          # Article structure, bibliography styles
```

## Compilation

Figures are written for XeLaTeX, which is required to load the New Computer Modern font via `fontspec` and `fontsetup`:

```bash
xelatex figure.tex
```

They can also be compiled with pdfLaTeX — just comment out the two font packages at the top of the file:

```tex
% \usepackage{fontspec}
% \usepackage[default]{fontsetup}
```

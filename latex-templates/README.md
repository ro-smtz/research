# latex-templates

Research-grade LaTeX structures used in my own papers, posters, and presentations. These are authentic working templates, not didactic examples — for educational TikZ and PGFPlots content see [Ars Mathematica](https://ro-smtz.github.io/ars-mathematica/).

## Structure

```
latex-templates/
├── figures/        # Standalone TikZ and PGFPlots figures
├── beamer/         # Presentation themes and slide templates
└── paper/          # Article structure, bibliography styles
```

## Compilation

Figures are compiled with XeLaTeX and exported to PDF, then converted to PNG at 150 DPI via macOS Preview. Aspect ratios: 4:3 for slides, 1:1 for standalone figures.

## Dependencies

- LaTeX distribution with XeLaTeX
- TikZ, PGFPlots, siunitx, physics

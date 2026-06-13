# Kinds as Projectibility Profiles

This repository contains Brett Reynolds's paper **Kinds as Projectibility
Profiles**.

## Current draft

- `main.tex` is the canonical LaTeX source.
- `main.pdf` is the compiled draft.
- `notes/section-plan.md` records the Roughdraft-reviewed section plan.

## Build

This project uses XeLaTeX:

```bash
make
```

The manual build sequence is:

```bash
xelatex main.tex
biber main
xelatex main.tex
xelatex main.tex
```

## License

The manuscript, source files, notes, and compiled PDF are licensed under the
Creative Commons Attribution 4.0 International License (CC BY 4.0). See
`LICENSE`.

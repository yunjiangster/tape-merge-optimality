# Tape merge is optimal up to a size ratio of 148/95

**Author:** Yunjiang Jiang

A computer-assisted proof of tape-merge optimality for two sorted lists of
lengths m ≤ n ≤ (148/95)m, together with the exact comparison bounds
M(6,22) = 21 and M(6,25) = 22.

- [Read the paper](TAPE_MERGE_OPTIMALITY.pdf)
- [LaTeX source](TAPE_MERGE_OPTIMALITY.tex)

## Build

The source is self-contained, with an inline bibliography.

```sh
pdflatex -interaction=nonstopmode -halt-on-error TAPE_MERGE_OPTIMALITY.tex
pdflatex -interaction=nonstopmode -halt-on-error TAPE_MERGE_OPTIMALITY.tex
```

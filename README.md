# RAdCor Algorithm Theoretical Basis Document

This repository contains the LaTeX source code of the Algorithm Theoretical Basis Document (ATBD) document for the atmospheric correction processor developed in the RAdCor project. The document describes the theoretical basis, the specific approach, and the implementation in the free and open source atmospheric correction software ACOLITE (https://github.com/acolite/acolite). The ACOLITE manual contains some information and examples on how to use the RAdCor processor. RAdCor is also described in the following publication: Castagna and Vanhellemont (2025), [A generalized physics-based correction for adjacency effects](https://doi.org/10.1364/AO.546766)

Suggested citation for the ATBD:
Castagna, A.; Vanhellemont, Q.; Sabbe, K. 2024. RAdCor Algorithm Theoretical Basis Document. Version 12/2024. Available at: https://github.com/acolite/radcor_atbd/.

To compile the document run from the root directory (in Linux or macOS):

```
{
  cd src
  pdflatex radcor_D_2_1_ATB.tex
  bibtex radcor_D_2_1_ATB.aux
  pdflatex radcor_D_2_1_ATB.tex
  pdflatex radcor_D_2_1_ATB.tex
  rm radcor_D_2_1_ATB.aux
  rm radcor_D_2_1_ATB.blg
  rm radcor_D_2_1_ATB.log
  rm radcor_D_2_1_ATB.out
  rm radcor_D_2_1_ATB.toc
  mv radcor_D_2_1_ATB.pdf ../radcor_D_2_1_ATB.pdf
}
```

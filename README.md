# RAdCor Algorithm Theoretical Basis Document

This repository contains the Latex source code of the Algorithm Theoretical Basis Document (ATBD) document for the new atmospheric correction processor developed in the RAdCor project. The document describes the theoretical basis, the specific approaches and the implementation in the free and open source atmospheric correction software ACOLITE (https://github.com/acolite/acolite). For information on usage of the processor in ACOLITE see ACOLITE's manual. 

Suggested citation:
Castagna, A.; Vanhellemont, Q.; Sabbe, K. 2024. RAdCor Algorithm Theoretical Basis Document. Version 12/2024. Available at: https://github.com/acolite/radcor_atbd.

To compile the document run from the root directory (in Linux):

```
{
  cd src
  pdflatex radcor_D_2_1_ATB.tex
  bibtex radcor_D_2_1_ATB.aux
  pdflatex radcor_D_2_1_ATB.tex
  pdflatex radcor_D_2_1_ATB.tex
  mv radcor_D_2_1_ATB.aux aux/radcor_D_2_1_ATB.aux
  mv radcor_D_2_1_ATB.blg aux/radcor_D_2_1_ATB.blg
  mv radcor_D_2_1_ATB.log aux/radcor_D_2_1_ATB.log
  mv radcor_D_2_1_ATB.out aux/radcor_D_2_1_ATB.out
  mv radcor_D_2_1_ATB.toc aux/radcor_D_2_1_ATB.toc
  mv radcor_D_2_1_ATB.pdf ../radcor_D_2_1_ATB.pdf
}
```



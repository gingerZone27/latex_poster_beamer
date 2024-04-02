## Latex-Based Poster Template
This project contains a latex-based poster template using beamer.

### Usage
Compile the main.tex file with latex system to generate your poster.

You can refer to the following table (to-be-updated) to add your own information:
|  Content You Want To Update |     Target File     |  Line Number  |
|:---------------------------:|:-------------------:|:-------------:|
|       Paper Title           |      main.tex       |      17       |
|       Author Info           |      main.tex       |     18-22     |
|      Paper Content          |      main.tex       |    from 35    |
|      Reference              |      ref.bib        |       -       |
|      Activity  Logo         |  beamerthemeZH.sty  |      94       |
|      Institute  Logo        |  beamerthemeZH.sty  |      105      |
|      Website and Email      |  beamerthemeZH.sty  |    127/131    |
|      Customized colors      |  beamerthemeZH.sty  |     18-23     |


Also, use the following command to add new blocks.
```latex
\begin{myblock}{Block Title Here}
Latex content should be here.
\end{myblock}\vfill
```

If not necessary, please follow the existing method of defining columns.

### Notice
The original template uses `minipage` to contain figures.
Package `subcaption` may be needed to insert subfigures.


### Acknowledgement
The source of link is [stackexchange](https://tex.stackexchange.com/questions/341/how-to-create-posters-using-latex).

The original project is [latex-beamerposter](https://github.com/deselaers/latex-beamerposter) with our appreciation.
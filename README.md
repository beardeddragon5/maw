# MAW Expose Vorlage

This project is a simple LaTeX template especially made for the
MAW-Course during my master semester at [HAW-Landshut](https://www.haw-landshut.de/).

During the course we needed to write an expose targeting a scholarship provider for
the final master thesis.

This was an therotical excersise and should train us in looking up ressources and
writing an interessesting, but realistical expose.

## What this template provides

- An relatively compact output, because the final page size shouldn't exceed a certain
number.
- The citations are in the format described in the book "Martin Kornmeier 'Wissenschaftlich schreiben leicht gemacht'".
- An better and more up-to-date version unlike the provided template from the institute
- Ability to format the sections to be more visually pleasing
- Ability to write in any editor without being spammt


## Installation

```bash
sudo apt-get install texlive texlive-lang-german texlive-bibtex-extra texlive-latex-extra latexmk biber
```

In the editor of your choice you can download an appropiate plugin for
latex support.

Test if everything is working by building the file from the `Expose.tex`.
All additional temporary build files should be put into `out/`. If the
first build fails run a second time, to be sure.

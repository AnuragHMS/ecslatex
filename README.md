# ecslatex
ECS LaTeX Template reconfigured for compilation in newer versions of TeX

To use, make LaTeX files and include them in `master.tex`. Three chapters have been included as an example.

This document uses IEEE Referencing (through `IEEETran.bst`) - This is available from [here](https://www.ieee.org/conferences_events/conferences/publishing/templates.html)

This is based on the original `ecsgdp.cls`, by [Steve R Gunn](https://www.ecs.soton.ac.uk/people/srg), and which can be found [here](http://users.ecs.soton.ac.uk/srg/softwaretools/document/)

## Compilation

To compile this, simply open up `master.tex` with your favourite LaTeX compiler (I use `pdflatex`) and compile.

You can edit the master BibTeX Bibliography file at `master.bib`. Remember to compile using BibTeX then a couple of times with LaTeX for these citations to show up in your document.

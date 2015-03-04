# CETYSLaTeX

Write documents using APA Style with CETYS Universidad modifications.

## Compilation

To create a Document.pdf file:

### Without bibliography:

    pdflatex Document.tex

### Using a bibliography.bib file:

    pdflatex Document.tex
    bibtex Document.aux
    pdflatex Document.tex
    pdflatex Document.tex 

## Features

* APA style formatting.
* CETYS style front page generation.
* Automatic source citation.
* Automatic references page generation.

## License: WTFPL

Copyright (C) 2015 Javier Rizzo

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.

# English Translation of "Arithmetices Principia, Nova Methodo Exposita"

This repository hold an English translation, with original Latin, of Guiseppe Peano's "Arithmetices Principia, Nova Methodo Exposita" or "The Principles of Arithmetic, Presented by a New Method".  This short book is from 1889 and it laid out the axioms of elementary arithmetic that are still used today.

## Compiling

Install [LaTeX](https://www.latex-project.org/get/)

Start a command prompt or terminal window

If you have pdflatex, run:
   pdflatex Peano

Otherwise:
   latex Peano
   dvipdfm Peano


## License

The files in this repository are issued under Creative Commons Attribution-ShareAlike 4.0

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.


## Origin of the Translation

Michael Nahas created this repository by coping the LaTeX and PDF files on February 27th, 2018 from:

[http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.pdf](http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.pdf)

[http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.tex](http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.tex)

[http://vincentverheyen.com/sites/default/files/documents/node_26/hyperendnotes.sty](http://vincentverheyen.com/sites/default/files/documents/node_26/hyperendnotes.sty)

According to [http://vincentverheyen.com/about](http://vincentverheyen.com/about) "all content ever published on this website is licensed under [Creative Commons] Attribution-ShareAlike 4.0".

Footnote 6 of the original document says "Written by Vincent Verheyen. Last updated on 17/8/2015. I encourage you to use your reason for good. If you want my support, please contact me via http://vincentverheyen.com/contact. It is possible to contribute to the flourishing of knowledge,
even when you have an intelligence like mine. Thank you and good luck studying.

"I would like to thank Mauro Allegranzo and acknowledge his support of this work and his various comments during its creation."


## Project Goals

* Create title/author page and move note from footnote 6 to it
* Change page size to allow A4 or Letter. (Original had 31cm by 200cm pages.)  Probably lay out text side-by-side on landscape paper
* Removed dependence on hyperendnotes package
* Add mathematical commentary (most likely in a color other than black; not much room for margin notes)

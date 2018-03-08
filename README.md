# English Translation of "Arithmetices Principia, Nova Methodo Exposita"

This repository holds an English translation, with original Latin, of Guiseppe Peano's "Arithmetices Principia, Nova Methodo Exposita" or "The Principles of Arithmetic, Presented by a New Method".  This treatise is from 1889 and it laid out the axioms of elementary arithmetic that are still used today.

**A recent PDF of the translation is available [HERE](https://github.com/mdnahas/Peano_Book/raw/master/Peano.pdf).**


## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.


## Compiling to PDF

If you want the most up-to-date version, or you want to modify it, or you want it on your paper size (e.g., A4), you can compile the document.  Here's how you do that:

1. Install [LaTeX](https://www.latex-project.org/get/)

2. Start a command prompt or terminal window

3. If you have pdflatex, run:
```
   pdflatex Peano
```

3. Otherwise run:
```
   latex Peano
   dvipdfm Peano
```

## Spellcheck

If you commit changes, please spellcheck.

I used the program "aspell".  You can install it with your package manager.  While at it, try to install the English (EN) and Latin (LA) dictionaries.  My package manager did not support a Latin dictionary.  You can downloaded the dictionary(s) [here](https://ftp.gnu.org/gnu/aspell/dict/0index.html).

To install a dictionary, copy it to a temp directory and run
```
    bunzip2 aspell6-la-*.tar.bz2
    tar xvf aspell6-la-*.tar
    cd aspell6-la-*[^r]
    ./configure
    make
    sudo make install
```

The following command will run spellcheck on the LaTeX file using both dictionaries.
```
    cat Peano.tex | aspell -t --lang=la list | aspell --lang=en list > misspelled_words.txt 
```

I found this command useful to prioritize mistakes.
```
   sort misspelled_words.txt | uniq -c | sort -n
```

## Origin of the Translation

Michael Nahas created this repository by coping the LaTeX and PDF files on February 27th, 2018 from:

[http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.pdf](http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.pdf)

[http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.tex](http://vincentverheyen.com/sites/default/files/documents/node_26/Peano.tex)

[http://vincentverheyen.com/sites/default/files/documents/node_26/hyperendnotes.sty](http://vincentverheyen.com/sites/default/files/documents/node_26/hyperendnotes.sty)

According to [http://vincentverheyen.com/about](http://vincentverheyen.com/about) "all content ever published on this website is licensed under [Creative Commons] Attribution-ShareAlike 4.0".

Footnote 6 of the original document says "Written by Vincent Verheyen. Last updated on 17/8/2015. I encourage you to use your reason for good. If you want my support, please contact me via http://vincentverheyen.com/contact. It is possible to contribute to the flourishing of knowledge,
even when you have an intelligence like mine. Thank you and good luck studying.

"I would like to thank Mauro Allegranzo and acknowledge his support of this work and his various comments during its creation."


NOTE: The website VincentVerheyen.com was expected to be deleted 2018-03-26.  The webpages may be available via the Internet Archive's [WaybackMachine](https://web.archive.org/) at 
https://web.archive.org/web/*/http://VincentVerheyen.com/node/26




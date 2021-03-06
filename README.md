Open Advice
===========

This is the repository for the Open Advice book. You can find the LaTeX
source of the book here.

中文配置方法 <http://vistb.net/2012/05/config-latex-ch-env-in-ubuntu/>

## Building a PDF

To build a pdf file out of the LaTeX source install pdflatex and run the
command

    make

If you don't have make, you can run:

    pdflatex Open-Advice

To build all other formats run:

    make all

## Updating the book after changes

If you have made local changes to the source of the book and want to render
a PDF again:

    make clean
    make

## Installing pdflatex

On Debian-based systems, you can install "pdflatex" with:

    sudo apt-get install texlive-latex-extra

On Gentoo-based systems, "pdflatex" and required extra pacakges can be installed with:

    emerge texlive-latexrecommended xcolor

## Issues

    "File `todonotes.sty' not found."

This means you need to run the above apt-get command, because you are
missing one of the LaTeX extra packages.

    "File `tocstyle.sty' not found."

If your distro doesn't have that you can download it from
http://www.tug.org/texlive/devsrc/Master/texmf-dist/tex/latex/koma-script/tocstyle.sty
and place it in the root directory of the book.

## Project Statistics

Project activity is tracked by ohloh.net - see
https://www.ohloh.net/p/open-advice-the-book
for details.

## Referencing This Book

To reference this book, you may use the following Bibtex citation:

```
@book{Greve2012,
author = {Greve, Georg and Hemel, Armijn and Prodromou, Evan and Kr\"{o}tzsch, Markus and Ortega, Felipe and Hawthorn, Leslie and Ottens, K\'{e}vin and Pintscher, Lydia and Mitchell, Jeff and Appel, Austin and Macieira, Thiago and Bergius, Henri and Blin, Kai and Pulido, Ara and Klapper, Andre and Leto, Jonathan and Jha, Atul and Bowen, Rich and Gentle, Anne and McCance, Shaun and Bhattacharjee, Runa and Paumier, Guillaume and Quintero, Federico Mena and Strode, M\'{a}ir\'{\i}n Duffy and Trounev, Eugene and Kaye, Robert and Bacon, Jono and Leisse, Alexandra and Riddell, Jonathan and May, Thom and Untz, Vincent and Jarvis, Stuart and Poortvliet, Jos and Khudairi, Sally and Plunkett, N\'{o}ir\'{\i}n and Neary, Dave and Greenaway, Gareth J. and Deckelmann, Selena and Adam, Till and Karlitschek, Frank and Daffara, Carlo and Jaeger, Till and Coughlan, Shane},
editor = {Pintscher, Lydia},
isbn = {9781105514937},
keywords = {foss,open source,oss},
pages = {1--310},
title = {{Open Advice: FOSS: What We Wish We Had Known When We Started}},
url = {http://open-advice.org/},
year = {2012}
}
```

## License

The book and its content is licenced under CC-BY-SA. For questions about the
book contact Lydia Pintscher at lydia@kde.org.

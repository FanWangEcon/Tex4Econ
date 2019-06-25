---
author:
- 'Fan Wang (University of Houston)'
bibliography:
- 'fansample.bib'
title: Sandbox Testing Latex
---

\maketitle
Equation Test
=============

Inline:
$\sigma_y = \sqrt{ \sum_{y} P(Y=y) \cdot \left( y - \mu_y \right)^2}$

$$\Omega^{\max} = \exp(z^{\max}) \cdot \left(\Lambda^{\max}\right)^{\alpha}$$

$$\label{eq:1}
\sum_{i=0}^{\infty} a_i x^i$$

Citation Testing
================

@becker_human_1986 is a paper on Human Capital.

URL Test
========

-   [Fan Wang Site](http://fanwangecon.github.io)

-   [Fan Wang Dynamic Asset Code
    Repository](https://fanwangecon.github.io/CodeDynaAsset/)

\pagebreak 
Pandoc
======

Install and convert Tex to Word
-------------------------------

For editing latex files in word.

1.  install pandoc: [Pandoc Site Installation
    Link](https://pandoc.org/installing.html)

2.  open up command line

3.  *cd into where tex file is*: cd

4.  *run this for tex to word*: pandoc -s fansample.tex -o
    fansample.docx

Convert from tex to word and markdown
-------------------------------------

1.  *run this for tex to word*: pandoc -s fansample.tex -o
    fansample.docx

2.  *run this for tex to md*: pandoc -s fansample.tex -o fansample.md

Convert from back to tex from word and markdown
-----------------------------------------------

1.  run this to convert tex to word: pandoc -s fansample.tex -o
    fansample.docx

2.  run this to convert tex to markdown: pandoc -s fansample.tex -o
    fansample.md

Convert with Bibliography
-------------------------

Suppose the file pandoc --bibliography=BiblatexChinaClosureWestern.bib
-o Draft20180210.docx Draft20180210.tex

\printbibliography

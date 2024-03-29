# Latex Submission for MS-2XXXXX Documentation

Contents in this zip folder were created following Journal of ABC  [Journal style guidelines](https://www.elsevier.com/journals/journal-of-abc)

## Manuscript File

*submit_journal.pdf* contains the compiled Manusciprt PDF file. It is compiled from the *submit_journal.tex* latex file. The *submit_journal.tex* file brings together text from various subfiles:

1. *manuscript_title_etc.tex*: manuscript title page information, including title, authors, abstract, keywords, acknowledgments.
2. *manuscript_main.tex*: this tex document contains all text and contains the main document of the paper
3. *manuscript_tab_fig.tex*: this tex document contains the main paper's five tables and five figures
4. *manuscript_online_appendix.tex*: this tex document contains the online appendix of the paper.

We also include *submit_journal.bbl*, which are created when the *submit_journal.tex* file is compiled with pdflatex.

## Folders

- *bib*: contains the bib file, *reference.bib*, that contains reference information, used to generate *submit_journal.bbl*.
- *fragments*: contains latex preambles used by the manuscript
- *tab_main*: tex file for the main tables in the paper
- *fig_main*: eps images for the main figures in the paper
- *tab_fig_online_appendix*: tables and figures used for online appendix.

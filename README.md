[![Star](https://img.shields.io/github/stars/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/stargazers) [![Fork](https://img.shields.io/github/forks/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/network/members) [![Star](https://img.shields.io/github/watchers/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/watchers) [![DOI](https://zenodo.org/badge/182257793.svg)](https://zenodo.org/badge/latestdoi/182257793)

This is a work-in-progress [website](https://fanwangecon.github.io/Tex4Econ/) of support files for writing various files with latex, produced by [Fan](https://fanwangecon.github.io/). The project includes sample file for papers, exams, homeworks, etc.

This package is synced with [overleaf project](https://www.overleaf.com/read/xjsqdwrkfrhq), all latex files and examples here are viewable and compilable on the overleaf project synced site.

From other repositories: For code examples, see [Python Example Code](https://fanwangecon.github.io/Py4Econ/), [R Example Code](https://fanwangecon.github.io/R4Econ/), [Matlab Example Code](https://fanwangecon.github.io/M4Econ/), and [Stata Example Code](https://fanwangecon.github.io/Stata4Econ/). See [here](https://github.com/FanWangEcon) for all of [Fan](https://fanwangecon.github.io/)'s public repositories.

Materials gathered from various [projects](https://fanwangecon.github.io/research) in which latex is used. The goal of this repository is to make it easier to find/re-use latex files produced for various projects.

[![](https://img.shields.io/github/last-commit/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/commits/master) [![](https://img.shields.io/github/commit-activity/m/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/graphs/commit-activity) [![](https://img.shields.io/github/issues/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/issues) [![](https://img.shields.io/github/issues-pr/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/pulls)

# 1. Latex Bib, Equations, Tables, Figures

## 1.1 [References](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference)

1.  [Biblatex Citation and Bibliography](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/biblatex_basic): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/biblatex_basic/biblatex_test.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/biblatex_basic/biblatex_test.pdf)
    - *biblatex-chicago; \textcite{becker_human_1986}; \autocite{becker_human_1986}*
    - Full title in-text citation: *\citetitle{becker_human_1994} \autocite{becker_human_1994}*
    - Display URL in bibliography if DOI does not exist with biber backend
    - Biblatex format for for working papers mimeo and in series
2.  [Section References, Vary Link Colors by Section](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/labelref): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/labelref/labelref_test.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/labelref/labelref_test.pdf)
    - *Section \ref{sec:intro} (Page \pageref{sec:intro}); \hypersetup{hidelinks=true}*

## 1.2 [Equations](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/equation)

1.  [Multiple Lines](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/equation): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/equation/multilines.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/equation/multilines.pdf)
    - *split vs gathered*
    - *substack vs array*
2.  [Equation Cases](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/equation): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/equation/cases.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/equation/cases.pdf)
    - *cases*

## 1.3 [Symbols, Operators and Accents](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/symbols)

1.  [Symbols and Accents](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/symbols): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/symbols/fs_symbols.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/symbols/fs_symbols.pdf)
    - *underline vs overline*, *underaccent bar vs bar*
    - *boldsymbol vs mathbf*
2.  [Unicode Handling](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/symbols): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/symbols/fs_unicode.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/symbols/fs_unicode.pdf)
    - Declare unicode and use unicode directly in latex
    - *inputenc*, *DeclareUnicodeCharacter*

## 1.4 [Estimates Table](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/)

1.  [Multi-Panel Estimation Table Medium Size](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_4col_cts_dis2inter.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_4col_cts_dis2inter.pdf)
    - Three main variables, three interactions, three controls, presented in separate groups
    - Two groups of estimates, results from four regressions
    - Table caption and multi-line table notes with linebreaks
2.  [Multi-Panel Estimation Table Large Size](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_6col_cts_dis2inter.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_6col_cts_dis2inter.pdf)
3.  [Small Estimates Table](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates/estismall.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates/estismall.pdf)

## 1.5 [Figures](https://github.com/FanWangEcon/Tex4Econ/blob/master/_fig/)

1.  [Figure Alignment](https://github.com/FanWangEcon/Tex4Econ/blob/master/_fig/alignment): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_fig/alignment/figalign.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_fig/alignment/figalign.pdf)
    - Center align single or multiple sub-figures with captions, vertically and horizontally
    - Caption equal-width with subfigure
    - **latex**: *float, subcaption, caption*

## 1.6 [TIKZ](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/)

1. [Tikz Page Layout](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/positioning): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/positioning/fs_tikz_position.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/positioning/fs_tikz_position.pdf)
    - Relative positioning, proportional to textwidth
    - Two or four subfigures
2. [Tikz Timeline](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline.pdf)
    - Straight and curved connected lines
3. [Tikz Dynamically Sized Eight Pane Model Timeline](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline_8pane.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline_8pane.pdf)
    - Dynamically sized panes for prior, current and next periods
    - Dynamically sized ext panes, graph panes and labeling areas
    - Parametrized proportioning of panes with dynamic adjustments
4. [Tikz Linear Spline Equation Plotting](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/fplot): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/fplot/functionplot.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/fplot/functionplot.pdf)
    - sum of linear equations
    - linear spline and inverted linear spline
    - *def, domain, variable, plot*
5.  [Tikz Figure Annotation](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/annotate): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/annotate/fs_tikz_annotate.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/annotate/fs_tikz_annotate.pdf)
    - point to intercept and slope
6.  [Tikz Game Strategy Graphs](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/tree): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/tree/fs_tikz_gametree.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/tree/fs_tikz_gametree.pdf)
    - continuous and discrete strategies
    - strategy branches, curved and straight lines

# 2. Latex Layout etc.

## 2.1 Sizing

1.  [Reduce Line-Gap](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/spacing/reduce): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/spacing/reduce/reduce.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/spacing/reduce/reduce.pdf)

## 2.2 Footer and Headers

1.  [Repaginate Response for Referees](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/foothead/repage): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/foothead/repage/repage_response_referee.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/foothead/repage/repage_response_referee.pdf)

## 2.3 Conversion

1.  [Pandoc File Conversion](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/pandoc): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/pandoc/fansample.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/pandoc/fansample.pdf)

# 3. Templates

In overleaf, click on New Project, choose upload project, then select zip below.

## 3.1 Working Paper Templates

1.  [Template Figure Table and Reference](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/draft.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/draft.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/fantemplate_basic_imgtabref.zip)

## 3.2 Revise and Resubmit Templates

1.  [Template Paper, Response to Referees, Section Numbering and Bib](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/draft.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/draft.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/fantemplate_paper_rr_response.zip)
    -   Figures, tables, references.
    -   Separate page numbers for each section: _\\renewcommand{\\thesection}{\\arabic{section}}_
    -   Separate heading count for responses to referees: _\\setcounter{section}{0}_
    -   Separate bibliographies: _refsection_

## 3.3 Accepted Paper Templates

1.  [Accepted Paper Submission to Journal](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_acceptedsubmit/): [**journal-tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_acceptedsubmit/submit_journal.tex) \| [**journal-pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_acceptedsubmit/submit_journal.pdf) \| [**preprint-tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_acceptedsubmit/submit_preprint.tex) \| [**preprint-pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_acceptedsubmit/submit_preprint.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_acceptedsubmit/fantemplate_acceptedsubmit.zip)
    - *journal-pdf* and *journal-tex*: All paper contents in a single PDF for submission to journal, with separate references and page numbering for the main text and the appendix, respectively. Contents are organized for copy-editors to find easily.
    - *preprint-pdf* and *preprint-tex*: All paper contents in a single PDF with one page-numbering for main and appendix and a single set of references. This file uses the same input files and saved strings as the *journal-tex* file. The resulting PDF can be shared as a preprint.

## 3.4 Other Templates

1. [Template Image Only Appendix](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_image_appendix/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_image_appendix/draft.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_image_appendix/draft.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_image_appendix/fantemplate_image_appendix.zip)
    -   An appendix file with only figures.
    -   Page number, section number, and alignment control for multiple figures.
    -   Captions below and above figure. Captions with heading and sub-notes.
2.  [Template Figure Table and Reference Roman 12 Double Space](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/draft.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/draft.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/fantemplate_basic_roman.zip)
3.  [Template Recommendation Letter](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/recommendation.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/recommendation.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/fantemplate_recommendation.zip)
    -   Recommendation letter with logo and signature.
    -   Contact and address panel.

## 3.5 Github Integration

This [overleaf project](https://www.overleaf.com/read/xjsqdwrkfrhq) is synced with this git repository. You can clone the project, pull project to overleaf, and compile in overleaf browser. Specifically: clone the repo; go to your overleaf account and create a project; click on menu under sync with git/github.

The writing/structure is to:
1. Store latex formatting file etc in separate files away from paper tex.
2. For papers, write in tex fragments stored in separate files. Main tex paper file mainly contains structure/outline.
3. Files synced through git/github, pull from github to edit/share with co-authors on [overleaf.com](https://overleaf.com) or edit locally.

Please contact [FanWangEcon](https://fanwangecon.github.io/) for issues or problems.

# 4. Program Installations

1. [Install Python, R, Latex, VSCode, Atom etc](https://fanwangecon.github.io/Tex4Econ/nontex/install/windows/fn_installations.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/install/windows/fn_installations.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/install/windows/fn_installations.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/install/windows/fn_installations.html)
    - Conda base Python, R in and outside of Conda
    - Windows and Linux instructions
    - Install various editors: VSCode, Atom, etc.
    - *conda update --all*
    - *Rtools, install.packages(), devtools::install_github()*
2. [Atom, Git, Github, etc Set-up for Linux](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_ubuntu.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/install/linux/fn_ubuntu.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_ubuntu.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_ubuntu.html)
    - *sudo apt-get install atom; install git*
    - *git init; config; git remote add; git pull*
    - *wget; bash; source*
    - *ssh-keygen -t rsa; cat*
3. [Vim and Neovim Set-up](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_vim.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/install/linux/fn_vim.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_vim.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_vim.html)
    - vimrc file, Vim-Plug plugin setup
    - *Plug 'vim-airline/vim-airline'*
    - *vim-airline, onedkar, Goyo, Limelight*


# 5. gitpages and git

1. [Bash Pull and Push from Single Remote Github Repo](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_basics/fs_git_bash.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/git/g_basics/fs_git_bash.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_basics/fs_git_bash.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_basics/fs_git_bash.html)
    - Create a new local folder after checking directories
    - Pull from remote after prompting for password
    - [Sample bash file](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_basics/pull_one)
2. [Multiple git Repositories setup with Github](https://fanwangecon.github.io/Tex4Econ/nontex/install/git/fs_git_setup.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/install/git/fs_git_setup.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/install/git/fs_git_setup.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/install/git/fs_git_setup.html)
    - set up ssh rsa security with github
    - initalize multiple repositories
    - secure ssh session to avoid passphrase entry
    - *mkdir d1 d2; git config --global; git init; git remote add*
    - *eval "$(ssh-agent)"; ssh-add ~/.ssh/id_rsa*
    - *git pull github master; git pull -u github master*
3. [Basic Git Commands](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_basics/fs_git_basics.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/git/g_basics/fs_git_basics.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_basics/fs_git_basics.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_basics/fs_git_basics.html)
    - Git check file status
4. [Sample Githug page](https://fanwangecon.github.io/Tex4Econ/nontex/githubpages/sample/): [**md**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/githubpages/sample/samplepage.md) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/githubpages/sample/)
    - Conda base Python, and Conda environment for R
    - *conda update --all*
    - *Rtools, install.packages(), devtools::install_github()*
4. [Git Subtree](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_subtree/fs_subtree.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/git/g_subtree/fs_subtree.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_subtree/fs_subtree.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_subtree/fs_subtree.html)
    - dropbox folder as main project git
    - subfolder also as git subtree synced to overleaf
    - **git**: *git subtree add, push, pull*

# 6 reveal.js

## 6.1 reveal.js Basic Examples

1. Go to the latest [reveal.js release](https://github.com/hakimel/reveal.js/releases)
    - go to the end of the latest release's release info, look for zip file and download
    - just open the zipped folder, the index.html is already working.
2. To allow multiple files to share the same *css*, *js*, *lib*, and *plugin*, create a folder to put these folders from the zipped file.
    - in a *present* folder that is parallel to the *css*, *js*, and other folders, put in there testing and other html files.
    - replace links to css, js, lib and plugin in the testing files

## 6.2 Default Tests

1. [Default Testing File](http://fanwangecon.github.io/Tex4Econ/nontex/revealjs/test/index.html)
2. [Default Demo File](http://fanwangecon.github.io/Tex4Econ/nontex/revealjs/test/demo.html)
3. [Modified Math Presentation](http://fanwangecon.github.io/Tex4Econ/nontex/revealjs/test/math.html)

## 6.3 Rmd and revealjs

1. [Revealjs Rmd and PDF](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_img.html): [**Rmd**](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_img.Rmd) \| [**pdf**](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_img.pdf) \| [**html**](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_img.html)
    - R for revealjs, include pictures
    - convert to PDF using [decktape](https://github.com/astefanutti/decktape)
    - **git**: *git subtree add, push, pull*
2. [Revealjs Rmd, Tex and PDF](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_tex.html): [**Rmd**](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_tex.Rmd) \| [**pdf**](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_tex.pdf) \| [**html**](http://fanwangecon.github.io/Tex4Econ/nontex/revealjsrmd/test_tex.html)
    - R for revealjs, include equations, newcommands
    - Include child tex files that define a set of newcommands
    - convert to PDF using [decktape](https://github.com/astefanutti/decktape)
    - **git**: *git subtree add, push, pull*

* * *

Please contact [![](https://img.shields.io/github/followers/fanwangecon?label=FanWangEcon&style=social)](https://github.com/FanWangEcon) [![](https://img.shields.io/twitter/follow/fanwangecon?label=%20&style=social)](https://twitter.com/fanwangecon) for issues or problems.

[![DOI](https://zenodo.org/badge/182257793.svg)](https://zenodo.org/badge/latestdoi/182257793)

![RepoSize](https://img.shields.io/github/repo-size/fanwangecon/Tex4Econ)
![CodeSize](https://img.shields.io/github/languages/code-size/fanwangecon/Tex4Econ)
![Language](https://img.shields.io/github/languages/top/fanwangecon/Tex4Econ)
![Release](https://img.shields.io/github/downloads/fanwangecon/Tex4Econ/total)
![License](https://img.shields.io/github/license/fanwangecon/Tex4Econ)

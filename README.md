[![HitCount](http://hits.dwyl.io/fanwangecon/Tex4Econ.svg)](https://github.com/FanWangEcon/Tex4Econ)  [![Star](https://img.shields.io/github/stars/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/stargazers) [![Fork](https://img.shields.io/github/forks/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/network/members) [![Star](https://img.shields.io/github/watchers/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/watchers)

This is a work-in-progress [website](https://fanwangecon.github.io/Tex4Econ/) of support files for writing various files with latex, produced by [Fan](https://fanwangecon.github.io/). The project includes sample file for papers, exams, homeworks, etc.

From [Fan](https://fanwangecon.github.io/)'s other repositories: For dynamic borrowing and savings problems, see [Dynamic Asset Repository](https://fanwangecon.github.io/CodeDynaAsset/); For code examples, see also [Matlab Example Code](https://fanwangecon.github.io/M4Econ/), [R Example Code](https://fanwangecon.github.io/R4Econ/) and [Stata Example Code](https://fanwangecon.github.io/Stata4Econ/); For intro econ with Matlab, see [Intro Mathematics for Economists](https://fanwangecon.github.io/Math4Econ/), and for intro stat with R, see [Intro Statistics for Undergraduates](https://fanwangecon.github.io/Stat4Econ/). See [here](https://github.com/FanWangEcon) for all of [Fan](https://fanwangecon.github.io/)'s public repositories.

Materials gathered from various [projects](https://fanwangecon.github.io/research) in which latex is used. The goal of this repository is to make it easier to find/re-use latex files produced for various projects.

[![](https://img.shields.io/github/last-commit/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/commits/master) [![](https://img.shields.io/github/commit-activity/m/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/graphs/commit-activity) [![](https://img.shields.io/github/issues/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/issues) [![](https://img.shields.io/github/issues-pr/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/pulls)

# 1. Latex Bib, Equations, Tables, Figures

## 1.1 [References](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference)

1.  [Biblatex Citation and Bibliography](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/biblatex_basic): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/biblatex_basic/biblatex_test.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/reference/biblatex_basic/biblatex_test.pdf)
    - *biblatex-chicago; \textcite{becker_human_1986}; \autocite{becker_human_1986}*
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

## 1.4 [Estimates Table](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/)

1.  [Multi-Panel Estimation Table](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_6col_cts_dis2inter.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_6col_cts_dis2inter.pdf)
2.  [Small Estimates Table](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates/estismall.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates/estismall.pdf)

## 1.5 [TIKZ](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/)

1. [Tikz Page Layout](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/positioning): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/positioning/fs_tikz_position.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/positioning/fs_tikz_position.pdf)
    - relative positioning, proportional to textwidth
    - two or four subfigures
2. [Tikz Timeline](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline.pdf)
    - straight and curved connected lines
3. [Tikz Dynamically Sized Eight Pane Model Timeline](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline_8pane.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline_8pane.pdf)
    - Dynamically sized panes for prior, current and next periods, with left and right in current period
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

# 3. Overleaf Integration and Template

In overleaf, click on New Project, choose upload project, then select zip below.

1.  [Template Figure Table and Reference](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/draft.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/draft.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_imgtabref/fantemplate_basic_imgtabref.zip)
2.  [Template Figure Table and Reference Roman 12 Double Space](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/draft.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/draft.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_basic_roman/fantemplate_basic_roman.zip)
3.  [Template Paper, Response to Referees, Section Numbering and Bib](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/draft.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/draft.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_paper_rr_response/fantemplate_paper_rr_response.zip)
    -   figures, tables, references
    -   separate page numbers for each section: _\\renewcommand{\\thesection}{\\arabic{section}}_
    -   separate heading count for responses to referees: _\\setcounter{section}{0}_
    -   separate bibliographies: _refsection_
4.  [Template Recommendation Letter](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/recommendation.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/recommendation.pdf) \| [**zip**](https://github.com/FanWangEcon/Tex4Econ/blob/master/template/fantemplate_recommendation/fantemplate_recommendation.zip)
    -   recommendation letter with logo and signature
    -   contact and address panel

## 3.4 Github Integration

This [overleaf project](https://www.overleaf.com/read/xjsqdwrkfrhq) is synced with this git repository. You can clone the project, pull project to overleaf, and compile in overleaf browser. Specifically: clone the repo; go to your overleaf account and create a project; click on menu under sync with git/github.

The writing/structure is to:
1. Store latex formatting file etc in separate files away from paper tex.
2. For papers, write in tex fragments stored in separate files. Main tex paper file mainly contains structure/outline.
3. Files synced through git/github, pull from github to edit/share with co-authors on [overleaf.com](https://overleaf.com) or edit locally.

Please contact [FanWangEcon](https://fanwangecon.github.io/) for issues or problems.

# 4. [One File Article](https://github.com/FanWangEcon/Tex4Econ/blob/master/singlefile_article/article_fan.tex)

For papers that are not too long, we might write all tex contents on the same page. This is the example single-file paper [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/singlefile_article/article_fan.tex) file, and this is the   [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/singlefile_article/article_fan.pdf) output. Even for single-file papers, various paper components listed below should be stored separately for clarity and convenience.

The paper [**preamble**](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/preamble_main.tex) is stored in its own file, and loads in the packages and settings, statistics/phrases/math, and citation from tex fragments listed below. A clear separation should be kept between these files, with the main [**preamble**](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/preamble_main.tex) only loading inputs in.

The preamble file can be inserted at the top of a full paper file, for example at the top of this [**multi-section file**](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main.tex).

For one-file article, we could directly load in the various tex fragments below. For example, we load these packages below into [**this file**](https://github.com/FanWangEcon/Tex4Econ/blob/master/singlefile_article/article_fan.tex).

-   **Numbers/Phrases/Math**: various tex fragments store key file components in separate files
    -   [_Numbers_](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/stats/stats_one.tex): Sometimes, we want to use the same number if various spots in the paper, these numbers should be stored as newcommands so that the number can be updated in one spot.
    -   [_Often Used Phrases_](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/shorthand/short_text.tex): Generally, there are terms that are used often in a paper. To make it easy to change these terms or to avoid having to rewrite over and over again, these terms could be stored as new commands.
    -   [_Often Used Math_](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/shorthand/short_math.tex): We might need to reuse various Math Symbols or parts of equations, they should also be stored as newcommands.
    -   The aggregate [_PDF_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main.pdf) file, compiling all subsection tex files together.
    -   The [_overleaf_](https://www.overleaf.com/read/xjsqdwrkfrhq) file, allowing for live compilation.
-   **Citation**: structure to cite efficiently
    -   [_Preamble Settings_](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/cite/cite_preamble.tex): One file to be loaded into preambles sets citation settings.
    -   [_End File Citation Settings_](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/cite/cite_end.tex): One file to be loaded at the end of the paper that determines bibliography text display.
    -   [_bib Files_](https://github.com/FanWangEcon/Tex4Econ/tree/master/_bib): Various bib files loaded from [zotero](https://www.zotero.org/) stored in own folder. Sync directly to zotero via overleaf.
-   **Packages and Settings**: Package loading etc.
    -   [_Package Loading_](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/preamble_one.tex)
    -   [_Additional Packages and Settings_](https://github.com/FanWangEcon/Tex4Econ/blob/master/fragments/preamble_two.tex)

# 5. [Multi-Section Article](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main.tex)

When a paper is longer, it could be difficult to manage long latex files. Compiling could take long periods of time if the full paper requires compilation for any edits in a subsection. The structure below allows for editing paper in subsections and compiling by sections. The structure works locally as well as remotely on browser based compiler.

We compile together two files with the same structure:
1. [Multi-section blank template](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main_blank.pdf) has no contents in the sections, useful for copy/cloning when starting new projects
2. [Multi-section template with contents](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main.pdf) has sample contents in sections, demonstrates what the file looks like filled up.

Inside [**overleaf**](https://www.overleaf.com/read/xjsqdwrkfrhq), the aggregate tex file that combines all sections together should be set as the main/default file under project options. Then as subsection text fragments are edited inside overleaf, the full pdf file is updated on the right showing current changes.

The same [**bib**](https://github.com/FanWangEcon/Tex4Econ/tree/master/_bib) file structure and [**preamble fragments**](https://github.com/FanWangEcon/Tex4Econ/tree/master/fragments) structure is used here as in the single file case above.

-   **Aggregate Tex and PDF**: combine subsections together in one joint overall paper file
    -   The aggregate [_tex_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main.tex) file, only showing section and subsection headings.
    -   The aggregate [_PDF_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main.pdf) file, compiling all subsection tex files together.
    -   The [_overleaf_](https://www.overleaf.com/read/xjsqdwrkfrhq) file, allowing for live compilation.
-   **Section PDF Compiles**: compile each section separately to reduce compile time and file length.
    -   Introduction Conclusion Section: [_Tex Compile_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_sandbox/introconclude_sandbox.tex), [_PDF_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_sandbox/introconclude_sandbox.pdf)
    -   Model Section: [_Tex Compile_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_sandbox/model_sandbox.tex), [_PDF_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_sandbox/model_sandbox.pdf)
    -   Estimation Section: [_Tex Compile_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_sandbox/estimate_sandbox.tex), [_PDF_](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_sandbox/estimate_sandbox.pdf)
-   **Section Folders**: each section has own folder.
    -   [Introduction Conclusion Section Folder](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/introconclude/)
    -   [Model Section Folder](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/model/)
    -   [Estimation Section Folder](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/esti/)
-   **Section Main Tex Files**: this file gathers subsection inputs together, used for section by section compilation
    -   [Introduction Conclusion Section Main File](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/introconclude/main.tex)
    -   [Model Section Main File](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/model/model_main.tex)
    -   [Estimation Section Main File](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/esti/esti_main.tex)
-   **Subsection Tex Files**: each subsection has own tex file:
    -   [Introduction](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/introconclude/intro.tex) from the intro and conclusion folder.
    -   [Conclusion](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/introconclude/conclude.tex) from the intro and conclusion folder.
    -   [Literature review](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/introconclude/literature.tex) from the intro and conclusion folder.
    -   [Introduction](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/introconclude/intro.tex) from the intro and conclusion folder.
    -   [Conclusion](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/introconclude/conclude.tex) from the intro and conclusion folder.
    -   [Model Subsection One](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/model/model_one.tex) from the model folder.
    -   [Model Subsection Two](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections/model/model_one.tex) from the model folder.

# 6. Program Installations

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


# 7. gitpages and git

1. [Multiple git Repositories setup with Github](https://fanwangecon.github.io/Tex4Econ/nontex/install/git/fs_git_setup.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/install/git/fs_git_setup.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/install/git/fs_git_setup.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/install/git/fs_git_setup.html)
    - set up ssh rsa security with github
    - initalize multiple repositories
    - secure ssh session to avoid passphrase entry
    - *mkdir d1 d2; git config --global; git init; git remote add*
    - *eval "$(ssh-agent)"; ssh-add ~/.ssh/id_rsa*
    - *git pull github master; git pull -u github master*
2. [Sample Githug page](https://fanwangecon.github.io/Tex4Econ/nontex/githubpages/sample/): [**md**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/githubpages/sample/samplepage.md) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/githubpages/sample/)
    - Conda base Python, and Conda environment for R
    - *conda update --all*
    - *Rtools, install.packages(), devtools::install_github()*
3. [Git Subtree](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_subtree/fs_subtree.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/git/g_subtree/fs_subtree.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_subtree/fs_subtree.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/git/g_subtree/fs_subtree.html)
    - dropbox folder as main project git
    - subfolder also as git subtree synced to overleaf
    - **git**: *git subtree add, push, pull*

# 8 reveal.js

## 8.1 reveal.js Basic Examples

1. Go to the latest [reveal.js release](https://github.com/hakimel/reveal.js/releases)
    - go to the end of the latest release's release info, look for zip file and download
    - just open the zipped folder, the index.html is already working.
2. To allow multiple files to share the same *css*, *js*, *lib*, and *plugin*, create a folder to put these folders from the zipped file.
    - in a *present* folder that is parallel to the *css*, *js*, and other folders, put in there testing and other html files.
    - replace links to css, js, lib and plugin in the testing files

## 8.2 Default Tests

1. [Default Testing File](http://fanwangecon.github.io/Tex4Econ/nontex/revealjs/test/index.html)
2. [Default Demo File](http://fanwangecon.github.io/Tex4Econ/nontex/revealjs/test/demo.html)
3. [Modified Math Presentation](http://fanwangecon.github.io/Tex4Econ/nontex/revealjs/test/math.html)

## 8.3 Rmd and revealjs

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

![RepoSize](https://img.shields.io/github/repo-size/fanwangecon/Tex4Econ)
![CodeSize](https://img.shields.io/github/languages/code-size/fanwangecon/Tex4Econ)
![Language](https://img.shields.io/github/languages/top/fanwangecon/Tex4Econ)
![Release](https://img.shields.io/github/downloads/fanwangecon/Tex4Econ/total)
![License](https://img.shields.io/github/license/fanwangecon/Tex4Econ)

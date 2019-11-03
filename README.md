[![HitCount](http://hits.dwyl.io/fanwangecon/Tex4Econ.svg)](https://github.com/FanWangEcon/Tex4Econ)  [![Star](https://img.shields.io/github/stars/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/stargazers) [![Fork](https://img.shields.io/github/forks/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/network/members) [![Star](https://img.shields.io/github/watchers/fanwangecon/Tex4Econ?style=social)](https://github.com/FanWangEcon/Tex4Econ/watchers)

This is a work-in-progress [website](https://fanwangecon.github.io/Tex4Econ/) of support files for writing various files with latex, produced by [Fan](https://fanwangecon.github.io/). The project includes sample file for papers, exams, homeworks, etc.

Materials gathered from various [projects](https://fanwangecon.github.io/research) in which latex is used. The goal of this repository is to make it easier to find/re-use latex files produced for various projects.

[![](https://img.shields.io/github/last-commit/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/commits/master) [![](https://img.shields.io/github/commit-activity/m/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/graphs/commit-activity) [![](https://img.shields.io/github/issues/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/issues) [![](https://img.shields.io/github/issues-pr/fanwangecon/Tex4Econ)](https://github.com/FanWangEcon/Tex4Econ/pulls)

# 1. Latex Tools

## 1.1 Estimates Table

1.  [Multi-Panel Estimation Table](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_6col_cts_dis2inter.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/multipanel/tab_6col_cts_dis2inter.pdf)
2.  [Small Estimates Table](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates/estismall.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_tab/estimates/estismall.pdf)

## 1.2 TIKZ

1.  [Tikz Timeline](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/tikz/timeline/timeline.pdf)

## 1.3 Conversion

1.  [Pandoc File Conversion](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/pandoc): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/pandoc/fansample.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_other/pandoc/fansample.pdf)

# 2. Latex Layout

## 2.1 Sizing

1.  [Reduce Line-Gap](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/spacing/reduce): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/spacing/reduce/reduce.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/spacing/reduce/reduce.pdf)

## 2.2 Footer and Headers

1.  [Repaginate Response for Referees](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/foothead/repage): [**tex**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/foothead/repage/repage_response_referee.tex) \| [**pdf**](https://github.com/FanWangEcon/Tex4Econ/blob/master/_support/foothead/repage/repage_response_referee.pdf)

# 3. Overleaf Integration

This [overleaf project](https://www.overleaf.com/read/xjsqdwrkfrhq) is synced with this git repository. You can clone the project, pull project to overleaf, and compile in overleaf browser. Specifically: clone the repo; go to your overleaf account and create a project; click on menu under sync with git/github.

The writing/structure is to:
1\. Store latex formatting file etc in separate files away from paper tex.
2\. For papers, write in tex fragments stored in separate files. Main tex paper file mainly contains structure/outline.
3\. Files synced through git/github, pull from github to edit/share with co-authors on [overleaf.com](https://overleaf.com) or edit locally.

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
1\. [Multi-section blank template](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main_blank.pdf) has no contents in the sections, useful for copy/cloning when starting new projects
2\. [Multi-section template with contents](https://github.com/FanWangEcon/Tex4Econ/blob/master/sections_combine/draft_main.pdf) has sample contents in sections, demonstrates what the file looks like filled up.

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

# 6. Miscellaneous Files

Go to [fan](http://fanwangecon.github.io/)'s [Miscellaneous Repository](http://fanwangecon.github.io/Tex4Econ/nontex/) with support files for git, github, and github pages, and others.

* * *

Please contact [![](https://img.shields.io/github/followers/fanwangecon?label=FanWangEcon&style=social)](https://github.com/FanWangEcon) [![](https://img.shields.io/twitter/follow/fanwangecon?label=%20&style=social)](https://twitter.com/fanwangecon) for issues or problems.

![RepoSize](https://img.shields.io/github/repo-size/fanwangecon/Tex4Econ)
![CodeSize](https://img.shields.io/github/languages/code-size/fanwangecon/Tex4Econ)
![Language](https://img.shields.io/github/languages/top/fanwangecon/Tex4Econ)
![Release](https://img.shields.io/github/downloads/fanwangecon/Tex4Econ/total)
![License](https://img.shields.io/github/license/fanwangecon/Tex4Econ)

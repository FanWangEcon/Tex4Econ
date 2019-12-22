This is a work-in-progress [website](https://fanwangecon.github.io/Tex4Econ/nontex) of miscellaneous research support files, produced by [Fan](https://fanwangecon.github.io/). Materials include miscellaneous git,  github and github pages issues.

From [Fan](https://fanwangecon.github.io/)'s other repositories: For dynamic borrowing and savings problems, see [Dynamic Asset Repository](https://fanwangecon.github.io/CodeDynaAsset/); For example code, see [M4Econ](https://fanwangecon.github.io/M4Econ/) for Matlab, [R4Econ](https://fanwangecon.github.io/R4Econ/) for R, and [Stata4Econ](https://fanwangecon.github.io/Stata4Econ/) for Stata; For intro econ with Matlab, see [Intro Mathematics for Economists](https://fanwangecon.github.io/Math4Econ/), and for intro stat with R, see [Intro Statistics for Undergraduates](https://fanwangecon.github.io/Stat4Econ/). See [here](https://github.com/FanWangEcon) for all of [Fan](https://fanwangecon.github.io/)'s public repositories.

Please contact [FanWangEcon](https://fanwangecon.github.io/) for issues or problems.

# Installations

1. [Software Updates: Python (Conda), R (R-studio), etc](https://fanwangecon.github.io/Tex4Econ/nontex/install/windows/fn_installations.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/install/windows/fn_installations.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/install/windows/fn_installations.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/install/windows/fn_installations.html)
    - Conda base Python, and Conda environment for R
    - *conda update --all*
    - *Rtools, install.packages(), devtools::install_github()*
2. [Atom, Git, Github, etc Set-up for Linux](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_ubuntu.html): [**Rmd**](https://github.com/FanWangEcon/Tex4Econ/blob/master/nontex/install/linux/fn_ubuntu.Rmd) \| [**pdf**](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_ubuntu.pdf) \| [**html**](https://fanwangecon.github.io/Tex4Econ/nontex/install/linux/fn_ubuntu.html)
    - *sudo apt-get install atom; install git*
    - *git init; config; git remote add; git pull*
    - *wget; bash; source*
    - *ssh-keygen -t rsa; cat*

# github pages and git

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

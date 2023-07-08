setup an emacs environment with doom and spacemacs

how to setup environment
=================

1. clone this repo with

``` bash
git clone git@github.com:eccnil/dotfile --recursive
```

1. need to install doomemacs

``` bash
mkdir ~/.emacs_profiles/
git clone --depth 1 https://github.com/doomemacs/doomemacs ~/.emacs_profiles/doom-emacs
~/.emacs_profiles/doom-emacs/bin/doom install
```
1. need to install spacemacs

``` bash
git clone https://github.com/syl20bnr/spacemacs ~/.emacs_profiles/spacemacs
```

that give us the stable branch (boring)

``` bash
cd  ~/.emacs_profiles/spacemacs
git switch develop
git pull
```

1. apply configuration

``` bash
make all
```

try it with

``` bash
emacs --with profile doom
```

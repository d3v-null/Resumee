# Compiling

## Install submodules

```bash
git submodule update --init --recursive
```

## Install LaTeX

```bash
brew cask install basictex
```

## install LaTeX modules / fonts

```bash
tlmgr install titlesec framed threeparttable wrapfig multirow enumitem bbding titling tabu mdframed tcolorbox textpos import varwidth needspace tocloft ntheorem environ trimspaces xifthen ifmtarg latexmk collection-fontsrecommended fontawesome sourcesanspro
```

## Install otf fonts:

- <https://fontawesome.com/v4.7.0/assets/font-awesome-4.7.0.zip>

## Compile to LaTeX

```bash
xelatex resumee_derwent.tex
```

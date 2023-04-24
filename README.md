# dvcr: A DVC implementation in R

Data Version Control (dvc) is a python tool <http://dvc.org> that
provides data version control using git but only for hashes of files. The
files themselves are managed outside of git (due to size constraints). DVC
offers a way to combine data and R code without creating very large packages
that are difficult to manage and distribute. This package wraps DVC in R
functions to integrate into data science workflows. It is inspired by an
existing package, <https://github.com/andrewcstewart/dvc-r>. The goal of this
software is to create a minimalist wrapper around dvc.

tikzdotncross
==========

Set of macros for defining/marking coordinates and crossing paths (with jumps).


For more details,  see the documentation,
[tikzdotncross.pdf](http://mirrors.ctan.org/graphics/pgf/contrib/tikzdotncross/doc/tikzdotncross.pdf)

--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*)

That, besides, pgf/TikZ

## Installation
The stable version is available at [CTAN](https://ctan.org/pkg/tikzdotncross).

## Usage
### Stable version
Just place
```latex
  \usepackage{tikzdotncross}
```

in the preamble and compile away.


Be aware that options might change between versions, so you have to check them manually.


## Contacting Author

For bug reports and enhancement suggestions, the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/tikzdotncross/issues).
Please be ready to provide an example code showing the bug, if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/tikzdotncross

-------------
Copyright 2024-present by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), version 1.3c (or later), and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consists of the files

* tikzdotncross.sty
    - The Package itself

* README.md (this file)
    - quick introduction

* tikzdotncross.tex
    - package documentation

* tikzdotncross.pdf
    - documentation in PDF format

-------------
* Version 1.3 (this)
    - typos. adding \showcoords alternate form. rewriting the TeX part as expl
    - switching over pkginfograb package's info

* Version 1.2b/1.2c
    - correcting package dependencies snafu (issue #1).

* Version 1.2 
    - Added some package options, to change pin defaults, see documentation.

* Version 1.1 
    - Documentation typos and improvement. Code cleanup.
 
* Version 1.0
    - Initial release by CTAN.

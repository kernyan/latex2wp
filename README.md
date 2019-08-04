# latex2wp
tex to wordpress html conversion python tool

# Usage
- Write tex code between "\begin{document}", "\end{document}" of post-template.tex
- place target tex file, macrosblog.tex, latex2wp.py, latex2wpstyle.py in same directory
- run python latex2wp.py *target_tex_file.tex*

# Output
- *target_tex_file.html*

# Change log
## Aug 4, 2019
- added support for \begin{equation\*}
- added support for \begin{eqnarray}

# Change log before fork
- v0.6.2 in May  6, 2009
- v0.6.1 in Feb 23, 2009
- v0.6   in Feb 21, 2009

# Doesn't work
- Currently, for eqnarray, and equation, instead of numbering multiline equations individually,
the whole \begin{equation/eqnarray} block are numbered as one equation
- align not supported
- \medskip, and \bigskip not supported
- \subsubsection not supported
- bibliographic references, and footnotes not supported

# Notes
- Fork from [Luca Trevisan's original code](https://lucatrevisan.wordpress.com/latex-to-wordpress/)

Use pdflatex to compile.

Use `texindy -L russian -C koi8-r -o algebra-koi.ind algebra.idx && iconv -f koi8-r -t utf-8 algebra-koi.ind > algebra.ind && rm algebra-koi.ind` to rebuild index.

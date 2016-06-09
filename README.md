Use pdflatex to compile.
To rebuild index you need to prepare your texindy installation:

* find the files `tex/inputenc/*.xdy`;
* convert, say, cp1251.xdy to utf with `iconv -f cp1251 -t utf8 cp1251.xdy | sudo tee utf8.xdy` or something like that.

Now you have the correct utf8.xdy! Use `texindy -L russian --codepage utf8 algebra.idx` to rebuild index.

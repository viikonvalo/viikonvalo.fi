<!--
Title: LyX
Template: comments
-->

Olen kokeillut Lyx:ssä ja
:   Anonymous 19. Heinäkuu 2011 - 16:47
:   Olen kokeillut Lyx :ssä ja myös erillisellä .tex tiedostolla seuraavia:
    \usepackage{graphics} \includegraphics{kuva.eps} mutta erillisellä .tex
    tiedostolla päätteessä pdflatex tiedosto.tex: ! LaTeX Error: Unknown graphics
    extension: .eps. Lyx:ssä: The control sequence at the end of the top line of
    your error message was never \def'ed. If you have misspelled it (e.g., `\hobx'),
    type `I' and the correct spelling (e.g., `I\hbox'). Otherwise just continue, and
    I'll forget about whatever was undefined. Olen kyllä käytttänyt aikoinaan Latexia
    emacsin kanssa ja vastaavat toiminnot ovat toimineet. 

Olet varmaan aiemmin Latexia
:   pesasa 19. Heinäkuu 2011 - 21:21
:   Olet varmaan aiemmin Latexia käyttäessäsi kääntänyt tiedostot latex-komennolla
    dvi:ksi, dvips-komennolla ps:ksi ja ehkä vielä ps2pdf-komennolla pdf-tiedostoksi.
    Lyx käyttää kuitenkin pdflatex-komentoa, joka kääntää tiedoston suoraan pdf:ksi.
    Pdflatex ei huoli eps-kuvia vaan ne pitää ensin kääntää johonkin muuhun muotoon.
    Esimerkiksi pdf-tiedostoiksi. LyXille kelpaavat myös svg-tiedostot.
    
    Eps-kuvan voi kääntää esimerkiksi epstopdf-ohjelmalla komentoriviltä tai
    Inkscapella graafisesti.

Tekstiä Lyx:llä
:   Anonymous 23. Kesäkuu 2011 - 3:07
:   OS/2:ssa! Pitääkös nyt sitten kesällä vielä kaivella se ossi esille, jotta pääsee
    vielä silläkin kokeilemaan wysiwyg:n lisäksi wysiwym:iä? 
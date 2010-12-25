BME Diplomaterv LaTeX sablon 
============================

A [Diplomaterv Portál](http://diplomaterv.vik.bme.hu/)on lévő .doc fájl
alapján készített LaTeX sablon.

**Nem hivatalos, saját felelősségre használd!**

Használat
---------

A *pdflatex* használatát javaslom, a kimenetet közvetlenül pdfben állítja elő
illetve jpg és png képek postscriptté konvertálás nélkül használhatóak.

    pdflatex dolgozat.tex

Ha mégsem pdflatex-et használsz, a címlaphoz ajánlom a *fig/bmelogo.ps* fájlt. 

Apróságok
---------

* A fájlok UTF8 kódolásúak. Deal with it. 

* [Magyar LaTeX segítség](http://www.math.bme.hu/latex/)

* Vimet a `:set tw=78` paranccsal ráveheted, hogy automatikusan törje a sorokat
78 karakter után. Folytonos állítgatás helyett érdemesebb az alábbi sort
elhelyezni valahol a tex forrásfájlban, pl. az utolsó sorban.

    % vim: tw=78


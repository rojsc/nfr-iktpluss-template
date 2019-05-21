# Template for NFR IKTPLUSS grant proposal

LaTeX-malen antar at du har installert skrifttypene Times New Roman, Calibri,
og XITS Math. XITS Math følger med LaTeX-pakken `xits`.  Om du ikke får tak i
disse skrifttypene, så kan du bytte dem ut med kloner, f.eks. XITS i stedet for
Times New Roman og Carlito i stedet for Calibri.  Selv om kloneskrifttypene er
ekstremt like de opprinnelige, så bryter du da instruksjonen fra
Forskningsrådet som sier at man skal bruke Arial, Calibri eller Times New
Roman.

Bruk LuaLaTeX til kompilering, og Biber til bibliografi.
Det enkleste er å bruke Latexmk:
```bash
latexmk -lualatex nfr-iktpluss-template
```

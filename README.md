# Preuzimanje

Preuzeli smo 202_tekst_python.tex datoteku sa merlina.

# Konverzija

Datoteku smo otvorili u VSC-u te smo je konvertirali u markdown ekstenziju na sljedeći način:
 1. Otvorili smo tekst datoteku
 2. Otvorili terminal
 3. Pomoću naredbe:
    
    ```
    pandoc 202_tekst_python.tex -o 202_tekst_python.md
    ```
    Konvertirali smo .tex u .md

# GitHub

Kreirali smo novi repozitorij na GitHub-u, te uploadali 202_tekst_python.md datoteku.
Kreator repozitorija je pozvao suradnika da bude kolaborator.
Unutar GitHub editora smo ispravili greške u konverziji, te comittali promjene u **MAIN** branch.

# Prije/Poslije

**Prije:**

:::python

Umetanje teksta u drugi tekst:

\>\>\> tekst = \"\"\"

Bio sam u {mjesto}.

Tamo sam {radnja}. Bilo mi je {kako} jer je vrijeme u {mjesto} bilo {vrijeme}.

\"\"\"

\>\>\> t = tekst.format(mjesto = 'Zadru', radnja='se kupao', kako='sjajno', vrijeme='lijepo')

\>\>\> print(t)

Bio sam u Zadru.

Tamo sam se kupao. Bilo mi je sjajno jer je vrijeme u Zadru bilo lijepo.

:::


**Poslije:**

(```)python     (bez zagrada)

Umetanje teksta u drugi tekst:

\>\>\> tekst = \"\"\"

Bio sam u {mjesto}.

Tamo sam {radnja}. Bilo mi je {kako} jer je vrijeme u {mjesto} bilo {vrijeme}.

\"\"\"

\>\>\> t = tekst.format(mjesto = 'Zadru', radnja='se kupao', kako='sjajno', vrijeme='lijepo')

\>\>\> print(t)

Bio sam u Zadru.

Tamo sam se kupao. Bilo mi je sjajno jer je vrijeme u Zadru bilo lijepo.

(```)            (bez zagrada)

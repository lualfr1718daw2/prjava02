# prjava02

1 - git branch branca00
    git checkout branca00
    git status
5 - git checkout master
    En el historial de la branca master unicament es veu el commit inicial, i en el de la branca00 es veu tambe el ultim commit realitzat desde la branca
6 - No veiem la ultima linea afegida ja que hem cambiat a la branca master
7 - Ara ja podem veure la ultima linea ja que hem tornat a la branca00
10 - git checkout master
     git merge branca00
     Ara el fitxer conte totes les lineas de les que hem fet commit a branca00
12 - git push -u origin master
     Ja que en el comandament hem especificat que volem fer un PUSH unicament de la branca master
14 - git push -u origin branca01
     Ara hi han dos branques, master amb 3 commits i branca01 amb 4 commits

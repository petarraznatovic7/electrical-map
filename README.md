# Mapa Osigurača

Interaktivna vizualizacija električne instalacije stana sa mapiranjem osigurača, utičnica i prekidača.

## Opis

Web aplikacija koja prikazuje nacrt stana sa svim električnim elementima i njihovom povezanošću sa razvodnom tablom. Omogućava brzo pronalaženje koji osigurač kontroliše koju utičnicu ili prekidač. 
Generalno ne znam kojim redom se i kako povezuje sa razvodne table, tako da nacrt je napravljen onako kako meni odgovara i olakšava da brzo vidim koji osigurač mi je vezan za koji potrošač kao i na kojim utičnicama nemam uzemljenje (da ih izbegavam :) 

## Funkcionalnosti
- **Interaktivna mapa** - SVG vizualizacija sa svim sobama
- **Filtriranje** - Po osiguračima, vrsti (utičnica/prekidač), uzemljenju i sobama
- **Dinamički brojači** - Prikaz broja elemenata po filteru u realnom vremenu
- **Tooltip informacije** - Detalji o svakom elementu (osigurač, uzemljenje, povezani uređaji)
- **Vizualno kodiranje** - Boje prema statusu uzemljenja (zeleno: DA, crveno: NE)
- **Prikaz povezanosti** - Linije pokazuju parent-child veze između elemenata (ovo verovatno nije pravilno urađeno, ali da ne bih imao milion strelica sa razvodne kutije, dozne i ostalo odlučio sam se za ovaj primitivan pristup)
- **Responsive dizajn** - Prilagođeno za desktop i mobilne uređaje
- **Mobile bottom sheet** - Tooltip na dodir za mobilne uređaje

## Pokretanje
Otvorite `index.html` u web pregledaču. Nije potreban server. Potrebno je predefinisati koordinate prostorija kao i utičnica.

Demo: https://petarraznatovic7.github.io/electrical-map/

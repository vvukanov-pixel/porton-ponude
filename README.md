# PORTON ponude

Otvorena web aplikacija za A4 ponude sobnih vrata PORTON (cjenik 2026/2027).

## Što radi
- Unos kupca, modela, dekora, dimenzija, štoka, količine
- Cijene iz cjenika 2026/2027 (FALC, FILO, FILO MURO, SLIDE 2/3)
- FILO MURO: do 214 cm = niži razred, od 215 cm = viši
- Postotak na cijenu, montaža i dostava po komadu
- Svaka nova ponuda dobiva broj P-GGMMDD-001 (brojač u pregledniku)
- Print / Spremi kao PDF — gore praznina za memorandum

Nema logina. Tko ima link, može raditi ponude.

## GitHub + Vercel

1. Novi repo na GitHubu, npr. porton-ponude
2. Uploadaj datoteke: index.html, README.md, vercel.json
3. Na Vercelu: Add New Project → import repo → Deploy

Ili lokalno otvori index.html u pregledniku.

## Broj ponude
Brojač je u pregledniku (localStorage). Na drugom računalu isti dan kreće od 001. Gumb "Novi broj" daje sljedeći.

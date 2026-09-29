# GitHowTo harjutusprojekt

See projekt on minu praktiline kokkuvõte GitHowTo harjutustest. Lõin lihtsa
HTML-lehe, lisasin sellele CSS-kujunduse ning kasutasin Git'i muudatuste
jälgimiseks, harude loomiseks ja ühendamiseks. Harjutuste käigus nägin, kuidas
Git säilitab projekti ajaloo ning aitab ka ekslikke muudatusi turvaliselt
parandada.

## Mida ma õppisin

- Git-repositooriumi oleku kontrollimine ja ajaloo vaatamine
- failide lisamine staging-alasse ning muudatuste commit'imine
- commit'ide parandamine, tühistamine ja taastamine
- tag'ide loomine ja eemaldamine
- uue haru loomine ning harude vahel liikumine
- failide ümbernimetamine ja teisaldamine
- harude ühendamine ning merge-konflikti lahendamine
- kohaliku repositooriumi sidumine GitHubiga

Harjutuste juhendina kasutasin [GitHowTo veebilehte](https://githowto.com/).

## Kasutatud Git käsud

Repo hetkeolukorda kontrollisin käsuga `git status`. Muudatuse salvestamiseks
kasutasin tavaliselt järgmisi käske:

```bash
git status
git add README.md
git commit -m "Kirjelda tehtud muudatust"
git log --oneline
```

Lisaks kasutasin harudega töötamiseks käske `git branch`, `git switch` ja
`git merge`. Varasemate sammude juures kasutasin ka käske `git revert`,
`git reset`, `git tag` ja `git mv`.

### Git'i põhitöövoog

1. Muudan või loon töökaustas faile.
2. Kontrollin muudatusi käsuga `git status`.
3. Lisan valitud muudatused staging-alasse käsuga `git add`.
4. Salvestan muudatused commit'ina käsuga `git commit`.
5. Vaatan vajadusel ajalugu käsuga `git log`.
6. Saadan commit'id GitHubi käsuga `git push`.

### Õpitulemuste kontrollnimekiri

- [x] Oskan kontrollida repositooriumi olekut
- [x] Oskan luua ja muuta commit'e
- [x] Oskan töötada erinevates harudes
- [x] Oskan lahendada lihtsa merge-konflikti
- [x] Oskan saata kohaliku projekti GitHubi
- [ ] Soovin veel harjutada keerukamate konfliktide lahendamist

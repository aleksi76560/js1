# js1

Hieman githubista ja gitistä

### Mikä github on?

Kehittäjille erinomainen paikka ylläpitää versiohallintaa.
Branchit ovat olennaisin asia versioinnissa.

### Mikä git on?

Versiohallinnan järjestelmä, joka huolehtii versiosta ja tiedostoista.

### Komennot

1. Kloonataan repositorio githubista lokaalisti -> git clone [repo linkki]
2. Luotiin uusi branchi -> git checkout -b [branchin nimi]
3. Julkaistiin branchi githubiin -> git push --set-upstream origin [branchin nimi]

huomioitavaa: upstream tutki AutoSetup!

4. Tarkistetaan millä branchillä ollaan -> git branch --show-current
5. Vaihdetaan branchista toiseen -> git checkout [olemassa olevan branchin nimi]
---
6. Lisätään muutokset -> git add .
7. Muutos ja sen viesti -> git commit -m "oma-viesti"
8. Julkaistaan muutos -> git push
Huomioitavaa: Ota selvää push.autoSetupRemote
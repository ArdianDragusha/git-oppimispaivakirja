# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Minulla oli vaikeaa päästä alkuun. Minulla oli myös aluksi ongelmia virheilmoitusten kanssa esim. "dubious ownership", mutta tajusin että olin unohtanut tehdä git init. Mielestäni oli aika selvä tehtävä, ei vaikuttanut hirveän vaikealta, opin samalla pari uutta asiaa, jotka en ennalta osannut, mutta seuraamalla tehtävänantoa, sain lopuksi tehtyä hyvin.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
|Git init |Tekee uuden paikallinen Git-repositorion|
|Git add . |Lisää kaikki tiedostot jotka on muokattu, committiin|
|git commit -m ""|Tallentaa commitin ja lisätään viesti, jotta tiedetään mitä commitoidaan|
|git remote add origin ...|Lisää paikallisen repon GitHubiin|
|git remote -v|Näyttää etärepositoriot (tämä oli uusi asia)|
|git push -u origin master|Lähettää master haaraan|
|git fetch|Hakee githubissa tehdyt muutokset, mutta ei yhdistä vielä (uusi asia)|
|git checkout origin/master|Näyttää githubissa olevan repon sisällön|
|git checkout master|Palaa master haaraan|
|git merge origin/master| Yhdistää githubissa olevan repon paikalliseen|
|git status|Näyttää repon statuksen|
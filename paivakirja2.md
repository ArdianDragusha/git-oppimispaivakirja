# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Minulla oli vaikeaa päästä alkuun. Minulla oli myös aluksi ongelmia virheilmoitusten kanssa esim. "dubious ownership", mutta tajusin että olin unohtanut tehdä git init. Mielestäni oli aika selvä tehtävä, ei vaikuttanut hirveän vaikealta, opin samalla pari uutta asiaa, jotka en ennalta osannut, mutta seuraamalla tehtävänantoa, sain lopuksi tehtyä hyvin.

Opin samalla ymmärtämään paremmin branchit, jotka ovat aina olleet vaikeita minulle. Nyt osaan ja yritän tulevaisuudessakin käyttää branchejä eri asioiden tekemiseen. Ymmärsin branchejen hyödyt paremmin myös, koska vanhemmissa kursseissa en nähny branchejen käyttöä niin tärkeäksi, mutta nyt tajusin miten tärkeää se voi olla. 

Mergen kanssa minulla on ollut aina ongelmia, enkä ole ikinä aikaisemmin ymmärtänyt sen idean. Minulla on usein käynyt vanhemmissa projekteissa, että 2 henkilöä tekee git pushia samaan tiedostoon, joka aiheuttaa merge ongelman, jolloin, kukaan meistä ei tiedä mitä on tapahtumassa vaan lähdemme itse poistamaan koodieditorista, siihen saakka, että merge viesti poistuu, mutta nyt ymmärrän asian paremmin, mutta en varmaan ihan vielä täydellisesti.

Minulla oli ongelmia excercisebot:in kanssa nyt tokalla kerralla, enkä saanut sitä toimimaan, mutta koska olen jo kerralleen tehnyt tämän tehtävän ja nyt teen toista kertaa niin, että saisin kaikki samaan repositoryyn tehtyä, niin päätin kopioida toisesta githubista tiedostot tähän. Olen siis kokeillut excercise bottia ja oli mielestäni todella kiinnostava tapa työskennellä.

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
